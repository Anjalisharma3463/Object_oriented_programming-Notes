# Object_oriented_programming-Notes

Introduction of Programming Paradigms:-
Paradigm can also be termed as method to solve some problem or do some task. Programming paradigm is an approach to solve problem using some programming language

1. Imperative programming paradigm: It is one of the oldest programming paradigm. It features close relation to machine architecture. It is based on Von Neumann 
architecture. It works by changing the program state through assignment statements. It performs step by step task by changing state. The main focus is on how to
 achieve the goal. The paradigm consist of several statements and after execution of all the result is stored.

Advantages:-
Very simple to implement
It contains loops, variables etc.

Disadvantage:  
Complex problem cannot be solved
Less efficient and less productive
Parallel programming is not possible

Examples of Imperative programming paradigm:
C Fortran  Basic

 

1 . Imperative programming is divided into three broad categories: Procedural, OOP and parallel processing. These paradigms are as follows:

1(A). Procedural programming paradigm – 
This paradigm emphasizes on procedure in terms of under lying machine model. There is no difference in between procedural and imperative approach. 
It has the ability to reuse the code and it was boon at that time when it was in use because of its reusability.

Examples of Procedural programming paradigm: c , c++ , java..

1(B). Object oriented programming – 
The program is written as a collection of classes and object which are meant for communication. 
It can handle almost all kind of real life problems

Advantages: 
Data security
Inheritance
Code reusability
Flexible and abstraction is also present

Examples of Object Oriented programming paradigm:
Simula : first OOP language ,  Java : C++ : 

1(C). Parallel processing approach – 
Parallel processing is the processing of program instructions by dividing them among multiple processors.

2. Declarative programming paradigm: 
It is divided as Logic, Functional, Database.The focus is on what needs to be done rather how it should be done basically emphasize on what code is actually doing
This is the only difference between imperative (how to do) and declarative (what to do) programming paradigms. 

2(A). Logic programming paradigms – 
It can be termed as abstract model of computation. It would solve logical problems like puzzles, series etc. In logic programming we have a knowledge base
 which we know before and along with the question and knowledge base which is given to machine, it produces result.

 In logical programming the main emphasize is on knowledge base and the problem. 

 predicates
  sumoftwonumber(integer, integer).
clauses
  sumoftwonumber(0, 0).
  sumoftwonumber(N, R) :-
    N > 0,
    N1 is N - 1,
    sumoftwonumber(N1, R1),
    R is R1 + N.

2(B).  Functional programming paradigms – 
The functional programming paradigms has its roots in mathematics and it is language independent. The key principle of this paradigms is the execution of series 
of mathematical functions

Examples of Functional programming paradigm: JavaScript

2(C). Database/Data driven processing approach – 
This programming methodology is based on data and its movement. Program statements are defined by data rather than hard-coding a series of steps.

CREATE DATABASE databaseAddress;
CREATE TABLE Addr (
    PersonID int,
    LastName varchar(200),
    FirstName varchar(200),
    Address varchar(200),
    City varchar(200),
    State varchar(200)
); 


In comparing procedural programming and object-oriented programming (OOP) in terms of key points, several differences can be highlighted:
 aradigm Focus:
 
OR 

Object-oriented programming – As the name suggests uses objects in programming. Object-oriented programming aims to implement real-world entities like 
inheritance, hiding, polymorphism, etc. in programming. The main aim of OOP is to bind together the data and the functions that operate on them so that no
 other part of the code can access this data except that function.

There are some basic concepts that act as the building blocks of OOPs i.e.
Class
Objects
Encapsulation
Abstraction
Polymorphism
Inheritance
Dynamic Binding
Message Passing


Class:--
A class is a logical entity used to define a new data type. A class is a user-defined type that describes what a particular kind of object will look like. 
Thus, a class is a template or blueprint for an object. A class contains variables, methods, and constructors.Class is a blueprint or a set of instructions
 to build a specific type of object. It is a fundamental concept of Object-Oriented Programming which revolves around real-life entities. Class determines how
 an object will behave and what the object will contain. Data encapsulation is supported with “class”. The class consists of both data and functions.
 The data in a class is called a member, while functions in the class 
are called methods.

class: class keyword is used to create a class in C++.
class_name: The name of the class.
class body: Curly braces surround the class body.
After closing curly braces, a semicolon(;) is used


Data Members:- The variables which are declared in any class by using any fundamental data types (like int, char, float, etc.) or derived data
 types (like class, structure, pointer, etc.) are known as Data Members.

 Methods:- A method is the equivalent of a function in object-oriented programming that is used inside classes. The methods are the actions that perform operations.
 A method accepts parameters as arguments, manipulates these, and then produces an output when the method is called on an object.

 Constructor:-  Constructors are special class functions that perform the initialization of every object. In C++, the constructor is automatically called when
 an object is created. It is a special method of the class because it does not have any return type. It has the same name as the class itself
 

practical use:-  
Classes are very useful in programming. Consider the example of where you don't want to use just one car but 100 cars. Rather than describing each one in detail
 from scratch, you can use the same car class to create 100 objects of the type 'car'. You still have to give each one a name and other properties, but the basic 
structure of what a car looks like is the same

Object:--
An object is an instance of a Class. It is an identifiable entity with some characteristics and behavior. Objects are the basic units of object-oriented programming.
  It may be any real-world object like a person, chair, table, pen, animal, car, etc. You need to have a class before you can create an object. When a class is
 defined, no memory is allocated, but memory is allocated when it is instantiated (i.e., an object is created).

Syntax to create an object in C++: 
class_name objectName;

Syntax to create an object dynamically in C++: 
class_name * objectName = new class_name();


Features of OOPs:-
Four major object-oriented programming features make them different from non-OOP languages:

1. Abstraction is the property by virtue of which only the essential details are displayed to the user.
2. Inheritance allows you to create class hierarchies, where a base class gives its behavior and attributes to a derived class.
3. Polymorphism ensures that it will execute the proper method based on the calling object’s type.
4. Encapsulation allows you to control access to your object’s state while making it easier to maintain or change your implementation at a later date.


Why do we need object-oriented programming?

To make the development and maintenance of projects more effortless.
To provide the feature of data hiding that is good for security concerns.
We can solve real-world problems if we are using object-oriented programming.
It ensures code reusability



Encapsulation:--
In normal terms, Encapsulation is defined as wrapping up data and information under a single unit. In Object-Oriented Programming, Encapsulation is defined 
as binding together the data and the functions that manipulate them. Encapsulation also leads to data abstraction or data hiding.
Properties of Encapsulation:-- Data Protection:,Information Hiding: 

code;-  In the provided code, the temp class encapsulates the data members a and b, as well as the method solve(). The internal state of the temp objects
 is hidden from external code, and access to that state is provided through the public method solve(), which calculates and returns a value based on the 
object's internal data.


#include <iostream>
using namespace std;
class temp{
     int a;
  int b;
  public:
  int solve(int input){
    a=input;
    b=a/2;
    return b;
  }
};
 
int main() {
  int n;
  cin>>n;
  temp half;
  int ans=half.solve(n);
  cout<<ans<<endl;
    
}


Features of Encapsulation
Below are the features of encapsulation:

We can not access any function from the class directly. We need an object to access that function that is using the member variables of that class. 
The function which we are making inside the class must use only member variables, only then it is called encapsulation.
If we don’t make a function inside the class which is using the member variable of the class then we don’t call it encapsulation.
Encapsulation improves readability, maintainability, and security by grouping data and methods together.
It helps to control the modification of our data members


Encapsulation also leads to data abstraction.:-
#include <iostream>
#include <string>
 
using namespace std;
 
class Person {
  private:
    string name;
    int age;
  public:
    Person(string name, int age) {
      this->name = name;
      this->age = age;
    }
    void setName(string name) {
      this->name = name;
    }
    string getName() {
      return name;
    }
    void setAge(int age) {
      this->age = age;
    }
    int getAge() {
      return age;
    }
};
 
int main() {
  Person person("John Doe", 30);
 
  cout << "Name: " << person.getName() << endl;
  cout << "Age: " << person.getAge() << endl;
 
  person.setName("Jane Doe");
  person.setAge(32);
 
  cout << "Name: " << person.getName() << endl;
  cout << "Age: " << person.getAge() << endl;
 
  return 0;
}

Encapsulation vs Abstraction
while encapsulation focuses on bundling data and methods into a single unit and controlling access to that unit, abstraction focuses on simplifying complex
 systems by hiding unnecessary details and providing a clear, simplified view of essential characteristics.
 Encapsulation is a means of achieving abstraction by hiding implementation details and exposing only the necessary functionality through well-defined interfaces.


Abstraction:::::::::
#include <iostream>
using namespace std;

class Summation {
private:
	// private variables
	int a, b, c; 
public:
	void sum(int x, int y)
	{
		a = x;
		b = y;
		c = a + b;
		cout<<"Sum of the two number is : "<<c<<endl;
	}
};
int main()
{
	Summation s;
	s.sum(5, 4);
	return 0;
}


Abstraction	                                                               vs                                                  encapsultsion
1.	Abstraction is the process or method of gaining the information.	  While encapsulation is the process or method to contain the information.
2.	In abstraction, problems are solved at the design or interface level.      	While in encapsulation, problems are solved at the implementation level.
3.	Abstraction is the method of hiding the unwanted information.	           Whereas encapsulation is a method to hide the data in a single entity or unit along
                                                                                    with a method to protect information from outside.

4.	We can implement abstraction using abstract class and interfaces.	      Whereas encapsulation can be implemented using by access modifier i.e.
                                                                                   private, protected and public.
5.	In abstraction, implementation complexities are hidden using
 abstract classes and interfaces.                                                	While in encapsulation, the data is hidden using 
                                                                                                     methods of getters and setters.
6.	The objects that help to perform abstraction are encapsulated.	             Whereas the objects that result in encapsulation need not be abstracted.

remevber trck: method if gaining conataon., problems at level, implememnt these,, hidden , merge.

Encapsulation:::---
#include <iostream>
using namespace std;

class EncapsulationExample {
private:
	// we declare a as private to hide it from outside
	int a; 

public:
	// set() function to set the value of a
	void set(int x) 
	{
		a = x;
	}

	// get() function to return the value of a
	int get() 
	{
		return a;
	}
};

// main function
int main() 
{
	EncapsulationExample e1;

	e1.set(10);

	cout<<e1.get();
	return 0;
}





Access Specifier:-

Access Specifiers in a class are used to assign access to the class members. It sets some restrictions on the class members from accessing the outside 
functions directly. Access specifiers have a vital role in securing data from unauthorized access.
It allows us to determine which class members are accessible to other classes and functions and which are not.

There are three types of access modifiers available in C++: 
Public
Private
Protected

Static Member Functions
● We can also declare the member function as static.
● Static member functions have following properties:
– They can have access to only other static members declared in 
same class.
– They can be called using class name.

Constructor:-                                                           

It is a block of code that initializes a newly created object.
It has the same name as the class name.
It has no return type.
It is called implicitly at the time of object creation
In the case of a method, no default method is provided.


   Method:--

It is a group of statements that can be called at any point in the program using its name to perform a specific task.
It should have a different name than the class name.
It needs a valid return type if it returns a value; otherwise void.
If a constructor is not present, a default constructor is provided by Java , but It is called explicitly by the programmer by making a method call


Class:--
Class is the blueprint of an object. It is used to create objects.
No memory is allocated when a class is declared.
A class is a group of similar objects.
Class is a logical entity.
A class can only be declared once.
An example of class can be a car.

object:-
Objects of the class car can be BMW, Mercedes, Ferrari, etc.
An object is an instance of the class.
Memory is allocated as soon as an object is created.
An object is a real-world entity such as a book, car, etc.
An object is a physical entity.
Objects can be created many times as per requirement.


Abstraction in C++::--
Abstraction means displaying only essential information and hiding the details. Data abstraction refers to providing only essential information about 
the data to the outside world, hiding the background details or implementation.


 Types of Abstraction:
Data abstraction – This type only shows the required information about the data and hides the unnecessary data.
Control Abstraction – This type only shows the required information about the implementation and hides unnecessary information.


 Advantages of Data Abstraction::-
Helps the user to avoid writing the low-level code
Avoids code duplication and increases reusability.
Can change the internal implementation of the class independently without affecting the user.
Helps to increase the security of an application or program as only important details are provided to the user.
It reduces the complexity as well as the redundancy of the code, therefore increasing the readability.


Polymorphism::--
The word “polymorphism” means having many forms. In simple words, we can define polymorphism as the ability of a message to be displayed in more than one form
Types of Polymorphism::--
1. Compile-time Polymorphism
2. Runtime Polymorphism


1.A. Function Overloading
When there are multiple functions with the same name but different parameters, then the functions are said to be overloaded, hence this is known
 as Function Overloading. Functions can be overloaded by changing the number of arguments or/and changing the type of arguments.

1.B. Operator Overloading
C++ has the ability to provide the operators with a special meaning for a data type, this ability is known as operator overloading. For example,
 we can make use of the addition operator (+) for string class to concatenate two strings. We know that the task of this operator is to add two operands.
 So a single operator ‘+’, when placed between integer operands, adds them and when placed between string operands, concatenates them


Almost all operators can be overloaded except a few. Following is the list of operators that cannot be overloaded. 
sizeof
typeid
Scope resolution (::)
Class member access operators (.(dot), .* (pointer to member operator))
Ternary or conditional (?:)

OPERATOR Overloading exampleS::----

 
#include <iostream>
using namespace std;

class Complex {
private:
	int real, imag;

public:
	Complex(int r = 0, int i = 0)
	{
		real = r;
		imag = i;
	}

	// This is automatically called
	// when '+' is used with between
	// two Complex objects
	Complex operator+(Complex const& obj)
	{
		Complex res;
		res.real = real + obj.real;
		res.imag = imag + obj.imag;
		return res;
	}
	void print() { cout << real << " + i" << imag << endl; }
};

// Driver code
int main()
{
	Complex c1(10, 5), c2(2, 4);

	// An example call to "operator+"
	Complex c3 = c1 + c2;   // complex c3 = c1.operator+(c2);
	c3.print();
}

2nd example::---
// C++ program to demonstrate operator overloading
// using dot operator
#include <iostream>
using namespace std;

class ComplexNumber {
private:
	int real;
	int imaginary;

public:
	ComplexNumber(int real, int imaginary)
	{
		this->real = real;
		this->imaginary = imaginary;
	}
	void print() { cout << real << " + i" << imaginary; }
	ComplexNumber operator+(ComplexNumber c2)
	{
		ComplexNumber c3(0, 0);
		c3.real = this->real + c2.real;
		c3.imaginary = this->imaginary + c2.imaginary;
		return c3;
	}
};
int main()
{
	ComplexNumber c1(3, 5);
	ComplexNumber c2(2, 4);
	ComplexNumber c3 = c1 + c2;
	c3.print();
	return 0;
}

CONFUSION IN OPERATOR OVERLOADING ::--

The operator+ function is invoked as c1.operator+(c2). Here, c1 becomes the left-hand side operand, so this pointer inside the function implicitly points to c1.
Accessing Members:

Inside the operator+ function, this->real refers to the real member variable of c1.
c2.real refers to the real member variable of c2.

Conversion Operator: We can also write conversion operators that can be used to convert one type to another type. 

Example: ;;
// C++ Program to Demonstrate the working
// of conversion operator
#include <iostream>
using namespace std;
class Fraction {
private:
	int num, den;

public:
	Fraction(int n, int d)
	{
		num = n;
		den = d;
	}

	// Conversion operator: return float value of fraction
	operator float() const
	{
		return float(num) / float(den);
	}
};

int main()
{
	Fraction f(2, 5);
	float val = f; // this lines calls conversion operator//
	cout << val << '\n';
	return 0;
}

---------------------------
Point(int i = 0, int j = 0)
{
    x = i;
    y = j;
}
This means that if you don't provide any arguments when creating a Point object, it will default to (0, 0)

#***********************************************************not in midsem***********************************************************************************************************#######
TYPES OF OPERATOR OVERLOADING:::===

1. Overloading Unary OperatoR::---In the unary operator function, no arguments should be passed. It works only with one class object. It is the overloading
 of an operator operating on a single operand.

// C++ program to show unary 
// operator overloading 
#include <iostream> 
using namespace std; 

class Distance { 
public: 
	int feet, inch; 

	// Constructor to initialize 
	// the object's value 
	Distance(int f, int i) 
	{ 
		this->feet = f; 
		this->inch = i; 
	} 

	// Overloading(-) operator to 
	// perform decrement operation 
	// of Distance object 
	void operator-() 
	{ 
		feet--; 
		inch--; 
		cout << "\nFeet & Inches(Decrement): " << 
				feet << "'" << inch; 
	} 
}; 

// Driver Code 
int main() 
{ 
	Distance d1(8, 9); 

	// Use (-) unary operator by 
	// single operand 
	-d1; 
	return 0; 
}

Note: d2 = -d1 will not work, because operator-() does not return any value.


2. Overloading Binary Operator
In the binary operator overloading function, there should be one argument to be passed. It is the overloading of an operator operating on two operands.

// C++ program to show binary 
// operator overloading 
#include <iostream> 
using namespace std; 

class Distance { 
public: 
	int feet, inch; 
	
	Distance() 
	{ 
		this->feet = 0; 
		this->inch = 0; 
	} 

	Distance(int f, int i) 
	{ 
		this->feet = f; 
		this->inch = i; 
	} 

	// Overloading (+) operator to 
	// perform addition of two distance 
	// object 
	// Call by reference 
	Distance operator+(Distance& d2) 
	{ 
		// Create an object to return 
		Distance d3; 

		
		d3.feet = this->feet + d2.feet; 
		d3.inch = this->inch + d2.inch; 

		// Return the resulting object 
		return d3; 
	} 
}; 

// Driver Code 
int main() 
{ 
	Distance d1(8, 9); 
	Distance d2(10, 2); 
	Distance d3; 

	// Use overloaded operator 
	d3 = d1 + d2; 

	cout << "\nTotal Feet & Inches: " << 
			d3.feet << "'" << d3.inch; 
	return 0; 
}

*** , d3 = d1 + d2: Here, d1 calls the operator function of its class object and takes d2 as a parameter, by which the operator function
 returns the object and the result will reflect in the d3 object.


3. Overloading Binary Operator using a Friend function
In this approach, the operator overloading function must be preceded by the friend keyword, and declare the function in the class scope.
 Keeping in mind, the friend operator function takes two parameters in a binary operator and varies one parameter in a unary operator. All 
the working and implementation would same as the binary operator function except this function will be implemented outside the class scope.

// C++ program to show binary 
// operator overloading using 
// a Friend Function 
#include <iostream> 
using namespace std; 

class Distance { 
public: 
	
	int feet, inch; 

	Distance() 
	{ 
		this->feet = 0; 
		this->inch = 0; 
	} 

	Distance(int f, int i) 
	{ 
		this->feet = f; 
		this->inch = i; 
	} 

	// Declaring friend function 
	// using friend keyword 
	friend Distance operator + (Distance&, 
								Distance&); 
}; 

// Implementing friend function 
// with two parameters 
// Call by reference 
Distance operator+(Distance& d1, 
				Distance& d2) 
{ 
	// Create an object to return 
	Distance d3; 

	d3.feet = d1.feet + d2.feet; 
	d3.inch = d1.inch + d2.inch; 

	// Return the resulting object 
	return d3; 
} 

// Driver Code 
int main() 
{ 
	Distance d1(8, 9); 
	Distance d2(10, 2); 
	Distance d3; 

	// Use overloaded operator 
	d3 = d1 + d2; 

	cout << "\nTotal Feet & Inches: " << 
			d3.feet << "'" << d3.inch; 
	return 0; 
}
****************************************not in midsem*****************************************************************************************************************************


2. Runtime Polymorphism
This type of polymorphism is achieved by Function Overriding. Late binding and dynamic polymorphism are other names for runtime polymorphism.
 The function call is resolved at runtime

A. Function Overriding
B. Virtual Function


A. functon overriding:--- 
// C++ program for function overriding with data members
#include <bits/stdc++.h>
using namespace std;

// base class declaration.
class Animal {
public:
	string color = "Black";
};

// inheriting Animal class.
class Dog : public Animal {
public:
	string color = "Grey";
};

// Driver code
int main(void)
{
	Animal d = new Dog(); // accessing the field by reference
					// variable which refers to derived
	cout << d.color; // Black
}


In the main() function, Animal d = Dog(); initializes an object d of type Animal using the constructor of Dog.
This might seem confusing, but it's actually creating an object of type Dog and then assigning it to an object of type Animal
This is an example of object slicing. When you assign a derived class object to a base class object
While object slicing occurs at compile-time, the determination of which member function or variable to access (i.e., which version of the member is used)
 is done at runtime.



B. Virtual Function
A virtual function is a member function that is declared in the base class using the keyword virtual and is re-defined (Overridden) in the derived class.

Some Key Points About Virtual Functions:
Virtual functions are Dynamic in nature. 
They are defined by inserting the keyword “virtual” inside a base class and are always declared with a base class and overridden in a child class
A virtual function is called during Runtime

// C++ Program to demonstrate
// the Virtual Function
#include <iostream>
using namespace std;

// Declaring a Base class
class GFG_Base {

public:
	// virtual function
	virtual void display()
	{
		cout << "Called virtual Base Class function"
			<< "\n\n";
	}

	void print()
	{
		cout << "Called GFG_Base print function"
			<< "\n\n";
	}
};

// Declaring a Child Class
class GFG_Child : public GFG_Base {

public:
	void display()
	{
		cout << "Called GFG_Child Display Function"
			<< "\n\n";
	}

	void print()
	{
		cout << "Called GFG_Child print Function"
			<< "\n\n";
	}
};

// Driver code
int main()
{
	// Create a reference of class GFG_Base
	GFG_Base* base;

	GFG_Child child;

	base = &child;

	// This will call the virtual function
	base->GFG_Base::display();

	// this will call the non-virtual function
	base->print();
}


///virtual jiske aage hoga vo call nahi hoga .. default me basse class ka hi call hota half


DIFFERENCE B/W INHERITENCE AND Polymorphism
Polymorphism is that in which we can perform a task in multiple forms or ways. It is applied to the functions or methods.
 Polymorphism allows the object to decide which form of the function to implement at compile-time as well as run-time.

Inheritance	vs Polymorphism
1.	Inheritance is one in which a new class is created (derived class) that inherits the features from the already existing class(Base class).
	Whereas polymorphism is that which can be defined in multiple forms.

2.	It is basically applied to classes.
	Whereas it is basically applied to functions or methods.

3.	Inheritance supports the concept of reusability and reduces code length in object-oriented programming.	
        Polymorphism allows the object to  decide which form of the function to implement at compile-time (overloading) as well as run-time (overriding).

4.	Inheritance can be single, hybrid, multiple, hierarchical and multilevel inheritance.	
          Whereas it can be compiled-time polymorphism (overload) as well as run-time polymorphism (overriding).

5.	It is used in pattern designing.	While it is also used in pattern designing.
6.	Example : The class bike can be inherit from the class of two-wheel vehicles, which is turn could be a subclass of vehicles.  
        Example : The class bike can have method name set_color(), which changes the bike’s color based on the name of color you have entered. 

rricks--: defi, aplied , work ,types, use patter n ,eg.

Friend Function-

If a function is defined as a friend function in C++, then the protected and private data of a class can be accessed using the function.
A class’s friend function is defined outside that class’s scope, but it has the right to access all private and protected members of the class. 
 Even though the prototypes for friend functions appear in the class definition, friends are not member functions.

#include <iostream>
using namespace std;
class Rectangle { 
 private: int length;   
  public:  Rectangle() {
       length = 10; // when object will be created then it will be auto be intialized with 10        }   

 friend int printLength(Rectangle); //friend function declaration 
 //Another way to wrte friend functions input parameters:::__
  friend int printLength(Rectangle, int);

          };
          
int printLength(Rectangle b) {   
     b.length += 10;    
     return b.length;
     }
     
     int main() {    
        Rectangle b; 
        //you cannot create an object like Rectangle obj.printLength(10);
          
         cout << "Length of Rectangle: " << printLength(b) << endl;    
         return 0;
         }
         
  // Output:Length of Rectangle: 20 


Characteristics of friend function:

A friend function can be declared in the private or public section of the class.

It can be called a normal function without using the object.

A friend function is not in the scope of the class, of which it is a friend.

A friend function is not invoked using the class object as it is not in the class’s scope.

A friend function cannot access the private and protected data members of the class directly. It needs to make use of a class object and then access
 the members using the dot operator.

A friend function can be a global function or a member of another class.

 

When should we write our own copy constructor?

C++ compiler provides a default copy constructor (and assignment operator) with class. When we don’t provide an implementation of the copy constructor
 (and assignment operator) and try to initialize an object with the already initialized object of the same class then the copy constructor gets called
 and copies members of the class one by one in the target object. But the problem with the default copy constructor (and assignment operator) is: 
When we have members that dynamically get initialized at run time, the default copy constructor copies this member with the address of dynamically allocated
 memory and not a real copy of this memory.Now, both the objects point to the same memory, and changes in one reflect in another object.
Further, the main disastrous effect is, that when we delete one of these objects another object still points to the same memory, which will be a dangling
 pointer, and memory leak is also a possible problem with this approach


//INHERITENCE::--
The capability of a class to derive properties and characteristics from another class is called Inheritance.

Interitence eg::
// Example: define member function without argument within
// the class

#include <iostream>
using namespace std;

class Person {
  private:
  int id;
  char name[100];

public:
  void set_p()
  {
    cout << "Enter the Id:";
    cin >> id;
    cout << "Enter the Name:";
    cin >> name;
  }

  void display_p()
  {
    cout << endl <<"Id: "<< id << "\nName: " << name <<endl;
  }
};

class Student : private Person {
  char course[50];
  int fee;

public:
  void set_s()
  {
    set_p();
    cout << "Enter the Course Name:";
    cin >> course;
    cout << "Enter the Course Fee:";
    cin >> fee;
  }

  void display_s()
  {
    display_p();
    cout <<"Course: "<< course << "\nFee: " << fee << endl;
  }
};

int main()
{
  Student s; // here we have created obje for child class but member function of parenet class wll also be caled automatically

  s.set_s();
  s.display_s();
  return 0;
}

output::- 
id - 4
name = andjal
course:btech
fee : 100000000

//same code you can werite like this also::--
// Example: define member function without argument outside the class

#include<iostream>
using namespace std;

class Person
{
	int id;
	char name[100];
	
	public:
		void set_p();
		void display_p();
};

void Person::set_p()
{
	cout<<"Enter the Id:";
	cin>>id;
	cout<<"Enter the Name:";
	cin>>name;
}

void Person::display_p()
{
	cout<<endl<<"id: "<< id<<"\nName: "<<name;
}

class Student: private Person
{
	char course[50];
	int fee;
	
	public:
		void set_s();
		void display_s();
};

void Student::set_s()
{
	set_p();
	cout<<"Enter the Course Name:";
	cin>>course;
	cout<<"Enter the Course Fee:";
	cin>>fee;
}

void Student::display_s()
{
	display_p();
	cout<<"\nCourse: "<<course<<"\nFee: "<<fee<<endl;
}

int main()
{
	Student s;
	s.set_s();
	s.display_s();
	return 0;
}

you can write like this alos:::--
// Example: define member function with argument outside the class

#include<iostream>
#include<string.h>
using namespace std;

class Person
{
	int id;
	char name[100];

	public:
		void set_p(int,char[]);
		void display_p();
};

void Person::set_p(int id,char n[])
{
	this->id=id;
	strcpy(this->name,n);	 
}

void Person::display_p()
{
	cout<<endl<<id<<"\t"<<name;
}

class Student: private Person
{
	char course[50];
	int fee;
	public:
	void set_s(int,char[],char[],int);
	void display_s();
};

void Student::set_s(int id,char n[],char c[],int f)
{
	set_p(id,n);
	strcpy(course,c);
	fee=f;
}


void Student::display_s()
{
	display_p();
	cout<<"t"<<course<<"\t"<<fee;
}

main()
{
	Student s;
	s.set_s(1001,"Ram","B.Tech",2000);
	s.display_s();
	return 0;
}

// Inheritance example:::--
// C++ program to demonstrate implementation
// of Inheritance

#include <bits/stdc++.h>
using namespace std;

// Base class
class Parent {
public:
	int id_p;
};

// Sub class inheriting from Base Class(Parent)
class Child : public Parent {
public:
	int id_c;
};

// main function
int main()
{
	Child obj1;

	// An object of class child has all data members
	// and member functions of class parent
	obj1.id_c = 7;
	obj1.id_p = 91;
	cout << "Child id is: " << obj1.id_c << '\n';
	cout << "Parent id is: " << obj1.id_p << '\n';

	return 0;
}


Modes of Inheritance: There are 3 modes of inheritance.

Public Mode: If we derive a subclass from a public base class. Then the public member of the base class will become public in the derived class and protected
            members of the base class will become protected in the derived class. 

Protected Mode: If we derive a subclass from a Protected base class. Then both 
        public members and protected members of the base class will become protected in  the derived class.
Private Mode: If we derive a subclass from a Private base class. Then both public members and protected members of the base class will become Private in the

 Derived class.
Types Of Inheritance:-
Single inheritance
Multilevel inheritance
Multiple inheritance
Hierarchical inheritance
Hybrid inheritance


STATIC DATA MEMBERS:::-

Static data members are class members that are declared using the static keyword. There is only one copy of the static data member in the class,
 even if there are many class objects. This is because all the objects share the static data member. The static data member is always initialized
 to zero when the first class object is created.
OR
Static data members are class members that are declared using static keywords. A static member has certain special characteristics which are as follows:

Only one copy of that member is created for the entire class and is shared by all the objects of that class, no matter how many objects are created.
It is initialized before any object of this class is created, even before the main starts.
It is visible only within the class, but its lifetime is the entire program.

Static  data member :;---

When we define the data member of a class using the static keyword, the data members are called the static data member. A static data member
 is similar to the static member function because the static data can only be accessed using the static data member or static member function.
 And, all the objects of the class share the same copy of the static member to access the static data


static data member eg::-
class Student {
   private:
   int rollNo;
   char name[10];
   int marks;
   public:
   static int objectCount;
   Student() {
      objectCount++;
   }

   void getdata() {
      cout << "Enter roll number: "<<endl;
      cin >> rollNo;
      cout << "Enter name: "<<endl;
      cin >> name;
      cout << "Enter marks: "<<endl;
      cin >> marks;
   }

   void putdata() {
      cout<<"Roll Number = "<< rollNo <<endl;
      cout<<"Name = "<< name <<endl;
      cout<<"Marks = "<< marks <<endl;
      cout<<endl;
   }
};
int Student::objectCount = 0;
int main(void) {
   Student s1;
   s1.getdata();
   s1.putdata();
   Student s2;

   s2.getdata();
   s2.putdata();
   Student s3;

   s3.getdata();
   s3.putdata();
   cout << "Total objects created = " << Student::objectCount << endl; //3
   return 0;
}
 



static member function::-- 
Static Member Function in a class is the function that is declared as static because of which function attains certain properties as defined below:

A static member function is independent of any object of the class. 
A static member function can be called even if no objects of the class exist.
A static member function can also be accessed using the class name through the scope resolution operator.
A static member function can access static data members and static member functions inside or outside of the class.
Static member functions have a scope inside the class and cannot access the current object pointer.
You can also use a static member function to determine how many objects of the class have been created.


example of static member function::--

#include <iostream>  
#include <string.h>  
using namespace std;  
// create class of the Car  
class Car  
{  
private:  
int car_id;  
char car_name[20];  
int marks;  
  
public:  
// declare a static data member  
static int static_member;  
  
Car()  
{  
static_member++;  
}  
  
void inp()  
{  
cout << " \n\n Enter the Id of the Car: " << endl;  
cin >> car_id; // input the id  
cout << " Enter the name of the Car: " << endl;  
cin  >> car_name;  
cout << " Number of the Marks (1 - 10): " << endl;  
cin >> marks;    
}  
  
// display the entered details  
void disp ()  
{  
cout << " \n Id of the Car: " << car_id;  
cout << "\n Name of the Car: " << car_name;  
cout << " \n Marks: " << marks;  
  
}   
};  
  
// initialized the static data member to 0  
int Car::static_member = 0;  
  
 int main ()  
{  
// create object for the class Car  
Car c1;  
// call inp() function to insert values  
c1. inp ();  
c1. disp();  
  
//create another object  
Car c2;  
// call inp() function to insert values  
c2. inp ();  
c2. disp();  
  
  
 cout << " \n No. of objects created in the class: " << Car :: static_member <<endl;  
return 0;  
}  

  Another eg of static member function::-
  // C++ Program to show the working of
// static member functions
#include <iostream> 
using namespace std; 

class Box 
{ 
	private: 
	static int length; 
	static int breadth; 
	static int height; 
	
	public:
	
	static void print() 
	{ 
		cout << "The value of the length is: " << length << endl; 
		cout << "The value of the breadth is: " << breadth << endl; 
		cout << "The value of the height is: " << height << endl; 
	}
}; 

// initialize the static data members 

int Box :: length = 10; 
int Box :: breadth = 20; 
int Box :: height = 30; 

// Driver Code

int main() 
{
	
	Box b; 
	
	cout << "Static member function is called through Object name: \n" << endl; 
	b.print(); 
	
	cout << "\nStatic member function is called through Class name: \n" << endl; 
	Box::print(); 
	
	return 0; 
}

Static variables in a class: As the variables declared as static are initialized only once as they are allocated space in separate static storage so, 
the static variables in a class are shared by the objects. There can not be multiple copies of the same static variables for different objects. Also
 because of this reason static variables can not be initialized using constructors. 

Constant Variables:
There are a certain set of rules for the declaration and initialization of the constant variables:

The const variable cannot be left un-initialized at the time of the assignment. // const int a; wrong
It cannot be assigned value anywhere in the program.  // const int a; a = 5; wrong
Explicit value needed to be provided to the constant variable at the time of declaration of the constant variable. // const int a = 5; right


college notes::::
FRIEND CLASS

#include <iostream>
using namespace std;

// Forward declaration of the class B
class B;

// Class A declaration
class A {
private:
    int a;

public:
    A() : a(0) {}

    // Friend function declaration
    friend class B;

    void display() {
        cout << "Value of class A: " << a << endl;
    }
};

// Class B definition
class B {
private:
    int b;

public:
    B() : b(0) {}

    void setData(A& x, int val) {
        // Class B can access private members of class A
        x.a = val;
    }

    void display() {
        cout << "Value of class B: " << b << endl;
    }
};

int main() {
    A objA;
    B objB;

    // Set data using object of class B
    objB.setData(objA, 10);

    objA.display();

    return 0;
}

##WHY THERE IS A FORWARD DECELERATION ???

Friend Class 2
##########################################################################
#include <iostream>
using namespace std;

// Forward declaration of the class B
//class B;

// Class A declaration
class A {
private:
    int a;

public:
    A() : a(0) {}

    // Friend class declaration
    friend class B;

    void display() {
        cout << "Value of class A: " << a << endl;
    }
};

// Class B definition
class B {
private:
    int b;

public:
    //B() : b(0) {}

    void setData(A& x, int val) {
        // Class B can access private members of class A
        x.a = val;
       // b= b1;
        //cout <<x.a;
    }

    void display() {
        cout << "Value of class B: " << b <<" "<<endl;
    }
};

int main() {
    A objA;
    B objB;

    // Set data using object of class B
    objB.setData(objA,10);
    //objB.setData(objA,10,15);
    

    objA.display();
    objB.display();

    return 0;
}

…………………………………………………………………………….
Access Private member function
####################################################################
#include <iostream>
using namespace std;

// Forward declaration of class B
class B;

// Class A declaration
class A {
private:
    int a;

    // Private member function
    void displayPrivate() {
        cout << "Private member function of class A" << endl;
    }

public:
    A() : a(0) {}

    // Friend class declaration
    friend class B;

    void display() {
        cout << "Value of class A: " << a << endl;
    }
};

// Class B definition
class B {
public:
    void accessPrivateMemberFunction(A& objA) {
        // Class B can access private member function of class A
        objA.displayPrivate();
    }
};

int main() {
    A objA;
    B objB;

    // Call member function of class B to access private member function of class A
    objB.accessPrivateMemberFunction(objA);

    return 0;
}

#########################################################################
Global Function as Friend
#############################################################################include <iostream>
using namespace std;

class MyClass {
private:
    int data;

public:
    MyClass() : data(0) {}

    // Forward declaration of friend function
    friend void friendFunction(MyClass&);

    void displayData() {
        cout << "Data: " << data << endl;
    }
};

// Definition of friend function
void friendFunction(MyClass& obj) {
    obj.data = 5; // Friend function can access private members of MyClass
}

int main() {
    MyClass obj;
    friendFunction(obj);
    obj.displayData(); // Output: Data: 5

    return 0;
}

########################################################################


// C++ Program to demonstrate the
// functioning of a friend class
#include <iostream>
using namespace std;

class GFG {
private:
	int private_variable;

protected:
	int protected_variable;

public:
	GFG()
	{
		private_variable = 10;
		protected_variable = 99;
	}

	// friend class declaration
	friend class F;
};

// Here, class F is declared as a
// friend inside class GFG. Therefore,
// F is a friend of class GFG. Class F
// can access the private members of
// class GFG.
class F {
public:
	void display(GFG& t)
	{
		cout << "The value of Private Variable = "
			<< t.private_variable << endl;
		cout << "The value of Protected Variable = "
			<< t.protected_variable;
	}
};

// Driver code
int main()
{
	GFG g;
	F fri;
	fri.display(g);
	return 0;
}



// C++ program to demonstrate the working of friend function

#include <iostream>
using namespace std;

class Distance {
    private:
        int meter;
        
        // friend function
        friend int addFive(Distance);

    public:
        //Distance() : meter(0) {}
        Distance(){meter =0;}
};

// friend function definition
int addFive(Distance d) {

    //accessing private members from the friend function
    d.meter += 5;
    return d.meter;
}

int main() {
    Distance D;
    cout << "Distance: " << addFive(D);
    return 0;
}

// Add members of two different classes using friend functions

#include <iostream>
using namespace std;

// forward declaration
class ClassB;

class ClassA {
    
    public:
        // constructor to initialize numA to 12
        ClassA() : numA(12) {}
        
    private:
        int numA;
        
         // friend function declaration
         friend int add(ClassA objectA, ClassB objectB);
};

class ClassB {

    public:
        // constructor to initialize numB to 1
        ClassB() : numB(1) {}
    
    private:
        int numB;
 
        // friend function declaration
        //friend int add(ClassA, ClassB);
         friend int add(ClassA objectA, ClassB objectB);
};

// access members of both classes
int add(ClassA objectA, ClassB objectB) {
    return (objectA.numA + objectB.numB);
}

int main() {
    ClassA objectA;
    ClassB objectB;
    cout << "Sum: " << add(objectA, objectB);
    return 0;
}
############################################################################
Member Function of another class as Friend
############################################################################
// C++ program to create a member function of another class
// as a friend function
#include <iostream>
using namespace std;

class base; // forward definition needed
// another class in which function is declared
class anotherClass {
public:
	void memberFunction(base& obj);
};

// base class for which friend is declared
class base {
private:
	int private_variable;

protected:
	int protected_variable;

public:
	base()
	{
		private_variable = 10;
		protected_variable = 99;
	}

	// friend function declaration
	friend void anotherClass::memberFunction(base&);
};

// friend function definition
void anotherClass::memberFunction(base& obj)
{
	cout << "Private Variable: " << obj.private_variable
		<< endl;
	cout << "Protected Variable: " << obj.protected_variable;
}

// driver code
int main()
{
	base object1;
	anotherClass object2;
	object2.memberFunction(object1);

	return 0;
}

########################################################################
Structured PROGRAMMING;;-
Structured Programming is a type of programming that generally converts large or complex programs into more manageable and small pieces of code.
These small pieces of codes are usually known as functions or modules or sub-programs of large complex programs.
It is known as modular programming and minimizes the chances of function affecting another.

example::-
// C program to demonstrate the
// structured programming
#include <stdio.h>

// Function for addition
int sum(int a, int b)
{
	return a + b;
}

// Function for Subtraction
int sub(int a, int b)
{
	return a - b;
}

// Driver Code
int main()
{
	// Variable initialisation
	int a = 10, b = 5;

	int add, minus;

	// Function Call
	add = sum(a, b);
	minus = sub(a, b);

	printf("Addition = %d\n", add);
	printf("Subtraction = %d\n", minus);
	return 0;
}

############
Unstructured Programming: 

Unstructured Programming is a type of programming that generally executes in sequential order i.e., these programs just not jumped from any line of code
 and each line gets executed sequentially. It is also known as non-structured programming that is capable of creating turning-complete algorithms.

// C program to demonstrate the
// unstructured programming

#include <stdio.h>

// Driver Code
int main()
{
	// Variable initialisation
	int a = 10, b = 5;
	int add, minus;

	// Operations performed
	add = a + b;
	minus = a - b;

	printf("Addition = %d\n", add);
	printf("Subtraction = %d\n", minus);
	return 0;
}


Structured Programming  VS Unstructured Programming

1. It is basically a subset of procedural programs.
 || It is basically a procedural program. 
2. In this, programmers are allowed to code a program simply by dividing the program into modules or smaller units.
 ||	In this, programmers are not allowed code divide programs into small units. Instead, the program should be written as a single continuous block
         without any breakage.
3. It is more user-friendly and easy to understand as compared to unstructured programming.
   ||	It is less user-friendly and little hard to understand as compared to structured programming.

4. It is easier to learn and follow.||	It is difficult to learn and follow
5. Its advantages include reduce complexity, facilitate debugging, increase programmer productivity programs, etc.||	Its advantages include its speed. 
6. Such programs can be used for small and medium-scale projects and also for complex projects.
 ||	Such programs cannot be used for medium   and complex projects. Instead, they can be used for small and easier projects. 

7.These programs do not allow code duplication.	|| These programs allow code duplication.  
8. Structured programs use a greater number of data types as compared to unstructured programS. 
     ||	Unstructured programs use a limited number of data types as compared to structured programs.  
9. It does not use GOTO to control the flow of execution. Instead, it uses loops.  ||	It uses GOTO to control the flow of execution.
10. It produces readable code.	|| It hardly produces readable code.
11. It does not provide full freedom to programmers to program as they want. || 	It provides full freedom to programmers to program as they want.

abstract data type::--Abstract Data type (ADT) is a type (or class) for objects whose behavior is defined by a set of values and a set of operations.

VISIBILTY MODE:- When a base class is derived by a derived class with the help of inheritance, the accessibility of base class by the derived class 
is controlled by visibility modes.

Characteristics of objects ::--
1. Identity means that each object has its own object identifier and can be differentiated from all other objects. Each object's name, or identity,
    is unique and distinct from other objects.
2. State refers to the properties of an object. For example, values of variables in the object contain data that can be added, changed or deleted.
3. Behavior refers to actions that the object can take. For example, one object can respond to another object to carry out software functions.

Some of the things in programming that can be defined as objects include the following:

variables, which hold values that can be changed;
data structures, which are specialized formats used to organize and process data;
functions, which are named procedures that perform a defined task; and
methods, which are programmed procedures that are defined as components of a parent class and are included in any instance of that class.


Array of Objects in C++ with Examples
An array in C/C++ or be it in any programming language is a collection of similar data items stored at contiguous memory locations and elements 
   can be accessed randomly using indices of an array.  
Array of Objects in C++ with Examples
An array in C/C++ or be it in any programming language is a collection of similar data items stored at contiguous memory locations and elements
   can be accessed randomly using indices of an array.  

Syntax::-
className ObjectName[number of objects];
The Array of Objects stores objects. An array of a class type is also known as an array of objects.

// C++ program to implement 
// the above approach
#include<iostream>
using namespace std;

class Employee
{
int id;
char name[30];
public:

// Declaration of function
void getdata();

// Declaration of function
void putdata();
};

// Defining the function outside 
// the class
void Employee::getdata()
{ 
cout << "Enter Id : ";
cin >> id;
cout << "Enter Name : ";
cin >> name;
}

// Defining the function outside 
// the class
void Employee::putdata()
{
cout << id << " ";
cout << name << " ";
cout << endl;
}

// Driver code
int main()
{
// This is an array of objects having
// maximum limit of 30 Employees
Employee emp[30]; 
int n, i;
cout << "Enter Number of Employees - ";
cin >> n;

// Accessing the function
for(i = 0; i < n; i++) 
	emp[i].getdata();

cout << "Employee Data - " << endl;

// Accessing the function
for(i = 0; i < n; i++) 
	emp[i].putdata();
}


ExamplE-2::--
// C++ program to implement
// the above approach
#include<iostream>
using namespace std;
class item
{
char name[30];
int price;
public:
void getitem();
void printitem();
};

// Function to get item details
void item::getitem()
{
cout << "Item Name = ";
cin >> name;
cout << "Price = ";
cin >> price; 
}

// Function to print item
// details
void item ::printitem()
{
cout << "Name : " << name << 
		"\n";
cout << "Price : " << price << 
		"\n";
}

const int size = 3;

// Driver code
int main()
{
item t[size];
for(int i = 0; i < size; i++)
{
	cout << "Item : " << 
			(i + 1) << "\n";
	t[i].getitem();
}

for(int i = 0; i < size; i++)
{
	cout << "Item Details : " << 
			(i + 1) << "\n";
	t[i].printitem();
}
}

Advantages of Array of Objects: 

The array of objects represent storing multiple objects in a single name.
In an array of objects, the data can be accessed randomly by using the index number.
Reduce the time and memory by storing the data in a single variable.

Passing an Object as argument
To pass an object as an argument we write the object name as the argument while calling the function the same way we do it for other variables.
function_name(object_name);

// C++ program to show passing
// of objects to a function

// C++ program to show passing
// of objects to a function

#include <bits/stdc++.h>
using namespace std;

class Example {
public:
  int a;

  // This function will take
  // an object as an argument
   void add(Example &E)
  { 
    E.a = E.a + a; // yaha have to pass with reference
    // this->a = this->a + E.a; //yaha dont need to pass  by reference
  }
};

// Driver Code
int main()
{
  // Create objects..
  Example E1, E2;
  // Values are initialized for both objects...
  E1.a = 50;
  E2.a = 100;

  cout << "Initial Values \n";
  cout << "Value of object 1: " << E1.a
    << "\n& object 2: " << E2.a
    << "\n\n";

  // Passing object as an argument
  // to function add()
  E2.add(E1);

  // Changed values after passing
  // object as argument
  cout << "New values \n";
  cout << "Value of object 1: " << E1.a
    << "\n& object 2: " << E2.a
    << "\n\n";

  return 0;
}

 
 Output
Initial Values 
Value of object 1: 50
& object 2: 100

New values 
Value of object 1: 50
& object 2: 150   //The change happens to E2 because the add function is called on E2


//constructor overloading...

#include <iostream>
using namespace std;

class Box {
private:
    double length;
    double width;
    double height;

public:
    // Default constructor
    Box() {
        length = 1.0;
        width = 1.0;
        height = 1.0;
    }

    // Parameterized constructor
    Box(double l, double w, double h) {
        length = l;
        width = w;
        height = h;
    }

    // Constructor with a single parameter (for a cube)
    Box(double side) {
        length = width = height = side;
    }

    // Function to calculate volume
    double volume() {
        return length * width * height;
    }
};

int main() {
    // Creating objects using different constructors
    Box box1; // Default constructor
    Box box2(3.0, 4.0, 5.0); // Parameterized constructor
    Box box3(2.5); // Constructor for a cube

    // Calculating volumes
    double volume1 = box1.volume();
    double volume2 = box2.volume();
    double volume3 = box3.volume();

    // Displaying volumes
    cout << "Volume of box1: " << volume1 << endl;
    cout << "Volume of box2: " << volume2 << endl;
    cout << "Volume of box3: " << volume3 << endl;

    return 0;
}

/// destructor/.........
#include <iostream>

class MyClass {
private:
    int* data;

public:
    MyClass() {
        std::cout << "Constructor called" << std::endl;
        data = new int[5];
    }

    ~MyClass() {
        std::cout << "Destructor called" << std::endl;
        delete[] data;
    }

    void setData(int value, int index) {
        data[index] = value;
    }

    void displayData() {
        std::cout << "Data: ";
        for (int i = 0; i < 5; ++i) {
            std::cout << data[i] << " ";
        }
        std::cout << std::endl;
    }
};

int main() {
    MyClass obj;
    obj.setData(1, 0);
    obj.setData(2, 1);
    obj.setData(3, 2);
    obj.setData(4, 3);
    obj.setData(5, 4);
    obj.displayData();

    return 0;
} 

 QUESTION-- implement a class called rectangle that represents a rectangle shape. the class should have memer variavles for length and width , 
            member functions to calculate the area and perimenter m and appropriate constructors and member functions to access the data members.

#include <iostream>

class Rectangle {
private:
    double length;
    double width;

public:
    // Default constructor
    Rectangle() : length(0.0), width(0.0) {}

    // Parameterized constructor
    Rectangle(double l, double w) : length(l), width(w) {}

    // Destructor (not explicitly needed for this example)
    //~Rectangle() {}

    // Getter functions
    double getLength() const {
        return length;
    }

    double getWidth() const {
        return width;
    }

    // Setter functions
    void setLength(double l) {
        length = l;
    }

    void setWidth(double w) {
        width = w;
    }

    // Member function to calculate area
    double calculateArea() const {
        return length * width;
    }

    // Member function to calculate perimeter
    double calculatePerimeter() const {
        return 2 * (length + width);
    }
};

int main() {
    // Create a rectangle object using the default constructor
    Rectangle rect1;
    
    // Set length and width using setter functions
    rect1.setLength(5.0);
    rect1.setWidth(3.0);

    // Access and display length and width using getter functions
    std::cout << "Length of rect1: " << rect1.getLength() << std::endl;
    std::cout << "Width of rect1: " << rect1.getWidth() << std::endl;

    // Calculate and display area and perimeter
    std::cout << "Area of rect1: " << rect1.calculateArea() << std::endl;
    std::cout << "Perimeter of rect1: " << rect1.calculatePerimeter() << std::endl;

    // Create a rectangle object using the parameterized constructor
    Rectangle rect2(4.0, 6.0);

    std::cout << "\nLength of rect2: " << rect2.getLength() << std::endl;
    std::cout << "Width of rect2: " << rect2.getWidth() << std::endl;
    std::cout << "Area of rect2: " << rect2.calculateArea() << std::endl;
    std::cout << "Perimeter of rect2: " << rect2.calculatePerimeter() << std::endl;

    return 0;
}



WRITE A C++ PROGRAM BASED ON OBJECT ORIENDTED APPROACH IN WHICH USER ENTERS THE NUMBERS AND PROGRAM WILL REVERESE THE NUMBER. AFTER REVERSING THE NUMBER,
 TSHOW THE SUM OF ALL NUMBERS..?

#include <iostream>

class NumberHandler {
private:
    int num;

public:
    // Function to input number from the user
    void inputNumber() {
        std::cout << "Enter a number: ";
        std::cin >> num;
    }

    // Function to reverse the number and calculate sum of digits
    int reverseNumberAndSum() {
        int originalNum = num;
        int reversedNum = 0;
        int digit, sum = 0;

        while (num != 0) {
            digit = num % 10;   // Extract the last digit
            reversedNum = (reversedNum * 10) + digit; // Build the reversed number
            sum += digit;   // Add the digit to the sum
            num = num / 10; // Move to the next digit
        }

        std::cout << "Reverse of " << originalNum << " is " << reversedNum << std::endl;
        return sum;
    }
};

int main() {
    NumberHandler nh;
    nh.inputNumber();
    int sum = nh.reverseNumberAndSum();
    std::cout << "Sum of digits of the reversed number: " << sum << std::endl;
    return 0;
}


how private data of a class can v=be accessed from ooutside of the class ?
 write c++ program of defining the concept of friend fucntion in c++ eith a suitale consise eg

#include <iostream>

// Forward declaration of the class
class MyClass;

// Friend function declaration
void displayPrivateData(const MyClass& obj);
//we can comment out these abvode two line of code.......................
class MyClass {
private:
    int privateData;

    // Declaring displayPrivateData() function as a friend of MyClass
    friend void displayPrivateData(const MyClass& obj);

public:
    MyClass(int data) : privateData(data) {}

    // No need to define getter function for privateData as friend function can access private members
};

// Definition of the friend function
void displayPrivateData(const MyClass& obj) {
    std::cout << "Private data accessed from friend function: " << obj.privateData << std::endl;
}

int main() {
    MyClass obj(10);
    
    // Accessing privateData using friend function
    displayPrivateData(obj);

    return 0;
}





write a c++ programm to display the area of rectangle by using a class name d Area with two member functions as per following details::
a) The frst function named as rectangle witll takes the length and breadth of the rectangle as parameters .
b) the second functon named as cal_area returns the area of rctangel.
c) assign proper data types to data members of the   classes. there should e two functions one to inpyt/get data and the other to display the dta.
d) in main() create three objects of each class and assign data and then display the data od reach object by callin g the pcorrespoinding functions /

#include <iostream>

class Area {
private:
    double length;
    double breadth;

public:
    // Function to input length and breadth
    void setRectangle(double len, double brd) {
        length = len;
        breadth = brd;
    }

    // Function to calculate area
    double cal_area() {
        return length * breadth;
    }

    // Function to display data
    void displayData() {
        std::cout << "Length: " << length << std::endl;
        std::cout << "Breadth: " << breadth << std::endl;
        std::cout << "Area: " << cal_area() << std::endl;
    }
};

int main() {
    Area obj1, obj2, obj3;

    // Set data for obj1
    obj1.setRectangle(5.0, 3.0);

    // Set data for obj2
    obj2.setRectangle(7.5, 4.2);

    // Set data for obj3
    obj3.setRectangle(10.0, 6.0);

    // Display data for obj1
    std::cout << "Data for obj1:" << std::endl;
    obj1.displayData();
    std::cout << std::endl;

    // Display data for obj2
    std::cout << "Data for obj2:" << std::endl;
    obj2.displayData();
    std::cout << std::endl;

    // Display data for obj3
    std::cout << "Data for obj3:" << std::endl;
    obj3.displayData();
    std::cout << std::endl;

    return 0;
}


##Features of object oriented programming

  
Object-oriented programming (OOP) is a programming paradigm based on the concept of "objects", which can contain data (attributes or properties)
 and code (methods or functions). Here are some key features of object-oriented programming:

Encapsulation: Encapsulation refers to the bundling of data and methods that operate on the data into a single unit or object. 
It allows for the hiding of internal state and requires all interactions to occur through well-defined interfaces. Encapsulation helps in 
achieving data abstraction and information hiding.

Abstraction: Abstraction refers to the process of hiding the complex implementation details and showing only the essential features of the object.
 It allows programmers to focus on what an object does rather than how it does it. Abstract classes and interfaces provide mechanisms for achieving
 abstraction in OOP.

Inheritance: Inheritance is a mechanism in which a new class inherits properties and behaviors (methods) from an existing class. The class that is
 inherited from is called the superclass or base class, and the class that inherits is called the subclass or derived class. Inheritance promotes 
code reusability and supports the concept of "is-a" relationships.

Polymorphism: Polymorphism allows objects of different classes to be treated as objects of a common superclass. It enables methods to be written
 to manipulate objects of a certain class to also manipulate objects of its subclasses without needing to know the specific subclass at compile 
time. Polymorphism is often achieved through method overriding and method overloading.

Class: A class is a blueprint for creating objects (instances) that share the same attributes and behaviors. It defines the properties and methods 
that all objects of that class will have. Classes act as templates for creating objects in OOP.

Object: An object is an instance of a class. It represents a unique entity with its own state (attributes) and behavior (methods). Objects can
 interact with each other through method calls and can also communicate by sending messages.

Message Passing: In OOP, objects communicate with each other by sending messages. A message is a request for an object to invoke one of its methods.
 Message passing is a key mechanism for achieving encapsulation and modularity in object-oriented systems.


# Basics-of-CPP

### Hello World and Calculator
**Experiment 1**

**AIM -**
To Print "Hello World" and program a simple calculator in C++

### Theory

C++ is a general-purpose, high-performance programming language that builds on the foundation of the C language. Developed by Bjarne Stroustrup in 1979. C++ is a cross-platform language used to create high-performance applications. It supports object-oriented programming.

This experiment consists of two practicals namely printing of `"Hello World"` and making of simple calculator program.

### Experiment 1 A: Hello World - 
In the hello world program , the `cout` function from the iostream library is used to print output. The iostream library in C++ is a library for input and output operations.

### Experiment 1 B: Simple Calculator - 
Arithmetic operators`(+,-,/,*)` were used to create calculator program and `cin` function is used to receive inputs from the user.
//Print hello world
#include<iostream>
using namespace std;
int main()
{
    cout<< "Hello World!";
    return 0;
}


 
// Input from user
#include<iostream>
using namespace std;
int main()
{
    string a;
    cout << "Enter your name ";
    getline(cin,a);
    cout<<"Hello  " <<a;
    return 0;
}

//Calculator 
#include<iostream>
using namespace std;
int main()
{ float a,b,c,d,e,f;
    cout<<"enter first number ";
    cin >> a;
    cout<< "enter second number ";
    cin >> b;
    c = a+b ;
    cout << "Sum is: " <<c<<endl;
    d = a-b;
    cout<< "Difference is: "<<d<<endl;
    e = a*b;
    cout<<"Product is:" << e <<endl;
    f = a/b;
    cout<<"Quotient is: "<<f<<endl;
    return 0;
}
Output
User Input
User Input

Hello World
hello

Calculator
Exp 1 calci

Conclusion
We learnt how to take input from user and print it, we learnt to use basic operators like +, - , * and /.

About
No description, website, or topics provided.
Resources
 Readme
 Activity
Stars
 0 stars
Watchers
 1 watching
Forks
 0 forks
Report repository
Releases
No releases published
Packages
No packages published
Languages
C++
100.0%
Footer


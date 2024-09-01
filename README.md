AIM
To learn about VS code and getting input from user and displaying it.

Software Used
VS Code and Cpp online Compiler

Problem Statement
1.) Write a program to print simple 'Hello world' message.

2.) Write a program to get the input from user and displaying it.

3.) Write a program to create a basic calculator.

Theory
To print a message or output we use 'cout' .

The namespace is used to decrease or limit the scope of any variable or function.

'endl' is used to move the cursor to the new line.

Program
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


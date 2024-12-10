1.1] Even or odd.

A] Code : -

(dev)

#include <iostream>

using namespace std;

int main() {

int num;

cout<<"\nEnter no to check even or odd: ";

cin>>num;

if (num%2==0){

cout<<num<<" is an even number."<<endl;

}

else{

}

cout<<num<<" is an odd number."<<endl;

return 0;

}
------------------------------------------------------------------------
1.2] Sum & Average.

A] Code : -

}

#include <iostream>

using namespace std;

int main()

{

int i, sum = 0, avg;

for(i=1; i <= 10; i++)

{

sum += i;

cout<<i<<"";
}
avg-sum/--i;

cout<<"\nSum = "<<sum;

cout<<"\nAverage = "<<avg;
}

-----------------------------------------------------------------------------------------------
1.3] Prime or Composite:

#include <iostream>

using namespace std;
{
int main()

int n, i, m = 0, flag = 0;

cout<<"Enter a number to check if its Prime: ":

cin>>n;

m=n / 2 ;

for(i = 2; i <= m; i++)
{


if (n % i == 0)
{

cout<<n<<" is not a Prime Number."<<endl;

flag = 1;

break:
}

}
if (flag == 0)
{
cout<<n<<" is a Prime number. "<<endl;
}
return 0;
}
-----------------------------------------------------------------------------------------------
] Sum, Difference, Product & Quotient.

A] Code : -

#include <iostream> using

namespace std; int main()
{

int a, b;

cout<<"\nEnter the value of A and B: ";

cin>>a>>b;

// Sum (+)

cout<<a<<" + "<<b<<" = "<<a+b<<endl;

// Subtraction (-)

cout<<a<<" - "<<b<<" = "<<a-b<<endl;

// Product (*)

cout<<a<<" "<<b<<" = "<<a*b<<endl;

// Division/Quotient (/)

cout<<a<<" / "<<b<<" = "<<a/b<<endl;

return 0;
}
----------------------------------------------------------------------------------------------------
] FUNCTION OVERLOADING
 Code : -

#include <iostream>

using namespace std;

void print ()
{

cout<<"\n......................";
}

void print (int a)
{

cout<<"\n";

for(int i = 1; i <= a; i++)
{

cout<<"#";
}

}
void print(int a, char c)
{
cout<<"\n";

for(int i = 1; i <= a; i++)
{

cout<<c;
}

}
int main()
{

int x;

cout<<"\nEnter number : ";

cin>>x;

print();

print(x);

print(x, '$');

return 0;

}
-----------------------------------------------------------------------------------------------
] ENCAPSULATION CLASS 
Code:-

#include <iostream>

using namespace std;

class Addition
{

private:

int a, b;

public:

void getNum()
{
cout<<"Enter value of a & b : ";

cin>>a>>b;

}

void printSum()
{

cout<<a<<" + "<<b<<" = "<<a+b<<endl;

}

};

int main()
{
Addition N;

N.getNum();

N.printSum();

return 0;
}
----------------------------------------------------------------------------------------------------
CONSTRUCTOR AND DEATRUCTOR 
Code :-

#include <iostream>

sing namespace std;

class MyClass {

public:

// Constructor MyClass() {

cout << "Constructor called" << endl;
}
// Destructor

-MyClass() {

cout << "Destructor called" << endl;
}
};
int main() {

cout << "Creating an object..." << endl;

MyClass obj;

cout << "Doing some work with the object..." << endl;

cout << "Object is about to go out of scope..."<< endl;

return 0; // Here, the destructor will be called for obj
}
----------------------------------------------------------------------------------------------------
SINGLE INHERITANCE 
CODE :-

#include<iostream>

using namespace std;

class text1
{

public:

int a;

void geta()

{

cout << "\nEnter the value of a: ";

cin >> a;
}

};

class text2 : public text1
{

int b;

public:

void getb ()

{

cout << "\nEnter the value of b: ";

cin >> b;

}

void cal()

{

cout << "\nAddition is = " << a + b;
}

};

int main()

{

text2 t2;

t2.geta();

t2.getb();

t2.cal();
}
----------------------------------------------------------------------------------------------------
MULTIPLE INHERITANCE Code:-

#include <iostream>

using namespace std;

class A
{

public:

int x;

void getx()
{

cout<<"Enter the value of x : ";

cin>>x;

}

};

class B
{

public:

int y:

void gety()
{

cout<<"Enter the value of y : ";

cin>>y:
}

};
class C : public A, public B
{

public:

void sum()
{

cout<<x<<" + "<<y<<" = "<<x+y;

};

int main()
{

C obj;

obj.getx();

obj.gety();

obj.sum();

return 0;
}
----------------------------------------------------------------------------------------------------
OPERATOR OVERLOADING USING FRIEND FUNCTION 

CODE :-

#include<iostream>

using namespace std;

class A
{

private:

int a;

public:

void set_a()
{

a = 5;
} 
void get_a()
{
 cout << a << "\n";
}

friend A operator* (A,  A);

};

A operator* (A ob1, A  ob2)
{

A temp;

temp.a ob1.a * ob2.a;

return temp;

}

int main()
{

A ob1, ob2;

ob1.set_a();

ob2.seta();

cout << "\nThe value of the first object: ";

ob1.get_a();

cout << "\nThe value of the second object: ";

ob2.get_a();

A ob3 = ob1 * ob2;

cout << "\nThe value after calling operator overloading function * is: ";

ob3.get_a();

return 0;
}
----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------

----------------------------------------------------------------------------------------------------
New File at / · Rinku411/Rinku411

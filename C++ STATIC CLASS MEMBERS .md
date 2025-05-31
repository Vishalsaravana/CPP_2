# C++ STATIC CLASS MEMBERS
## PROGRAM STATEMENT :
To write a CPP Program to create class Rectangle and calculate the volume of the rectangle, make use of static member variable in the class Rectangle.

## ALGORITHM :

1.	Start the program.
2.	Define a class Rectangle with a static variable var to count the number of objects created. The class includes a constructor to initialize length, breadth, and height, and a method Volume to calculate the volume.
3.	In the main function, read two sets of dimensions from the user, create two Rectangle objects with these dimensions, and display their volumes.
4.	Print the total number of Rectangle objects created using the static variable var.
5.	End the program.

## PROGRAM :
```
#include <iostream>
usingnamespacestd; class Rectangle {
public:
static double var;
// Constructor definition Rectangle(doublel,doubleb,double h)
{
length=l; breadth=b; height=h;
cout<<"Constructor called."<<endl; var++;

}
double Volume()
{
return length*breadth*height;
}
 
private:
double length; // Length of a box double breadth; // Breadthofa box double height; // Height ofabox
};
double Rectangle::var=0; int main(void)
{
int l,b,h,l1,b1,h1; cin>>l>>b>>h>>l1>>b1>>h1; Rectangle r(l,b,h);
cout<<"Volume :"<<r.Volume()<<endl; Rectangle r1(l1,b1,h1); cout<<"Volume :"<<r1.Volume()<<endl; cout<<"Totalobjects:"<<Rectangle::var;

return 0;
}
```
## OUTPUT :
![image](https://github.com/user-attachments/assets/a7c01c82-8899-4ead-8883-d004801ed043)

## RESULT :
Thus, the C++ program to create class Rectangle and calculate the volume of the rectangle, make use of static member variable in the class Rectangle is created successfull


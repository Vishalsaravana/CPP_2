# C++ DYNAMIC MEMORY ALLOCATION

## PROGRAM STATEMENT :
To write a CPP Program to allocate memory dynamically for a double variable. (Note: p_var = new typename;)

## ALGORITHM :

1.	Start the program.
2.	Define a class var_space with a method allocateSpace that dynamically allocates memory for a double, reads a value from the user, and prints it.
3.	In the main function, create an object of var_space and call allocateSpace.
4.	End the program.

## PROGRAM :
```
#include <iostream> using namespace std; class var_space
{
public:


void allocateSpace()
{
double*ptr=newdouble; cin>>*ptr;
cout<<"Double Value is : "<<*ptr;
}
};
int main()
{
var_space v; v.allocateSpace(); return 0;
}
 ```
## OUTPUT :
![image](https://github.com/user-attachments/assets/52e604b3-ee4a-450a-a31d-06e1d842e2a2)

## RESULT :
Thus, the C++ program to allocate memory dynamically for a double variable is created successfully.
 

# C++ OPERATOR OVERLOADING

## PROGRAM STATEMENT :

To write a CPP Program to overload the '-' operator i.e. a positive value should be turned into a negative value.

## ALGORITHM:  

1.	Start the program.
2.	Define a class rep with integer variables v and v1, and overload the decrement operator (--) to perform custom operations.
3.	In the overloaded -- operator, double the value of v, assign it to v1, then subtract v1 from v and print the result.
4.	In the main function, create an object c1 of class rep, read an integer value into c1.v, and use the overloaded decrement operator on c1.
5.	End the program.

## PROGRAM:
```
#include<iostream> using namespace std; class rep
{
public:
int v,v1;
void operator --()
{
v1=v*2; v=v-v1; cout<<v;
}
};
int main()
{

rep c1; cin>>c1.v;
--c1;
}
```

## OUTPUT :
![image](https://github.com/user-attachments/assets/411f0ed4-709e-41d5-9149-6968996fb191)

## RESULT :
Thus, the C++ program to overload the '-' operator i.e. a positive value should be turned into a negative value is created successfully.



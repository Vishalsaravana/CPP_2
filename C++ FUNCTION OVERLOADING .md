# C++ FUNCTION OVERLOADING

## PROGRAM STATEMENT :

To write a CPP program to overload a function to print Integer data in one and Floating-Point data in another.

## ALGORITHM :

1.	Start the program.
2.	Define a class print with a method dat overloaded to accept either an integer or a float, printing each with a respective label.
3.	In the main function, declare an integer a and a float b, and read their values from the user.
4.	Create an object p of the print class, and call the overloaded dat method to print the integer and float values.
5.	End the program.

## PROGRAM :
```
#include<iostream> using namespace std; class print{
public:
void dat(int n){ cout<<"Integer="<<n<<endl;
}
void dat(float g){
cout<<"Floating Point="<<g<<endl;
}
};
int main(){
int a; float b; print p;
cin>>a>>b; p.dat(a);
p.dat(b); return 0;
}
 ```

## OUTPUT :
![image](https://github.com/user-attachments/assets/580772ad-f983-46df-8015-564c33b313d1)

## RESULT :
Thus, the C++ program to overload a function to print Integer data in one and Floating- Point data in another is created successfully



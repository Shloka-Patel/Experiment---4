# Experiment---4

Aim -> To study and implement C++ Bitwise Operators. <br> 

Software -> Visual Studio Code <br> 

Theory -> Bitwise Operaotors in C++ are used to perform bit-level operations on the operands. <br> 
          Its symbols and functions are as follows: <br> 
          1. & -> Binary AND <br>
          2. | -> Binary OR <br>
          3. ^ -> Binary XOR <br> 
          4. << -> Left Shift  <br> 
          5. >> -> Right Shift <br> 
          6. ~ -> Compelement <br> 

Code:<br>
```
#include<iostream> 
using namespace std; 
int main()  
{ 
int a, b, x, y;
cout<<"Enter a number: ";                       
cin>>a; 
cout<<"Enter another number: ";                 
cin>>b; 
cout<<"Binary AND: "<<(a&b)<<"\n";              
cout<<"Binary OR: "<<(a|b)<<"\n";                
cout<<"Binary XOR: "<<(a^b)<<"\n";               
cout<<"Left Shift: "<<(a<<b)<<"\n";              
cout<<"Right Shift: "<<(a>>b)<<"\n";             
cout<<"Complement of a: "<<(x=~a)<<"\n";        
cout<<"Complement of b is: "<<(y=~b)<<"\n";      
return 0;
}
``` 
Output <br> 

![exp4](https://github.com/Shloka-Patel/Experiment---4/blob/main/Output_4.png) <br> 

Conclusion -> I learnt about bitwise operators. 

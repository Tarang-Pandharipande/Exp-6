# Exp-6
### Aim :
To study and implement C++ decision making statements Loops.

### Theory :
In C++, loops are programming constructs that allow a section of code to be repeated multiple times. 
The primary types of loops in C++ are the for loop, while loop, and do-while loop.

- **For Loop**: Ideal for situations where the number of iterations is known beforehand.
-  It includes an initialization, a condition check, and an increment or decrement operation all in one line, making it concise and easy to read.

- **While Loop**: Best used when the number of iterations is unknown and depends on a condition.
- The loop checks the condition first and then executes the loop body. It continues to loop as long as the condition remains true.

- **Do-While Loop**: Similar to the while loop, but with the key difference that it guarantees the code inside the loop will run at least once.
-  This is because the condition is evaluated after the loop body is executed. This loop is useful when the code needs to run at least once regardless of the condition.

### Code : 
``` //Tarang - 23070123140
#include <iostream>
using namespace std;

int main()
{
// for loop
int i=0;
for(i=0;i<=10;i++){
cout<<i<<endl;
}
cout<<endl;
cout<<endl;

// while loop
int a = 10;
while(a>0)
{
cout<<a<<endl;
a--;
}
cout<<endl;
cout<<endl;

// do-while loop
int b = 0;
do {
cout<<b<<endl;
b+=2;
}
while (b <= 10);

cout<<endl;
cout<<endl;

//nested for loop
int set = 10;
for(int b = 1;b<=set;b++){
for(int c = 1;c<=set;c++){
cout<<b*c<<"\t";
}
cout<<endl;
}
cout<<endl;
cout<<endl;

// nested while loop
int ROWS = 5;

int d = 0;
while (d < ROWS) {
int e = 0;
while (e <= d) {
cout << "* ";
e++;
}
cout << endl;
d++;
}
cout<<endl;
cout<<endl;

// nested for-while loop
int rows = 5;
for (int i = rows; i >= 1; i--) {
int j = 1;
while (j <= i) {
cout << j << " " ;
j++;
}
cout<<endl;
}
// nested do while 
int rowred = 1;
do {
int cols = 1;
do {
cout << "* ";
cols++;
}
while (cols <= 5);
cout <<endl;
rowred++;
} while (rowred <= 3);

return 0;
}
```

### Output : 
![Screenshot 2024-08-05 160441](https://github.com/user-attachments/assets/bf369c93-6716-421f-a423-1d62eaa25246)
![Screenshot 2024-08-05 160425](https://github.com/user-attachments/assets/4ef549f0-675a-43ec-8d94-8e1d44e5db63)

### Conclusion :
Learnt the usage of looping statements and their importance 

EX NO 5 : C PROGRAM TO CALCULATE MARKS AND AVERAGE OF THE STUDENT

AIM:

To write a program to calculate marks and average of the student.

ALGORITHM:

1. Start.
2. Declare three variable value of type int for marks.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Find total and average.
6. Print the result
7. End.

PROGRAM:

#include <stdio.h>

int main() {

 int sub1, sub2, sub3, total;
 
 float average;
 
 scanf("%d %d %d", &sub1,&sub2,&sub3);
 
 total = sub1 + sub2 + sub3;
 
 average = total / 3.0;
 
 printf("\nTotal : %d\n", total);
 
 printf("Average : %.2f\n", average);
 
 return 0;

}

OUTPUT:

![Screenshot 2025-05-12 113221](https://github.com/user-attachments/assets/3109ab17-3376-4271-b59f-e2ff63a80474)

RESULT:

Thus, the program is executed and verified successfully.

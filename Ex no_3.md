EX NO 3: C PROGRAM TO FIND NUMBER OF YEARS BASED ON PRINCIPLE,RATE & SIMPLE INTEREST.

AIM:

To write a C program to find number of years based on principle, rate & simple interest.

ALGORITHM:

1. Start.
2. Declare the variables.
3. Prompt the user to enter a value.
4. Read the value using scanf.
5. Calculate the number of years using the formula:
6. End .

PROGRAM:

#include <stdio.h>

#include <math.h>

int main()

{

float p,n,r,si,ci;

scanf("%f%f%f", &p,&n,&r);

si=((p*n*r)/100);

ci=(p)*(pow((1+ r/100),n));

printf("Simple Interest = %0.2f\nCompound Interest = %0.2f", si,ci);

return 0;

}

OUTPUT:

![Screenshot 2025-05-12 112715](https://github.com/user-attachments/assets/eca53dd1-05ab-4178-bfbb-ea31ca98ed2a)

RESULT:

Thus, the program is executed and verified successfully.

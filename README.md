OBJECTIVE:
The objective of this C program is to calculate
and display the area of a circle based on the
input radius provided by the user. It uses the
formula for the area of a circle, which is π (pi)
times the radius squared.


#include<stdio.h>
 main()
 {
float r,area;
clrscr();
 printf(“ Enter the radius of the circle \n”);
 scanf(“%f”,&r);
 area=3.142*r*r;
 printf(“ The area of a circle =%f”,area);
 }

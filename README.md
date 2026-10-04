//discriminant.c
//this is the code to find the discriminant.
#include<stdio.h>
int main()
{
    float a,b,c;
    float discriminant;
    printf("enter the coefficent of a: ");
    scanf("%f",&a);
    printf("enter the coefficent of b: ");
    scanf("%f",&b);
    printf("enter the coefficent of c: ");
    scanf("%f",&c);
    discriminant = (b*b)-(4*a*c);
    printf("the value of the discriminant is: %f",discriminant);
    return 0;
 } 

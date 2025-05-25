# scanning-of-all-datatypes
#include<stdio.h>
void main()
{
int a;
float b;
char c;
double d;
printf("integer: ");
scanf(" %d",&a);
printf("floating-point number: ");
scanf(" %f",&b);
printf("character: ");
scanf(" %c",&c);
printf("double: ");
scanf(" %lf",&d);
printf("You entered:\n");
printf("Integer: %d\n",a);
printf("Float: %f\n",b);
printf("Character: %c\n",c);
printf("Double: %lf",d);
}

# Dowhile_switch
#include<stdio.h>
void main()
{
int ch,a,b;
printf("Enter first number ");
scanf("%d",&a);
printf("Enter second number ");
scanf("%d",&b);

do
{
printf("Menu \n");
printf(" 1.Addition \n");
printf("2.substraction\n");
printf("3.Multiplication \n");
printf("4.Division \n");
printf("enter your choice ");
scanf("%d",&ch);

switch(ch)
{
case 1:
printf("The addition =%d",a+b);
break;
case 2:
printf("The substraction =%d",a-b);
break;
case 3:
printf("The  multiplication =%d",a*b);
break;
case 4:
printf("The division =%d",a/b);
break;
case 5:
printf("exit");
break;
}
}
while(ch!=5)
}

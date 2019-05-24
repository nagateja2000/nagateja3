#include<stdio.h>
void input(int *a,int *b)
{
printf("enter two numbers\n ");
scanf("%d%d",&*a,&*b);
}
int add(int a,int b)
{
int c;
c=a+b;
return c;
}
int output(int c)
{
printf("sum of two numbers is %d",c);
}
int main()
{
int a,b,c;
input(&a,&b);
c=add(a,b);
output(c);
}





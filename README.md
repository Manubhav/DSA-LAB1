# DSA-LAB1
#include <stdio.h>
long long int input();
 void output(long long int);
int main()
{
	long long int c;
  c= input();
  output(c);
}
long long int input()
{	
  long long int b;
  printf("Enter PRN:");
	scanf("%lld",&b);
	return b;
}
void
 output(long long int a)	
{
	printf("PRN is: %lld",a);
}	

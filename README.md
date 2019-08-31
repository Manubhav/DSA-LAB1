# DSA-LAB1
## PROGRAM TO PRINT INTEGER VALUE EXCEEDING +-2,147,483,647
      #include <stdio.h>
      long long int input();
     void output(long long int);    //RANGE OF LONG LONG INT IS +-9,223,372,036,854,775,807
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


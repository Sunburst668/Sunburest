#include <stdio.h>
void main()
{int a=1;
   int b=0;
   do
 {
	 if(a%3==2&&a%5==3&&a%7==2)
	 {
	   printf("%d\t",a);
    b++;
	if(b==5)
	{
	printf("\n");
	}
  }
  a++;
 }
while(1<=a&&a<=1000);
}

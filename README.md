#include <stdio.h>
int main() 
{
	int a;
	printf("Enter the number:");
	scanf("%d",&a);
	if(a==0)
	  printf("The value is ZERO");
	else
	  if(a<0)
	    printf("The value is NEGATIVE");
	  else
	    printf("The value is POSITIVE");
	return 0;
}

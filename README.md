# ZIP-ZAP-ZOOM
Write a program for ZIP, ZAP and ZOOM game: 
1. If the number is multiple of 3 to display “ZIP”
2.  2. If the number is multiple of 5 to display “ZAP” 
3.  3. If the number is multiple of 3 and 5 to display “ZOOM”

#include<stdio.h>
int main()
{
	int num;
	printf("Enter a number: ");
	scanf("%d",&num);
	if (num % 3 == 0 && num % 5 == 0)
	{
		printf("ZOOM \n",num);
	}
	else if (num % 3 == 0)
	{
		printf("ZIP",num);
	}
	else if (num % 5 == 0)
	{
		printf("ZAP ",num);
	}

	else
	{
		printf("INVALID",num);
	}
	return 0;
}

=========================================================================================

OUTPUT

---------------------------------

Enter a number: 30
ZOOM 

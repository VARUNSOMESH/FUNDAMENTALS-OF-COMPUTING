#include <stdio.h>
int main()
{
	int digit,i,pos=0,pow=1,dec=0,num;
	printf("Enter Binary number: ");
	scanf("%lu",&num);
	int p=num;
	while(num!=0)
	{
		pow=1;
		digit=num%10;
		num=num/10;
		for(i=1;i<=pos;i++)
		{
			pow=pow*2;
		}
		pos++;
		dec=dec+(pow*digit);
	}
	printf("\nDecimal equivalant of %d is %d",p,dec);
	return 0;
}

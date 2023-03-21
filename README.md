#include<stdio.h>

int main()
{
        int a[3];
	int b[2];
	int max, min,min_a, i,x;
	max = 100; 
	min = 2000;
	min_a = 2000;
	for (i = 0; i < 3; i++)
	{
		scanf_s("%d", &a[i]);
		if (a[i] < min) min = a[i]; 
	}
	for (i = 0; i < 2; i++)
	{
		scanf_s("%d", &b[i]);
		if (b[i] < min_a) min_a = b[i];
	}
	x = min + min_a - 50;
	printf("%d",x);

	return 0;

}

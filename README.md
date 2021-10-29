# solid-rectangle-pattern
this is about a c program to print  solid Tritangle pattern 
#include<stdio.h>
int main()
{
	int i,j,n;
	printf("number of rows:");
	scanf("%d",&n);
	for(i=0;i<n;i++)
	{
		for(j=0;j<i;j++)
		{
			printf("01");
		}
		printf("\n");
	}
	return 0;
    
}

OUTPUT:

01
0101
010101
01010101

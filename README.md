# -practice
#include <stdio.h> 
long int fa(int);
int main()
	{
		int a;
		long int b;
		scanf("%d",&a);
		b=fa(a);
		printf("%ld",b); 
	}
long int fa(int x)
	{
		if(x==2)
		return 3;
		else return 2*fa(x-1)+1;
	}

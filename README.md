# lab
#include <stdio.h>
#include <math.h>

int main()
{
	int m, n, a, b, c;

	printf("enter m,n \n");
	scanf("%d", &m);
	scanf("%d", &n);

	a = n++ * m;
	b = n++ < m;
	c = m-- > m;

	printf("Result 1: %d \n", a);
	printf("Result 2: %d \n", b);
	printf("Result 3: %d \n", c);
	return 0;
   
}

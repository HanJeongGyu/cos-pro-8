# cos-pro-8

```c
#include <stdio.h>

int main(void)
{
	int num = 0;
	int i = 2;
	int sum = 0;
	int j = 0;
	int cnt = 0;

	printf("1 ~ num까지의 제차 수열의 합을 구하세요\n\nnum을 입력하세요 : ");
	scanf_s("%d", &num);

	printf("\n\n\nfor문 이용 \n\n\n");


	// sum = sum + i;
	// printf("cnt = %2d, j = %2d, i = %3d, sum = %d\n", cnt, j, i, sum);


	for (i = 1; i <= num; i++)
	{
		j = j + 1;
		sum = sum + i;

		printf("cnt = %2d, j = %2d, i = %3d, sum = %d\n", cnt, j, i, sum);
	}

	printf("\n\n\nwhlie문 이용 \n\n\n");
	i = 2;
	j = 0;
	sum = 0;

	while (i <= num)
	{
		j = j + 1;
		sum = sum + i;

		printf("cnt = %2d, j = %2d, i = %3d, sum = %d\n", cnt, j, i, sum);
		i = i + j;
	}

	printf("\n\n\ndo whlie문 이용 \n\n\n");
	i = 2;
	j = 0;
	sum = 0;

	do
	{
		j = j + 1;
		sum = sum + i;

		printf("cnt = %2d, j = %2d, i = %3d, sum = %d\n", cnt, j, i, sum);
		i = i + j;
	} while (i <= num);

	return 0;
}

/*
	int num = 0;
	int i = 0;
	int sum = 0;

	printf("1 ~ num까지의 합을 구하세요\n\nnum을 입력하세요 : ");
	scanf_s("%d", &num);
	printf("\n\n\nfor문 이용 \n\n\n");

	for (i == 1; i <= num; i++)
	{
		sum = sum + i;
		//printf("%d %d\n", i, sum);
		printf("%d + ", i);
	}

	printf("\b\b = %d\n\n\n", sum); // baskspace를 이용하여 + 지우기

	printf("\n\n\nwhlie문 이용 \n\n\n");
	i = 1; // i 초기화
	sum = 0;
	while (i <= num)
	{
		sum = sum + i;
		//printf("%d %d\n", i, sum);
		printf("%d + ", i);
		i++;
	}

	printf("\b\b = %d\n\n\n", sum); // baskspace를 이용하여 + 지우기

	printf("\n\n\ndo whlie문 이용 \n\n\n");
	i = 1; // i 초기화
	sum = 0;
	do
	{
		sum = sum + i;
		//printf("%d %d\n", i, sum);
		printf("%d + ", i);
		i++;
	} while (i <= num);

	printf("\b\b = %d\n\n\n", sum); // baskspace를 이용하여 + 지우기
	
	return 0;
*/

/*
	int num = 0;
	int i = 2;
	int sum = 0;
	int j = 0;
	int cnt = 0;

	printf("1 ~ num까지의 계차 수열의 합을 구하세요\n\nnum을 입력하세요 : ");
	scanf_s("%d", &num);

	printf("\n\n\nfor문 이용 \n\n\n");
	
	
	// sum = sum + i;
	// printf("cnt = %2d, j = %2d, i = %3d, sum = %d\n", cnt, j, i, sum);
	

for (cnt = 1; cnt <= num; cnt++)
{
	j = j + 1;
	i = i + j;
	sum = sum + i;

	if(i > num) break;

	printf("cnt = %2d, j = %2d, i = %3d, sum = %d\n", cnt, j, i, sum);
}

return 0;
*/
```

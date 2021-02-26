# 20210226

## 1找零錢
```c
#include <stdio.h>
int main()
{
	int a;
	scanf("%d", &a);
	printf("%d=50*%d+5*%d+1*%d\n",a,a/50,a%50/5,a%50%5);
}
```

## 2因數個數
```c
#include <stdio.h>
int main()
{
	int n,a=0;
	scanf("%d", &n);
	for(int i=1;i<=n;i++)
	{
		if(n%i==0)
		{
			a++;
		}
	}
	printf("%d\n", a);
}
```

#include<stdio.h>
main()
{
	int a=0;
	printf("进入学校\n");
	
		printf("想学习吗？（1/0)>:");
	scanf("%d",&a);
	
	if(a==1)
		printf("想学习\n");
		else
		{
		printf("不想学习\n");
		exit(0);
	}
	while(a<100)
	{
		printf("学习:%d\n",a);
		a++;
	}
	if(a>=100)
		printf("好学生\n");
}

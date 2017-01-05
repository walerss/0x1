# 0x1
菜鸟之路
#include<stdio.h>
void main()
{ 
	int a,b,c;
	printf("请输入整数：a=");
	scanf("%d",&a);
	printf("请输入整数：b=");
	scanf("%d",&b);
	if(a>b) c=a;
	if(a<b) c=b;
	printf("c=%d",c);
}

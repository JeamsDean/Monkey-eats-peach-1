# Monkey-eats-peach-1
Monkey eats peach 1
#include<stdio.h>/*包含头文件*/
int main()/*定义主函数*/
{
	int x, n;/*定义整形变量*/
	x = 1;/*最后一天剩了一个桃子*/
	for (n = 9; n >= 0; n--)/*往前推共九天*/
	{
		x = 2*(x + 1);
	}
	printf("第一天摘了%d个桃子", x);
}
/*从最后一天开始计算,每天都吃掉一半后多吃一个*/

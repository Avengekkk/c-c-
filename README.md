# c-primer-plus

//用来确定数的上下溢问题的代码

#include <stdio.h>
#include <float.h>
#include <limits.h>

	int main()
	{

		int big_int = 2147483647;
		//signed int最大值是2的31次方
//可以用while循环来解决这个问题，代码如下：
//int maxint=1;
while(maxint>0)
{maxint++;}
pritnf("%d",maxint-1);
		float big_float = 3.4e39;
		//float最大值  一般是   3.4e39 

		float small_float = 10.0 / 3;
		//float的有效位数是6位

		printf("整数型最大值越界结果%d\n", big_int + 1);    //越界

		printf("浮点数最大越界结果%f\n", big_float);     //越界
//可以用另一种方法得inf;
//float a=1.0;
printf("%f",a/0.0);->得到的是INF，double同理

		printf("float最大有效精度%f\n", small_float);

		printf("float类型最大值%f\n", FLT_MAX);

		printf("int类型的最大值%d\n", INT_MAX);
		
		
		return 0;

	}

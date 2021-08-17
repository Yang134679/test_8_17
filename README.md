# test_8_17
#define _CRT_SECURE_NO_WARNINGS 1
#include <stdio.h>
#include <string.h>
using namespace std;



//int fib(int n)
//{
//	if(n<=2)
//		return 1;
//	else
//		return fib(n-1)+fib(n-2);
//}
//int main()
//{
//	int a=10;
//	scanf("%d",&a);
//	int b=fib(a);
//	printf("b=%d\n",b);
//	return 0;
//}

//int count =0;
//int fib(int n)
//{
//	if(n==3);
//	count++;
//	if(n<=2)
//		return 1;
//	else
//		return fib(n-1)+fib(n-2);
//}
//int main()
//{
//	int a=0;
//	scanf("%a",&a);
//	int f=fib(a);
//	printf("%d\n",count);
//	return 0;
//}

//int factorial(int n)
//{
//	if(n<=1)
//		return 1;
//	else
//		return n*factorial(n-1);
//}
//int main()
//{
//	int m=5;
//	int f=0;
//	scanf("%d",&m);
//	f=factorial(m);
//	printf("%d\n",f);
//	return 0;
//}

//int main()
//{
//	scanf("");
//	printf("");
//	return 0;
//}

//int Strlen(const char *str)
//{
//	if(*str=='0')
//		return 0;
//	else return 1+Strlen(str+1);
//}
//int main()
//{
//	char *p="abcde";
//	int len=Strlen(p);
//	printf("%d\n",len);
//	return 0;
//}

//void print(int n)
//{
//	if(n>9)
//	{
//		print(n/10);
//	}
//	printf("%d ",n%10);
//}
//
//int main()
//{
//	int num=0;
//	scanf("%d",&num);
//	print(num);
//	printf("\n");
//	return 0;
//}

//void new_line()
//{
//	printf("heh\n");
//}
//void three_line()
//{
//	int i=0;
//	for(i=0;i<3;i++)
//	{
//		new_line();
//	}
//}
//int main()
//{
//	three_line();
//	return 0;
//}

//int get_max(int x,int y)
//{
//	return (x>y)?(x):(y);
//}
//
//int main()
//{
//	int num1=10;
//	int num2=20;
//	scanf("%d%d",&num1,&num2);
//	int max= get_max(num1,num2);
//	printf("max=%d\n",max);
//	return 0;
//}


//int main()
//{
//	printf("%d\n",strlen("c:\test\328\test.c"));//结果是14
//	printf("c:\test\328\test.c");//\32被解释成一个转义字符
//	return 0;
//}

//int main()
//{
//	int a,b;
//	scanf("%d%d",&a,&b);
//	printf("%d\n%d\n",a,b);
//	return 0;
//}

//void exchange(int *i,int *p)
//{
//	int q=*i;
//	*i=*p;
//	*p=q;
//}
//int main()
//{
//	int a=1;
//	int b=2;
//	int c=0;
//	exchange(&a,&b);
//	printf("a=%d\nb=%d\n",a,b);
//	c=a+b;
//	printf("c=%d\n",c);
//	return 0;
//}

//int main()
//{
//	//int age=0;
//	//scanf("%d",&age);
//	//printf("%d\n",age);
//	//printf("%d\n",sizeof(int));
//	int num=10;
//	int *p=&num;
//	*p=20;
//	printf("%p\n",*p);
//	printf("%d\n",p);
//	printf("%p\n",p);
//	printf("%p\n",num);
//	printf("%d\n",num);
//	printf("%p\n",&num);//总结：int *p是指针p，指针用来指代地址，p用来存放地址；
//						//		*p是解引用，将p中存放的地址拿出来使用。
//	return 0;
//}


//int main()
//{
//	//cout<<"Hello world"<<endl;
//	printf("Hello world\n");
//	return 0;
//}

//class Std
//{
//private:
//	int num;
//	int score;
//public:
//	void display()
//	{
//		printf("num=%d\n",num);
//		printf("score=%d\n",score);
//	}
//	void setin()
//	{
//		printf("请依次输入学号、成绩，以空格键隔开\n");
//		scanf("%d%d",&num,&score);
//	}
//};
//Std std1,std2;
//
//int main()
//{
//	std1.setin();
//	std2.setin();
//	std1.display();
//	std2.display();
//	return 0;
//}

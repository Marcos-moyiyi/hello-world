#include<iostream>
using namespace std;
#define MAXSIZE 100            //定义一个符号常量 
#define OK 0                   //定义一个符号常量
#define ERROR -1               //定义一个符号常量
typedef int Status;            //定义一个类型 
typedef int Elemtype;          //定义一个类型
typedef struct                 //定义结构体 
{
	Elemtype *data;
	int Lenth;
}SqList;
Status IintList(SqList &L)//顺序表的初始化 
{
	L.data=new Elemtype[MAXSIZE];//为顺序表分配一个大小为MAXSIZE的数组空间 
	if(!L.data) 	return ERROR;//储存分配失败就返回ERROR 
	L.Lenth=0;//长度初始化为0 
	return OK; 
}
int main()
{
	int i;
	SqList L; 
	IintList(L);//调用初始化函数 
	return 0;
}

## 声明一个变量
变量这一概念来源于数学。变量在C语言中可以用来存储计算结果以及参与到运算中去。你可以将变量理解为数学中 “未知数”这一概念，但是与“未知数”不同的是，多数情况下你是知道变量中储存的数值是什么。
### 如何声明一个变量
声明变量的方式如下几种：
* 数据类型 变量名;
* 数据类型 变量名 = 变量值;
##### 示例：声明一个变量
```c
#include<stdio.h>  
int main(void)  
{  
    int a; //声明了一个变量名为a的变量，这个变量的数据类型是int型。
    int b = 14; //声明了一个变量名为b的变量，这个变量的数据类型是int型，它的值为14.
    return 0;  
}
```
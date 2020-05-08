## 算术运算
在C语言中，我们可以进行诸如加减乘除一类的算术运算。

### 算术运算符
* 加法：+
* 减法：-
* 乘法：\*
* 取整：\/
* 取余：%

##### 加法：+
你可以这样进行加法运算
```c
#include<stdio.h>  
int main(void)  
{  
    int a = 1;//声明整型变量a其值为1
    int b = 2;//声明整型变量b其值为2
    int c = a + b;//声明整型变量c其值为 a + b;
    printf("%d",&c);  //输出结果
    return 0;  
}
```
你还可以这样进行加法运算
```c
#include<stdio.h>  
int main(void)  
{  
   
    int c = 1 + 2;//声明整型变量c其值为 1 + 2
    printf("%d",&c);;  //输出结果
    return 0;  
}
```

##### 减法：-
你可以这样进行减法运算
```c
#include<stdio.h>  
int main(void)  
{  
    int a = 1;//声明整型变量a其值为1
    int b = 2;//声明整型变量b其值为2
    int c = a - b;//声明整型变量c其值为 a - b;
    printf("%d",&c);  //输出结果
    return 0;  
}
```
你还可以这样进行减法运算
```c
#include<stdio.h>  
int main(void)  
{  
   
    int c = 1 - 2;//声明整型变量c其值为 1 - 2
    printf("%d",&c);;  //输出结果
    return 0;  
}
```

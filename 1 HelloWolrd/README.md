## HelloWorld
本篇展示了一个最基础的HelloWorld代码是如何写出来的

###### 代码如下
```c
#include<stdio.h>  
int main(void)  
{  
   printf("Hello World!");  
    return 0;  
}
```
正如上面代码所展示的一样，它是一个十分简单的程序。让我们来看看它的结构。  
  

第一行语句\#include\<stdio.h\> 表示将一个名为stido.h的头文件在预编译阶段加入到本程序的头部。作为一个新手，你完全可以不理解什么是头文件，什么又是预编译阶段。
  

第二行语句int main(void)  表示定义一个返回值为int类型的名为main的函数。在这里你可以不理解什么是函数，什么又是返回值，因为这些知识将会在后续篇章中详细讲述。在当前阶段你只要知道C语言的程序是从这里开始执行就可以了。  
  

第四行语句printf(\"Hello World!\")\;  则是本程序输出Hello World的核心，该语句会将它的小括号内的双引号中的字符显示到屏幕上，而在C语言中，单条的语句应以分号\;结尾，这是语法要求，不遵循此要求的程序将会出现语法错误。  
  

第五行语句return 0\; 表示该函数返回了一个0的返回值。作为一个新手，你也可以完全不理解这句话，这些知识将会在后续篇章中详述。  
  
现在，你最应该做的事情就是把这个代码写到你的编辑器上，然后编译并执行它。
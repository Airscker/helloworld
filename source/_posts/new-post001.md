---
title: new post001
author:Airscker
date: 2021-01-31 00:28:12
tags:
---

### Somthing about C#,here is the note of mine:
#### some tips(whatever):
```using System;
using System.Collections.Generic;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
//使用命名空间,注意；不可省略
using demeo;
using ConsoleApp1;

namespace ConsoleApp1
{
    public class Program
    {
        //成员变量
        static int var2;
        //define a Main method ,it mut be defined as static         
        static int Main(string[] args)//返回值可以是int类型或者void类型
        {
            //声明变量
            //局部变量
            int var1;
            //28位精度decimal数据类型
            decimal dec1=1.12m;//m后缀表示decimal类型，不加m会默认存储为double类型，此时报错
            var2 = 100;//对于静态成员变量可以直接调用
            var1 = 100;//成员变量初始化
            int var3=var1;//此处定义了引用类型，改变var3的值会同时改变var1的值，但是string的引用是一个例外
            //Console就是一个类，WriteLine就是Consle类中的一个函数（方法）
            Console.WriteLine("hello world!"+var1) ;//输出内容
            var3 = 200;//此处改变var3的值会改变var1的值
            Console.WriteLine(var1+var1);
            
            Console.ReadLine();//获取输入内容 
            return 0;
        }
    }
}
//define a namespace
namespace demeo
{
    // 类的定义
    class Test1
    {
        
    }
    //一个命名空间内定义多个类
    public class Card
    {

    }
}
```
#### something else:

first we define a class object:
```
class class1{
    string name;
    int age;
}
```
then we can use it to define an object in other part of the whole program：
```
class1 class1_obj = new class1{name="you",age=19};
```



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
//ʹ�������ռ�,ע�⣻����ʡ��
using demeo;
using ConsoleApp1;

namespace ConsoleApp1
{
    public class Program
    {
        //��Ա����
        static int var2;
        //define a Main method ,it mut be defined as static         
        static int Main(string[] args)//����ֵ������int���ͻ���void����
        {
            //��������
            //�ֲ�����
            int var1;
            //28λ����decimal��������
            decimal dec1=1.12m;//m��׺��ʾdecimal���ͣ�����m��Ĭ�ϴ洢Ϊdouble���ͣ���ʱ����
            var2 = 100;//���ھ�̬��Ա��������ֱ�ӵ���
            var1 = 100;//��Ա������ʼ��
            int var3=var1;//�˴��������������ͣ��ı�var3��ֵ��ͬʱ�ı�var1��ֵ������string��������һ������
            //Console����һ���࣬WriteLine����Consle���е�һ��������������
            Console.WriteLine("hello world!"+var1) ;//�������
            var3 = 200;//�˴��ı�var3��ֵ��ı�var1��ֵ
            Console.WriteLine(var1+var1);
            
            Console.ReadLine();//��ȡ�������� 
            return 0;
        }
    }
}
//define a namespace
namespace demeo
{
    // ��Ķ���
    class Test1
    {
        
    }
    //һ�������ռ��ڶ�������
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
then we can use it to define an object in other part of the whole program��
```
class1 class1_obj = new class1{name="you",age=19};
```



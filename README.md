# 一个os实现
学习os所用，打算实现（copy大法）一个基本功能俱全的os

- log: 2019-6-9 完成对gdt表的初始化，并进入了保护模式
- log: 2019-6-10 写获取内存，还是有bug
- log: 2019-6-11 改掉了内存检测的bug
- log: 2019-6-12 初始化一级页表二级页表，映射内核至虚拟空间3gb以上
- log: 2019-6-21 将内核加载进指定内存处，并初始化内核至编译虚拟地址处
- log: 2019-7-5 实现了第一个打印函数，但是在加载内核的时候出了bug，不得不说搞os最恶心的就是debug，忙了一段实验室终于又继续了
- log: 2019-7-7 增加打印整数的函数
- log: 2019-8-2 添加中断符号表，和简单的中断处理程序，初始化8259A芯片，并进行中断测试

---
title: Hare/QBE 中文教程
type: docs
---

# Hare/QBE 中文教程

{{< hint danger >}}
**this docuemnt is on progress, please keep patient**  
{{< /hint >}}

{{< columns >}}
## What is Hare

Hare aims to become a 100-year programming language

[Why Hare]()
<--->

## What is QBE

QBE is a light compiler backend, short for Quentin's Bizarre Experiment. 
{{< /columns >}}


{{< columns >}}
## Hare 社区与生态

- [x] helios 

<--->
## QBE 社区与生态

- [x] cprog

{{< /columns >}}

## 为啥要写这个教程

[官方教程](https://harelang.org/tutorials/introduction) 已经覆盖了 hare 的基本语法，
如果你通读了一遍或者几遍，应该可以写一些 demo 程序，或者尝试用 Hare stdlib 写一些功能性的东西。
但是，此教程并没有告诉你：

1. Hare 程序是如何编译的、如何执行的
2. Hare 编译器是如何工作的？
3. Hare 后端 QBE 是如何工作的？
4. Hare 语言如何与 C 交互
5. Hare 语言 ...  

作为 Hare 语言的第一个中文教程（可能是吧？）希望在本文档中提供如下内容：

1. Hare 语言基本语法
2. Hare 语言编程实战
   - Hare 语言编译过程与运行时分析
   - 用 Hare 写个 kexec-tools 
   - 如何与 C 语言交互 - Hare SDL2 binding
   - 如何编写 freestanding 程序- 写个 kernel 
3. Harec 编译器
   - lex() parse() check() gen()
   - 理解一个 ha 语法在 harec 中如何实现
4. QBE 后端
   - QBE IR 教程
   - QBE IR 后端实现分析 (big one)
   -  
5. Hare 社区文化
6. and More
   - 
That's all. Let's Go.

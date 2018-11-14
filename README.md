# DataStructure

数据结构实验作业

## 实验1 结构体操作练习

有5 个学生，每个学生的数据包括学号、姓名、3 门课的成绩。

从键盘输入5个学生数据，要求输出每个学生的各项数据及3 门课平均成绩，以及最高平均分的学生各项数据（包括学号、姓名、3 门课的成绩、平均分数）

## 实验2  顺序表合并

将两个已经按从小到大顺序排好序的顺序表l1, l2合并成一个新的排好序的顺序表l3。

**要求**:

+ 在O(n)时间复杂度内完成。例如不得先连接二表，再整体排序。
+ l1和l2能够由用户输入。

例如:

 l1: (1, 9, 11, 12)

 l2: (2, 7, 13, 20)

合并成l3: (1, 2, 7, 9, 11, 13, 12, 20)

## 实验3 链表合并

将两个已经按从小到大顺序排好序的链表 l1, l2 合并成一个新的排好序的链表 l3 。  

**要求**:

+ 在 O(n) 时间复杂度内完成。例如不得先连接二表，再整体排序。  
+ l1 和 l2 能够由用户输入。  
+ 合并后的新链表不占用存储空间，即直接将 l1 和 l2 链接在一起  

## 实验4 八皇后问题

八皇后问题是十九世纪著名的数学家高斯提出的：在8X8格的国际象棋上摆放八个皇后，使其不能互相攻（任意两个皇后都不能处于同一行、同一列或同一斜线上），问有多少种摆法？输出所有的皇后摆法。

## 实验5 文本单词统计

设计程序，统计并输出一篇英文文章（文本文件）中的各个单词出现的次数。

## 实验6 约瑟夫问题

n个人围成一个圆圈，首先第s个人从1开始一个人一个人顺时针报数, 报到第m个人，令其出列。然后再从出列的下一个人开始，从1顺时针报数，报到第m个人，再令其出列，…，如此下去, 直到全部人出列为止

对任意给定的n, s, m, 求人员的出列顺序

## 实验7 二叉树遍历

设计程序，能够接受用户前序输入，构造对应二叉树，并对其进行中序遍历。

## 实验8 图的遍历

构造如下图结构，按照深度优先和广度优先的方式对图进行遍历。
![实验8](https://wx1.sinaimg.cn/mw690/bf4e3631ly1fwx8oz2jomj208w09l0t5.jpg)

## 实验9 排序方法比较

设计快速排序程序，能够对数据进行正确排序，并比较冒泡排序或插入排序等O(n2)时间复杂度算法和快速排序算法的差异。

首先保证快速排序算法正确性，然后随机产生大量数据，统计冒泡排序或插入排序所需时间，然后统计快速排序所需时间，比较二者之间所需时间差距。

## 实验10 C++ STL练习

学习附件pdf中提供的学习材料，掌握string, vector, list, set和map数据结构的基本用法。
[学习材料](https://www.cnblogs.com/skyfsm/p/6934246.html)

根据学习的内容，完成以下任务：

+ 合并两个string字符串
+ 创建一个vector，将一组数字存入，再添加一些数字，输出
+ 创建一个vector，将一组字符串存入并输出
+ 创建一个list，将一组数字存入并输出
+ 创建一个set，添加一些重复记录，输出
+ 创建一个map，存入一些记录并输出

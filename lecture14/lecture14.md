# 【第十四课】正交向量与子空间

原文链接：[https://zhuanlan.zhihu.com/p/30515094](https://zhuanlan.zhihu.com/p/30515094)

## **0、前言**

MIT线性代数课程精细笔记\[第十三课\]笔记见[MIT线性代数课程十三讲-经典题型的解法！](https://zhuanlan.zhihu.com/p/30494021)，该笔记是**连载**笔记，本文由坤博所写，希望对大家有帮助。

## **一、知识概要**

这是新的一部分，研究的重点还是之前提到过的子空间，但是本节我们主要从 正交的角度来探讨这些子空间具有的性质以及正交向量的特点等。主要内容都在 图（一）上。

![](https://pic1.zhimg.com/80/v2-1cbdca0babc6ebf8fa592b4f07c76e56_hd.jpg)

## **二．正交向量与子空间**

**2.1 基本正交概念**

首先我们来介绍一下正交的概念，在线性代数中，正交就是垂直，无论 我们以后谈论的是向量正交还是空间正交，都可以理解为：垂直。

  


我们首先来研究最简单的向量正交：

![](https://pic4.zhimg.com/80/v2-e02b5b30f65bb4afa17c229cda228bef_hd.jpg)

![](https://pic3.zhimg.com/80/v2-cf57ac80c098a623e278a07e074d438b_hd.jpg)

![](https://pic4.zhimg.com/80/v2-c05a927b6715e3d11998429b4ba5f0b6_hd.jpg)

接下来我们说一说空间的正交，两个空间正交就是：一个空间中的任意一 个向量，都与另一个空间中的任意一个向量正交。

这里有一个问题要注意一下，有一种很容易混淆，就是教授上课时候举的 例子，黑板与地面的两个平面的子空间并不正交，因为这两个平面有交线。而这 个交线无法满足空间正交的定义。

这也提醒了我们：两个平面在某一非零向量处相交，那这两个平面一定不 正交，因为相交处的这个非零向量无法满足空间正交定义。

![](https://pic4.zhimg.com/80/v2-e8edadd9ee2448f7efb37bdde66eb3e7_hd.jpg)

**2.2 零空间与行空间的正交关系**

![](https://pic4.zhimg.com/80/v2-eddb9e042399fccf495d5658b5b7385e_hd.jpg)

![](https://pic1.zhimg.com/80/v2-a20d7b392bbbb87fd1d2cdfcb49dcd9d_hd.jpg)

![](https://pic1.zhimg.com/80/v2-4a1c52391312d5a151ec758785a5bb18_hd.jpg)

**2.3 无解方程的最优解**

我们上一节中看见了，矩阵的数据来源于实际测量，那么就势必会有测量不 准确的时候，例如有时候我们求解 Ax = b 方程时，如果 A 的列数太多，那么其 中就很有可能混进去一些不准确的数据。这时我们以往的手段求解方程并不会求 出准确的解。这就引出了我们这部分内容。

![](https://pic1.zhimg.com/80/v2-265da7da830fa8a9afe5a54d4fcba0a5_hd.jpg)

![](https://pic2.zhimg.com/80/v2-235f40fdbf9aa6a66f184b8868543704_hd.jpg)

![](https://pic4.zhimg.com/80/v2-348f65efd6c6ac1a17ff1bf2bbae2484_hd.jpg)

## **三、学习感悟**

![](https://pic2.zhimg.com/80/v2-1fcb6c0c8993f537df7abb0d8ea735c0_hd.jpg)


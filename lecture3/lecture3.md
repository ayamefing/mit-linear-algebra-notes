## 【第三课】乘法和逆矩阵

原文链接：[https://zhuanlan.zhihu.com/p/28434767](https://zhuanlan.zhihu.com/p/28434767)

## **0、前言**

MIT线性代数课程精细笔记\[第二课\]笔记见[MIT线性代数课程精细笔记\[第二课\]](https://zhuanlan.zhihu.com/p/28325166)，该笔记是**连载**笔记，本文由坤博所写，希望对大家有帮助。

## **一、知识概要**

前面介绍了向量与矩阵之间的乘法，这一节我们要介绍两个矩阵之间的乘法。 并讨论逆矩阵存在的条件。最后又介绍了求解逆矩阵的方法。

## **二、矩阵乘法**

**2.1 矩阵乘法最常见求解方式**

![](https://pic3.zhimg.com/80/v2-5d0fdb0414810845382a9f283b12d731_hd.jpg)

![](https://pic3.zhimg.com/80/v2-2912bad4f525784a77b8c461e9e162f7_hd.jpg)

![](https://pic3.zhimg.com/80/v2-488a238c3c057e45c979a70582c4521a_hd.jpg)

**2.2 列组合与行组合方式**

**2.2.1 列组合：**

还记得我们之前学习过矩阵与列向量的乘积，得到一个列向量：

![](https://pic1.zhimg.com/80/v2-b29078336d025f564df30b6560a6e789_hd.jpg)

这种方法的关键就是将右侧矩阵 B 看做列向量组合，将问题转化为矩阵与向 量的乘法问题。也表明了矩阵 C 就是矩阵 A 中各列向量的线性组合，而 B 其实 是在告诉我们，要以什么样的方式组合 A 中的列向量。

**2.2.2 行组合：**

![](https://pic3.zhimg.com/80/v2-8600f77bf53bb566a49719f36e2369b8_hd.jpg)

同样，按照形式，这次将矩阵 A 看做行向量组合就行了：

![](https://pic4.zhimg.com/80/v2-1360dcb636d42763f10d1af4ff6f4c11_hd.jpg)

**2.3 列乘以行**

![](https://pic3.zhimg.com/80/v2-00ab57746ba754703c28c0bced891c8e_hd.jpg)

![](https://pic2.zhimg.com/80/v2-011b6b7ef1c8f4b26a2d286e961b10d8_hd.jpg)

**2.4.分块做乘法**

分块乘法就是宏观上的矩阵乘法，比如现在有一个 50\*50 的矩阵与 50\*50 矩 阵相乘，一个一个进行运算很麻烦，尤其是如果矩阵在某一区域上有一定的性质， 那么我们可以将其分块，如：

![](https://pic4.zhimg.com/80/v2-f441757ba0162ca47c7b8aad2024c339_hd.jpg)

## **三．逆矩阵**

**3.1 逆矩阵介绍**

![](https://pic1.zhimg.com/80/v2-46da7cbf880189ee1ade342504bfb0bb_hd.jpg)

![](https://pic2.zhimg.com/80/v2-d6adc73d8a9b3aab3e784fab9619eba0_hd.jpg)

**3.2 逆矩阵求解**

![](https://pic4.zhimg.com/80/v2-f9e012a7fef233e9dfc72040eb04e831_hd.jpg)

**3.2.1 高斯-若尔当方法**

![](https://pic1.zhimg.com/80/v2-1f8c036555d701dc6b931af3b663429b_hd.jpg)

接下来论证它的合理性：

![](https://pic3.zhimg.com/80/v2-29e5adaf8d30f05a477f8b031ae5cb4b_hd.jpg)

![](https://pic1.zhimg.com/80/v2-f934e17322b30b6c8a12c2bb1eae6f3c_hd.jpg)

## **四．学习感悟**

这节介绍了认识矩阵乘法的不同角度，并介绍了逆矩阵的相关知识以及如何 即求解逆矩阵。这节内容很好的体现了我自己认为的这门课的优点之一：少有繁 琐的证明，更多的理解与类比。多从向量，空间，线性组合的角度去认识矩阵之 间的运算，这是这门课的核心之一。


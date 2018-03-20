# 【第六课】列空间和零空间

原文链接：[https://zhuanlan.zhihu.com/p/29410442](https://zhuanlan.zhihu.com/p/29410442)

## **0、前言**

MIT线性代数课程精细笔记\[第四课\]笔记见[MIT线性代数课程精细笔记\[第五课\]](https://zhuanlan.zhihu.com/p/28863518)该笔记是**连载**笔记，本文由坤博所写，希望对大家有帮助。

## **一、知识概要**

本节从之前学习的子空间开始，介绍了子空间的部分性质。并重点介绍了列 空间与方程 Ax = b 之间的联系。并由此引出了零空间，根据 Ax = b 这个方程给 出了两种构建子空间的方法。

## **二．子空间**

**2.1 子空间回顾**

![](https://pic1.zhimg.com/80/v2-ce44eb52addcb88009443d06c4dd2eda_hd.jpg)

![](https://pic1.zhimg.com/80/v2-1cd2cbb5d84df1c3476173599af8211c_hd.jpg)

很明显，子空间直线 L 或平面 P 上，任取两个向量相加，得到的向量仍在该 子空间中。而且将其上的向量做数乘伸长或缩短一定倍数，其结果也还在该子空 间中。所以它们都对线性运算封闭。

**2.2 子空间的“交”与“并”**

上面我们都是分别研究的两个子空间，那么接下来我们对两个空间之间联系 部分展开讨论

**2.2.1 P∪L 空间**

还是讨论上面𝑅 3 的子空间 P 与 L，首先要研究的就是它们的并空间，即：现 有一集合，包含了 P 与 L 中的所有向量，那么这个集合是子空间吗？

答案是否定的。

很明显，我们将直线 L 与平面 P 看做同一个集合 P∪L 之后,这个集合对线性 运算并不封闭。比如我们随便在直线 L 上取一个向量 a，在平面 P 上取一个向量 b。此时向量 a+b 方向就会夹在直线 L 与平面 P 之间，脱离了 P∪L 的范围。所以 P∪L 无法构成空间。

![](https://pic2.zhimg.com/80/v2-c95e0cc8860c9e6f0e4e343e23bb97b7_hd.jpg)

![](https://pic1.zhimg.com/80/v2-bd22f89a898f1eae126f5e4ae17c2a31_hd.jpg)

**2.2.2 P∩L 空间**

![](https://pic7.zhimg.com/80/v2-b8c73381430db4cd0d4feb2d6a4c7931_hd.jpg)

![](https://pic4.zhimg.com/80/v2-9fbd070857476d03a702f092bf295916_hd.jpg)

## **三.列空间**

**3.1 列空间回顾**

![](https://pic3.zhimg.com/80/v2-2ed587b68cc915f0861021fb4c6984db_hd.jpg)

那么这个子空间有多大呢？这就需要用 Ax = b 方程来解释了。

**3.2 Ax = b 的空间解释\(从 A 的角度\)**

![](https://pic4.zhimg.com/80/v2-89d949dda55cf404a9ee27a12673d905_hd.jpg)

![](https://pic3.zhimg.com/80/v2-189ca1b2b00903dde627c9b29e0a3ef2_hd.jpg)

![](https://pic1.zhimg.com/80/v2-0a69157d62c974ca5261a1e815ab1df9_hd.jpg)

![](https://pic4.zhimg.com/80/v2-40408a8c6cbd1a2d511c5edd46a1342c_hd.jpg)

## **四、零空间**

**4.1 零空间介绍**

![](https://pic4.zhimg.com/80/v2-4487ca3943297bdb78ca8904ec92402b_hd.jpg)

![](https://pic7.zhimg.com/80/v2-a444d82ec1c1f73f2aaa9bdffe630d67_hd.jpg)

![](https://pic3.zhimg.com/80/v2-66717d8699bf7248d4b95f15e8947fef_hd.jpg)

**4.2 Ax = b 的空间解释\(从 x 的角度\)**

那如果上面构造零空间的方程右侧变为任意向量的话，其解集 x 还能构成 向量空间吗？

![](https://pic3.zhimg.com/80/v2-8b47a28f4a181bfda824d4d38672cf85_hd.jpg)

## **五.学习感悟**

![](https://pic1.zhimg.com/80/v2-e6cb6f58dcf60ace6f52402a297865f9_hd.jpg)

  



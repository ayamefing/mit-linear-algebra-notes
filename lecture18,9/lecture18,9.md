# 【第十八、九课】行列式及其性质、行列式公式和代数余子式

原文链接：[https://zhuanlan.zhihu.com/p/32007844](https://zhuanlan.zhihu.com/p/32007844)

## **0、前言**

MIT线性代数课程精细笔记\[第十七课\]笔记见[正交矩阵和 Gram-Schmidt 正交化\[MIT线代第十七课\]](https://zhuanlan.zhihu.com/p/30954790)，该笔记是**连载**笔记，本文由坤博所写，希望对大家有帮助。

## **一、知识概要**

这一节是为下面求特征值来进行铺垫，主要是要掌握求行列式的方法与行列 式的一些性质，掌握行列式一般求解过程之后这部分不是很难。由于这部分主要 在于技巧的掌握，抽象理解部分并不是很多，我这里将 18,19 课中关于行列式的 内容放在了一起。

## **二、行列式性质**

行列式是跟每个方阵都有关的一个数字。这个数字包含了这个矩阵的很多性 质，例如之前介绍过的，方阵是否可逆可以根据行列式进行判断，行列式为 0， 则方阵不可逆。

![](https://pic1.zhimg.com/80/v2-7996f7ee44f11d2bd587d974d213e73a_hd.jpg)

![](https://pic1.zhimg.com/80/v2-9d838044775f0c2383e8f9c5c25acb8a_hd.jpg)

![](https://pic3.zhimg.com/80/v2-0da83021792094262c2172165ea2c85f_hd.jpg)

![](https://pic3.zhimg.com/80/v2-84ad0d1c0da834ce0e190bbd1268dd0c_hd.jpg)

![](https://pic1.zhimg.com/80/v2-1604859443a16c870dbeadb5fabacea9_hd.jpg)

![](https://pic2.zhimg.com/80/v2-7bb663f21b9bcde506926ea2d952ad82_hd.jpg)

![](https://pic4.zhimg.com/80/v2-08bde3fe3c265cfbfee270890a7d1164_hd.jpg)

## **三、行列式公式**

前面介绍的是行列式的基本性质，掌握这些性质不需要知道行列式怎么求解， 但是我们可以根据这些性质推出来行列式的一般求解过程。我们从二阶行列式谈起：

![](https://pic1.zhimg.com/80/v2-c846dfe05807e52b81b2cc521d93b042_hd.jpg)

![](https://pic4.zhimg.com/80/v2-4d76ef9842e7b474c40455bc3067ac14_hd.jpg)

![](https://pic1.zhimg.com/80/v2-2c2e69e4574e18d84f37aa815fa5f552_hd.jpg)

![](https://pic1.zhimg.com/80/v2-0041444341c4c8c3b53d327d0bdf3816_hd.jpg)

![](https://pic1.zhimg.com/80/v2-4638e11dca8dc5bb5c51e051784b6b0c_hd.jpg)

## **四、代数余子式**

接下来介绍代数余子式概念，利用代数余子式我们可以更方便地求解行列式， 其作用即是将 n 阶行列式化成 n-1 阶。

根据前面所讲的公式，不难发现，在选元素做累乘时，例如从第一行中选了第 一个元素，则剩余因子从剩余的 n-1 行和 n-1 列中选取，于是剩余的因子组成一 个 n-1 阶行列式，这就是所谓代数余子式

![](https://pic2.zhimg.com/80/v2-b319bbf3ff40ef8505f12fe727455204_hd.jpg)

![](https://pic1.zhimg.com/80/v2-6a7c0404616014b04015f0a91616a288_hd.jpg)

![](https://pic4.zhimg.com/80/v2-888d0d63b166d6485ceb9fea8d6cac32_hd.jpg)

![](https://pic2.zhimg.com/80/v2-829a9b9256e3f551eb1e143f1146a0cf_hd.jpg)

![](https://pic4.zhimg.com/80/v2-43ccb9b956e8ad39c3bcc6d153bb7a0a_hd.jpg)

![](https://pic1.zhimg.com/80/v2-79a7b83d1e8747af6a65d05899541f3f_hd.jpg)

![](https://pic4.zhimg.com/80/v2-e6186a4c598a5fcc0efe26526d4cbee9_hd.jpg)

## **五、学习感悟**

这两节主要围绕计算行列式的技巧展开讨论，首先介绍了行列式具有的性质， 之后引出了使用公式计算行列式的方式，最后介绍了最常用的计算行列式的方法： 代数余子式展开。这部分主要是计算技巧问题，需要理解的部分较少。


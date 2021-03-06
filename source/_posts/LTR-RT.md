---
title: LTR-RT
tags: [LTR, LTR-retriever]
date: 2018-12-13 21:10:19
permalink:
categories:
description:
---
<p class="description">反转录逆转录转座子</p>

<!-- more -->

## 转座因子

几乎所有基因组内，都存在着转座因子(transposable element)或称转座子(transposon)。它们是基因组中可移动的DNA序列，可由基因组内的一个位置移至另一个位置。

转座子不利用其他元件（如噬菌体或质粒DNA）就可完成基因组内的移动。在真核生物和原核生物中，都已返现以DNA形式移动的转座子。每种转座子都携带棉麻其滋生转座所需的酶活性基因。

转座子可分为两大类：

1. 一类因子，或称反转录因子

   1.1这类转座子在总体结构和转座机制上都通常与反转录病毒高度相似，称为LTR反转录转座子(LTR retrotransposon)

   1.2另一类成为非LTR反转录转座子(non-LTR retrotransposon)

2. 二类因子，或称DNA型因子

## 酵母*Ty*因子

酵母中存在5中类型的*Ty*因子，所有因子都是反转录转座子，具有特征性的LTR与*gag*和*pol*基因，可以分为*Ty1/copia*因子类和*Ty3/gypsy*因子类，每一类在简化遗传上是独特的，并含有特征性顺序的可读框。

在大多数情况下，*Ty1*因子的转座效率大大低于细菌转座子，约为10<sup>-7</sup>~10<sup>-8</sup>。许多压力因素，如诱变剂和营养缺乏，可提高转座发生率。

*Ty1*因子的一般组织结构如图所示，每个因子长5.9 kb，末端的334 bp组成了LTR，历史上称为δ因子。

尽管单一*Ty1*因子的两个重复序列可能是相同或至少是非常相关的，但LTR序列也表现出很大的异源性。与*Ty1*因子相连的LTR序列保守型远远大于单一的LTR因子。这是因为*Ty1*因子的转座就像反转录病毒的复制一样，它包括LTR的倍增。所有，近期掺入的因子携带同样的LTR，而随着随机突变，在很长时间后，独立的LTR就会发生趋异。

## LTR-RTs的结构

LTR-RT (LTR retrotransposon) 结构的主要特征是75 ~ 5000 bp的长末端重复区域。在5'端LTR和3‘端LTR中间的区域被称为中间区域(the internal region)，其中编码了转座需要的蛋白。每一个LTR的末端都有双碱基的motif，大多数情况下都是5'-TG..CA-3', 在其他非典型的motif也有在一些物种中被发现。LTR末端motif的侧翼就是TSD(target site duplication)，这是由整合酶(integrase)剪切得到的交错切口产生的。TSDs的长度在3-6 bp之间，在植物中一般为5 bp。根据TSD产生的机制，5’和3‘端的TSD应当完全一致。

## LTR-retriever

LTR-RT是大多数植物基因组中转座子的最大组成部分。由于LTR-RT序列的多样性，基于序列同源性的方法来识别LTR-RT不是一个有效的方式。但是，LTR-RTs在不同物种之间其元件的结构是保守的。基于这些结构的特性，很多软件都能够识别LTR-RTs。这些软件识别LTR-RT的效率都很敏感，但是其准确性并不高。作者认为5’LTR与3‘LTR的前后区域不应该相同，以此来界定LTR的边界。

## 参考来源

基因X

<hr />
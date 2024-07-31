---
layout: post
title: 相关性分析
date: '2024-07-25 16:49:35'
permalink: /post/correlation-analysis-z1egbbl.html
published: true
---

# 相关性分析

​![image](https://raw.githubusercontent.com/2thcmoon/2thcmoon.github.io/master/images/image-20240725165701-yp71nrk.png)​

​![image](https://raw.githubusercontent.com/2thcmoon/2thcmoon.github.io/master/images/image-20240725165849-ek2yxro.png)​

预期进行两次相关性分析：第一次对NPBS分成的两束光（一束RAM噪声监测、一束进入环形腔）进行相关性分析，第二次对RAM噪声监测和Sagnac信号进行相关性分析。

# Pearson相关性分析

PCC 是一种统计和描述两独立观测变量之间相关性强弱的系数,将观测量的协方差除以两个变量的标准差得到。虽然协方差也是一种评估两个随机变量相关性的方式，但是协方差的取值范围为负无穷至正无穷，只能判定两个随机变量的正负相关程度，而 PCC 在其基础上除以了两个随机变量的标准差，将两个随机变量之间的相关性关系限制在了-1到1之间，当两个变量的线性关系增强时，Pearson 相关性系数趋于1或-1。PCC 的表达式为：

‍

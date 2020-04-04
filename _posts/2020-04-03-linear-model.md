---
layout:     post
title:      Linear model
subtitle:   Linear regression
date:       2020-04-03
author:     Fei-Fei
header-img: img/post-bg-rwd.jpg
catalog: true
tags:
    - linear model
    - statistics
---

<head>
  <script id="MathJax-script" async
          src="https://cdn.jsdelivr.net/npm/mathjax@3/es5/tex-mml-chtml.js">
  </script>
</head>


# Linear regression 


Brief Introduction of linear model [Youtube:StatQuest](https://www.youtube.com/watch?v=nk2CQITm_eo&list=PLblh5JKOoLUIcdlgu78MnlATeyx4cEVeR&index=17)

## 1. least square of residuals
[Youtube: Deriving the least square of the slope and intercept](https://www.youtube.com/watch?v=ewnc1cXJmGA)



\\(\hat{Y}=\hat{\beta}_0+\hat{\beta}\_1{X}\\)

\\(minQ=\sum\_{i=1}^{n}(y\_i-(\beta\_0+\beta\_1x\_i))^2\\)

\\(\frac{\partial{Q}}{\partial{\beta\_0}}=-2\sum\_{i=1}^n(y\_i-(\beta\_0+\beta\_ix\_i))=0 \\) 

\\(\bar{y}=\beta\_0+\beta\_1\sum_{i=1}^nx\_i\\)

\\(\frac{\partial{Q}}{\partial{\beta\_1}}=-2\sum\_{i=1}^{n}(y\_i-(\beta\_0+\beta\_ix\_i))x\_i=0\\)



## 2. \\(R^2\\)

>![](https://tva1.sinaimg.cn/large/00831rSTly1gdgkdg4zpqj30v50ecdkl.jpg)
>The left means sum of squared mean SS(mean); the right means sum of sqaured residuals, called fit SS(fit), which is variation not be explained by the regression line.

>\\(R^2\\) is the percentage of variation explained by the relationship between two variables


## 3.   \\(F\\) distribution and  \\(p_{value}\\)

>![](https://tva1.sinaimg.cn/large/00831rSTly1gdglhj0dhcj30v50ec0x5.jpg)
>
>
>

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


Basic Introduction of linear model [Youtube:StatQuest](https://www.youtube.com/watch?v=nk2CQITm_eo&list=PLblh5JKOoLUIcdlgu78MnlATeyx4cEVeR&index=17)

## 1. least square of residuals
[Youtube: Deriving the least square of the slope and intercept](https://www.youtube.com/watch?v=ewnc1cXJmGA)



\\(\hat{Y}=\hat{\beta}_0+\hat{\beta}\_1{X}+\varepsilon\\)

>\\(minQ=\sum\_{i=1}^{n}(y\_i-(\beta\_0+\beta\_1x\_i))^2\\)
><br/>
>\\(\frac{\partial{Q}}{\partial{\beta\_0}}=-2\sum\_{i=1}^n(y\_i-(\beta\_0+\beta\_1x\_i))=0 \\) 
>
>
>\\(\bar{y}=\beta\_0+\beta\_1\bar{x}\\)
><br/>
>
>\\(\frac{\partial{Q}}{\partial{\beta\_1}}=-2\sum\_{i=1}^{n}(y\_i-(\beta\_0+\beta\_1x\_i))x\_i=0\\)
><br/>
>Remember out next aim is to get \\(\beta_1\\)
><br/>
>\\(\because \beta\_0=\bar{y}-\beta\_1\bar{x}\\)
><br/>
>\\(\\therefore \sum\_{i=1}^{n}(y\_i-(\beta\_0+\beta\_ix\_i))x\_i=\sum\_{i=1}^{n}(y\_i-(\bar{y}-\beta\_1\bar{x}+\beta\_1x\_i))x\_i \\)
><br/>
>\\(=\sum\_{i=1}^{n}x\_i(y\_i-\bar{y})-\beta\_1\sum\_{i=1}^{n}x\_i(x\_i-\bar{x})=0 \\)
><br/>
>\\(\therefore\beta\_1=\frac{\sum\_{i=1}^{n}x\_i(y\_i-\bar{y})}{\sum\_{i=1}^{n}x\_i(x\_i-\bar{x})}=\frac{Cov(X,Y)}{Var(X)}
\\) 


## 2. \\(R^2\\)

>![](https://tva1.sinaimg.cn/large/00831rSTly1gdgkdg4zpqj30v50ecdkl.jpg)
>The left means sum of squared mean SS(mean); the right means sum of sqaured residuals, called fit SS(fit), which is variation not be explained by the regression line.

>\\(R^2\\) is the percentage of variation explained by the relationship between two variables

The proof of why Pearson correlation coefficient = R-square in simple linear model

>![](https://tva1.sinaimg.cn/large/00831rSTly1gdhyft6ivdj30u40s2wir.jpg)
>![](https://tva1.sinaimg.cn/large/00831rSTly1gdhyio1zlxj30ff0ivabo.jpg)

## 3.   \\(F\\) distribution and  \\(p_{value}\\)



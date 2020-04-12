---
layout:     post
title:      Paper reading
subtitle:   Learn from Huanwei's script
date:       2020-04-06
author:     Fei-Fei
header-img: img/post-bg-rwd.jpg
catalog: true
tags:
    - genetics
    - polygenic score
    - paper
---
#[Rcheatsheets](https://rstudio.com/resources/cheatsheets/)

# fread
[library(data.table)](https://cran.r-project.org/web/packages/data.table/vignettes/datatable-intro.html) Similar to read.table but faster and more convenient. 

`ans <- flights[origin == "JFK" & month == 6L]`
>column can be referred to as if they are *variables*

# %>%
>pheno1 = pheno1 %>% mutate(WHR=WC/HC, FFR=FEV/FVC, WHRadjBMI=resid(lm(WHR~BMI, na.action=na.exclude)), HTsq=HT^2, HTcube=HT^3)
The meaning of %>%
>iris %>% head() is equivalent to head(iris).
I think the benefit is to decrease variables when a lot of process.

# mutate
library(dplyr) like above add new variables

>![]zhttps://tva1.sinaimg.cn/large/00831rSTly1gdl3lm2ct8j312q0u0ttr.jpg)
>![](https://tva1.sinaimg.cn/large/00831rSTly1gdl3nmfzw9j312q0u0ha4.jpg)

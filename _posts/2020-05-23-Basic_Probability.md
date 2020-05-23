---
layout:     post
title:     	R packages
subtitle:   GWAS
date:       2020-05-08
author:     Fei-Fei
header-img: img/post-bg-rwd.jpg
catalog: true
tags:
    - R
---

(ROCR tutorial)[https://www.r-bloggers.com/a-small-introduction-to-the-rocr-package/]
prediction=list(data[1:16517,"SCORESUM"],data[16518:(16517*2),"SCORESUM"],data[(16517*2+1):(16517*3),"SCORESUM"],data[(16517*3+1):(16517*4),"SCORESUM"],data[(16517*4+1):82581,"SCORESUM"])
labels=list(data[1:16517,"myopia"],data[16518:(16517*2),"myopia"],data[(16517*2+1):(16517*3),"myopia"],data[(16517*3+1):(16517*4),"myopia"],data[(16517*4+1):82581,"myopia"])
pred=prediction(prediction, labels)
pred

perf<- performance(pred, "tpr", "fpr")
plot(perf,col=as.list(rainbow(5))) #col=1:10
abline(a=0,b=1)

#area under the curve
auc.perf = performance(pred, measure = "auc")
auc.perf@y.values

# 
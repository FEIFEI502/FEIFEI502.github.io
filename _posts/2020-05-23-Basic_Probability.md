---
layout:     post
title:     	Basic of probability
subtitle:   Statistics
date:       2020-05-23
author:     Fei-Fei
header-img: img/post-bg-rwd.jpg
catalog: true
tags:
    - Statistics
---
Unions, Intersection, Complement

# Conditional Probability
![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf21d13wu1j30me0hojvz.jpg)

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf2318fkywj30qw0ge44f.jpg)

correlation, the postive one and the negative one (mutually exclusive events).

# Independent Events
 
 Independent doesn't mean there is no intersection. It means the frequency of A in B is equal in all sample space, also the complement part as well.
 ![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf226aflm4j30qw0gegsu.jpg)
 
 The above can also be used to check independent events.
 
 
# De Morgan's laws
![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf23dm13urj30qq0cemz9.jpg)

# Discrete Probablity Distribution

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf23slw6hjj30rq0hw79q.jpg)

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf24atp8ruj30d806e0u0.jpg)

## the Expected Value and Variance

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf240wb8djj30nq0dq79z.jpg)

## Bernouli Distribution
P(success X=1)=p
P(failure X=0)=1-p

E(X)=p
Var(X)=E(X^2)-E(X)^2 = p-p^2=p(1-p)

## Bonimial Distribution
n independent Bernoulli distribution

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf23f8cqy4j30w00i20yr.jpg)

n=2
E(X)=2p(1-p)+2P^2=2p
Var(X)=2p(1-p)+4P^2-(2p)^2=2p(1-p)

X~Bonimial(n,p)
E(X)=np
var(X)=np(1-p)

## Hypergeometric Distribution

sampling is done without replacement,e.g. drawn 4 red balls from 5 randomly drawn with replacement (all contains 6 red balls and 14 yellow balls)

![](https://tva1.sinaimg.cn/large/007S8ZIlgy1gf24sbl8jkj30pc0amn2z.jpg)
N=20 the number of balls
n=6 the number of drawn balls, of objects samples
a=5 of successes in the population

The binomial distribution can sometimes provide a reasonable approximation to the hypergeometrix distribution (sampling less than around 5% of the population). The reason is, drawning a small number from big population alternate a little frequency.

## Geometric Distribution

X is the number of getting the first success.


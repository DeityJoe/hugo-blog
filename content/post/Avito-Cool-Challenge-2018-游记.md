+++
title = "Avito Cool Challenge 2018 游记"
date = "2018-12-17T22:47:17+08:00"
categories = ["游记"]
tags = ["Codeforces"]
description = ""
aliases = ["/post/Avito-Cool-Challenge-2018-游记", "/Avito-Cool-Challenge-2018-游记"]
+++


这两天比赛是真的多..碰上了场 Chinese Legends Round / HackForces 竟然在紫名涨了点分QAQ

<!-- more -->

看到 A，$gcd(x,x-1)=1$ ，这不是sb题吗？然后愉快地WA了...互质 $\ne$ 不为倍数鸭QAQ还有 $1$ 呢.开场-50分..

B貌似比C难，但A的人比C多..其实当时交的时候还没想清楚 $p$ 个一样的人数是 $p$ 的倍数这个结论，就感觉好像是对的，就交了。

C 很快就想到了结论，排列组合乘一乘随便做，而且数据范围小到可以用杨辉三角算组合数+不用快速幂。

D 感觉要搞个MST，然后就真的先搞了个MST，然后就没有想到简单的解法..正解是MST搞完所有关键点就不搞了。一开始写挂了，然而pt特别水（好像直接输出MST最大边就可以），A完E之后看到jason的D被叉了，就仔细看了下，发现自己写挂了..然后重交，少了 $400$  多分。

E 贪心搞一搞就行了，据说ylh没有做出来是忘了积一定差越小和越小..

F 看了看感觉不会，于是锁了 D 开始叉人。看到room rank1的正解感觉自己整个人都sb了..在离比赛结束 $5$ 分钟的时候看到一个感觉写挂了的，然而不敢hack，于是一直盯着看，直到离比赛结束还有 $1$ 分钟的时候才hack，然而一不小心把数据打错了..幸好格式错误不扣分，赶紧点回去重新hack，最后在离比赛结束 $4s$ 的时候提交了hack，然后绿了！喜提 $100$ 分、$50​$ 名。

当时比赛一结束我就跟 ylh 说我感觉如果我不 fst能再涨 $100$ 名，然后最后真的又涨了 $100$ 名.. B和D一堆fst的。

F 用奇偶性判断选择的哪边，感觉很妙。

G 没仔细看。

H：

> and we didn't except anyone to pass.

不知道会在紫名待多久QAQ
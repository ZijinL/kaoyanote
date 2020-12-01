# 大数定理 中心极限定理

## 切比雪夫不等式

**一个数偏离其期望的概率的上限：**$P\{|X-E(X)| \ge \epsilon\} \le \frac {D(X)}{\epsilon^2}$  

**依概率收敛：**$\lim\limits_{n\rarr\infin}P\{|X_n - a| < \epsilon\} = 1$ 

1. ![image-20201201082844691](PB5-大数中心.assets/image-20201201082844691.png)
   
2. 

## 大数定律

**均值依概率收敛于数学期望**

* 切比雪夫大数定律：独立、期望存在、方差有上界；均值依概率收敛于其数学期望
* 伯努利大数定律：独立、同服从0-1分布；均值依概率收敛于其数学期望$p$ 
* 辛钦大数定律：独立同分布、期望为$\mu$；均值依概率收敛域其数学期望$p$，$\lim\limits_{n\rarr\infin}P\{|\frac1n\sum\limits_{i=1}^{n} X_i-\mu|\le \epsilon\} = 1$，

## 中心极限定理

**大量独立同分布均值近似服从正态分布：**$\overline X \sim N(\mu, \frac{\sigma^2}{n})$ ；特殊$Y_n \sim B(n,p) \sim N(np, np(1-p))$ 


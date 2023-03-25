---
title: mechanics-3
date: 2019-10-10
tags: mechanics
mathjax: true
categories: 力学
---
# 力学第三章

## 提纲

暂无

## 题目

3.1， 3.5， 3.7， 3.8， 3.10 ，
3.14， 3.15， 3.17， 3.20， 3.27

## 评分约定

共10题，每题10分。某题结果正确基本可以得到该题满分。

本次评分细则由**张爱强助教**给出，如果有问题可以发邮件至 zhangaq19@mails.tsinghua.edu.cn
### 3.1
**题目**
一列火车总质量M，最后一节车厢质量m，若m从匀速前进的列车脱离，s路程后停止。机车牵引力不变，每节车厢所受的摩擦力正比于重量而与速度无关。脱开的车厢停止时距列车后端距离。

选择质心参考系，整体受力平衡，内部两个物体受大小相等，方向相反的力。
--(1 point)
因此两个物体加速度之比$\frac{a_{M-m}}{a_{m}}=\frac{m}{M-m}$
--(3 point)
质心系下两个物体都从静止开始做匀加速运动，因此位移之比$\frac{s_{M-m}}{s_{m}}=\frac{a_{M-m}}{a_{m}}=\frac{m}{M-m}$
--(2 point)
m在质心系中速度从0至$v_0$，而在地面参考系中，速度从$v_0$到0，所以$s_{m}=s$
--(2 point)
因此两者间的距离在质心系中为$X=s_{M-m}+s_{m}=\frac{ms}{M-m}+s=\frac{Ms}{M-m}$
--(2 point)

--(在地面参考系中解答同样给分，如果在地面参考系求解未完全解出，在5分基础上酌情加减）

### 3.5
**题目**
物体A和B用绳连接，A位于摩擦因数$\mu$的水平桌面，B在滑轮下自然下垂，忽略绳和滑轮质量，绳不可伸长，B下降h的速度

能量守恒
$$\frac{1}{2}{(m_{A}+m_{B})}v^2-m_{B}gh=-m_{A}gh$$
--{9 point}
解得
$$v=\sqrt{\frac{2(m_{B}gh-m_{A}g\mu h)}{m_{A}+m_{B}}}$$
--{1 point}
### 3.7
**题目**
在劲度系数K的弹簧下挂$m_1$,$m_2$,初始静止，烧断连线，$m_1$最大速度

$m_1$将会向上做加速运动，直至弹簧拉力等于$m_1g$，此时弹簧长度$x_2=m_1g/k$

初始弹簧长度$x_1=(m_1+m_2)g/k$
--(4 points)
机械能守恒
$$\frac{1}{2}k({x_2}^2-{x_1}^2)+m_1g(x_2-x_1)+\frac{1}{2}m_1v^2=0$$

--(4 points)
解得
$$v=\sqrt{\frac{g^2m_2^2}{km_1}}=\frac{m_2g}{m_1\sqrt{k/m_1}}$$

--(2 points)
（使用弹簧振子的公式或其它方法计算同样给分)
比如由弹簧振子公式
$$v=A_0w=(x_2-x_1)\sqrt{k/m_1}=\frac{m_2g}{\sqrt{m_1k}}$$
### 3.8
**题目**
劲度系数k，另一端质量$m_{A}$，把弹簧长度压短$x_0$，放置$m_{B}$,撤去外力

（1）A、B离开时，B速率
A、B分离时，两者运动上速度相等，加速度恰好相等，且之后两者速度不等，即两者加速度发生变化，对应弹簧恰好位于原长。

由机械能守恒
$$-\frac{1}{2}k{x_0}^2+\frac{1}{2}{m_{A}+m_{B}}v^2=0$$

解得$v=\sqrt{\frac{k{x_0}^2}{m_{A}+m{B}}}$
--(5 points)
--(使用弹簧振子公式或其他方法同样给分）
（2）A距起始点移动的最大距离
A减速至0，位移最大
$$\frac{1}{2}k{x_1}^2-\frac{1}{2}m_{A}v^2=0$$

解得$x_1=\sqrt{\frac{m_{A}}{m_A+m_B}}x_0$

最大距离为$x=x_0+x_1=(1+\sqrt{\frac{m_{A}}{m_A+m_B}})x_0$
--(5 points)
(使用弹簧振子公式同样给分）

### 3.10
**题目**
质量为$m_1,m_2$,k弹簧连接，

（1）至少多大F压$m_1，m_2$离地临界条件是离地二者速度恰好为零，此时弹簧伸长为$x_2=(m_2g)/k$

机械能守恒,$x_1={(F+m_1g)}/k$为压缩长度
--(2 points)
$$\frac{1}{2}k{({x_2}^2-{x_1}^2)}+m_1g(x_1+x_2)=0$$

解得$x_1=\frac{2m_1g+m_2g}{k}$其中有一个负解被舍去

--（3 points)
因此力F的大小应该为$m_1g+m_2g$
--(2 points)

此问可用弹簧振子对称性求解，因为平衡点位于压缩$m_1g/k$，而临界条件时对应的伸长量与平衡点距离为$(m_1g+m_2g)/k$,因此力F作用同样压缩为$(m_1g+m_2g)/k$,因此力F的大小为$(m_1g+m_2g)$。
(直接可得7分)
(2)力F撤出后
加速度最大时，合外力最大$F_{total}=F$，即为初始时刻，加速度为g
--(1 point)
在平衡位置加速度为0，弹簧压缩$(m_1g)/k$
--(1 point)
在m2刚要离开地面时，整体法可知$a_c=g$。
--(1 point)
### 3.14
**题目**
质量M静止光滑水平面，m以$v_0$入射，
(1)木块对子弹作用力的功
动量定理
$$v=mv_0/(m+M)$$
--(3 points)
由动能定理功为
$$W=\frac{1}{2}m(v^2-{v_0}^2)=-6397.44J$$
--（2 points)
(2)子弹对木块作用力的功
动能定理
$$W=\frac{1}{2}Mv^2=125.44J$$
--(2 points)
(3)耗散掉的机械能
能量守恒
$$\Delta E=\frac{1}{2}(m{v_0}^2-(m+M)v^2)=6272J$$
--(3 points)
或者内力做功之差
$$W_{mM}+W_{Mm}=6272J$$
--(同样给分3 points)
### 3.15
**题目**
$m_1,m_2$静止，k弹簧相连，m,$v_0$入射$m_1$，弹簧最多压缩

（注：此处子弹入射后立即和物块同速，否则此过程耗散的能量有差别）
入射后子弹和$m_1$速度为
$$v_1=\frac{mv_0}{m_1+m}$$
--(3 points)
若弹簧压缩最多，对应物块的速度恰好相等
$$v_2=\frac{mv_0}{m_1+m_2+m}$$
--(3 points)
弹簧压缩量为x,对应能量守恒
$$-\frac{1}{2}(m_1+m)v_1^2+\frac{1}{2}(m_1+m_2+m)v_2^2+\frac{1}{2}kx^2=0$$
--(3 points)
解得
$$x=\sqrt{\frac{m_2}{(m_1+m_2+m)(m_1+m)k}}mv_0$$
(1 points)
### 3.17
**题目**
$m_B$水平面静止，$m_A$从h处滑下，弹性碰撞，A，B发生两次碰撞条件

临界条件A第二次滑下的速度等于B
--(2 points)
A第一次滑下速度$v_0$
弹性碰撞后二者的速度为
$$v_A=\frac{(m_A-m_B)v_0}{m_A+m_B},v_B=\frac{2m_Av_0}{m_A+m_B}$$
--(3 points)
因此$m_A<m_B$A才能反向，同时A速度需要大于B
$$m_B-m_A>2m_A$$
--(3 points)
因此
$$m_B>3m_A$$
--(2 points)
### 3.20
**题目**
感谢**邵文辉**助教指出**题目中误差应该只有N原子速度的不确定度**,因此以下答案修改为
（1）中子质量
结果为$1.16\pm 0.25u$

（2）中子初速度
结果为$(3.07\pm 0.31)\times10^7m/s$

(此处误差`不包括结果值`按照区间两侧端点值计算此次给分,以后应该注意使用不确定度的传递公式）
-----------------------
（1）中子质量
弹性碰撞引起的反冲速度最大
$$v_H=\frac{2m_nv_0}{m_n+m_H}$$

$$v_N=\frac{2m_nv_0}{m_n+m_N}$$

$$v_H/v_N=\eta=\frac{m_n+m_N}{m_n+m_H}$$

$$m_n=\frac{m_N-\eta m_H}{\eta-1}=1.1590u$$
--(2 points)
不确定度的计算要从最初的物理量的不确定度传递过来，具体细节如下
在公式中用到了$\eta$，所以我们可以先单独求该物理量的不确定度，当然也可以直接将$\eta$替换成最初的物理量进行求导得到不确定度的公式
$$\frac{\Delta \eta}{\eta}=\sqrt{(\frac{\Delta v_H}{v_H})^2+(\frac{\Delta v_N}{v_N})^2}$$

因此可以得到$\Delta\eta=\sqrt{2}/10 \eta$

注意上面的不确定度最好要多保留几位，否则会影响最后的不确定度的结果。此处可也先不求出，均保留至最后计算

对于$m_n$的不确定度可以使用类似求导手法
$$\Delta m=\frac{13m_H}{(\eta-1)^2}\Delta\eta=0.2618$$
--(2 points)
求完了不确定度，需要取合适的位数，一般取1-2位即可，此处0.2618中的2比较小，可以适当多取1位，取2位有效数字

结果的小数位数根据不确定度的位数取，因此最后结果为$1.16\pm 0.26u$
--(1 point)

（2）中子初速度
$$v_0=\frac{v_Nv_H(m_N-m_H)}{2(v_Nm_N-v_Hm_H)}=3.0736\times10^7m/s^2$$
--(2 points)
$$\frac{\Delta v_0}{v_0}=\sqrt{(\frac{\Delta v_H}{v_H}+\frac{m_N\Delta v_N}{v_Nm_N-v_Hm_H})^2-(\frac{\Delta v_N}{v_N}+\frac{m_H\Delta v_N}{v_Nm_N-v_Hm_H})^2}=0.224$$

$$\Delta v_0=0.689\times10^7m/s$$
--(2 points)
因此结果为$(3.07\pm 0.69)\times10^7m/s$
--(1 points)


### 3.27
**题目**
求圆心角为2$\theta$的一段均匀圆弧质心

以x轴为对称轴，原点为圆心作一个圆弧,线密度$\rho$
其中由对称性可知质心纵坐标为0
--（4 points)
质心横坐标
$$x_c=\frac{\int_{-\theta}^{\theta}{\rho r\cos{\theta}rd\theta}}{2\rho r\theta}=r\sin{\theta}/\theta$$
--(6 points)
其实也可以去积分纵坐标，结果同样为0

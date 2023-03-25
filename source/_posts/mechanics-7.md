---
title: mechanics-7
date: 2019-11-07 11:49:56
tags:
mathjax: true
categories: 力学
---
# 力学第五章
连续体力学

## 评分细则

本次评分由**张爱强**助教给出
每题10分，共100分。有错误或者疑问可以邮件至:**zhangaq19@mails.tsinghua.edu.cn**

### 5.1
**题目**

圆筒状锅炉，气体压强p，求正应力

选择半个柱体作为研究对象。由对称性可知，正应力处处相等。
列出平衡方程(L为单位长度)：
$$PLD=\tau 2Ld$$
    （5 points)
$$\tau = \frac{PD}{2d}$$
     (5 points)
**附注**
球体情况下
$$\tau = \frac{PD}{4d}$$
由于本人在群里看错了题，可能会有误导，所以把第一个关系式列成球体也给5分，结果仍不给分

使用微元法同样给分。

### 5.2
**题目**

（1）矩形横截面在轴向拉力作用下产生拉伸应变为$\epsilon$，泊松比$\sigma$，体积相对改变为
取一个小正方体微元，边长l，那么体积变化(取$\epsilon$的一阶量)为
$$\frac{V-V_0}{V_0}=(1+\epsilon)(1-\sigma\epsilon)^2-1=\epsilon(1-2\sigma)$$
         (4 points)
(2)同1，可以求得压缩时
$$\frac{V-V_0}{V_0}=(1-\epsilon)(1+\sigma\epsilon)^2-1=-\epsilon(1-2\sigma)$$
       (4 points)

（3）代入公式可得
$$\frac{V-V_0}{V_0}=\epsilon(1-2\sigma)=\tau/Y(1-2\sigma)=2.8\times10^{-12}$$
       (2 points)

### 5.9
**题目**
截面5.0cm2的均匀虹吸管，最高点高于水面1.0m，出口在水下0.6m，

（1）定常流动管内最高点压强
伯努利方程，选择水面和出口($h_1=-0.6m$)
$$\frac{p_0}{\rho g}=\frac{p_0}{\rho g}+\frac{v^2}{2g}+h_1$$
解得
$$v=\sqrt{-2gh_1}=3.43m/s$$
        (4 points)
选择水面和最高点($h_2=1m$)
$$\frac{p_0}{\rho g}=\frac{p_2}{\rho g}+\frac{v^2}{2g}+h_2$$
解得(p_0=1.01\times 10^5pa,g=9.8m/s^2)
$$p_2=p_0+\rho g(h_1-h_2)=0.853\times 10^5pa$$
          (3 points)
（2）虹吸管的体积流量
$$Q_V=vS=1.71\times 10^{-3}m^3/s$$
         (3 points)
注：此题如果上述常数取值不一样，结果的有效位的数值应该有差异
### 5.10
**题目**
油箱内石油密度0.9g/cm3,水厚度1m，油厚度4m

伯努利方程分两段区间，界面处压强相等为$p_1$,此外$h_1=-4m,h_2=-1m$

$$\frac{p_0}{\rho_{oil} g}=\frac{p_1}{\rho_{oil} g}+h_1$$
            (3 points)
$$\frac{p_1}{\rho_{water} g}=\frac{v^2}{2g}+\frac{p_0}{\rho_{water} g}+h_2$$
(4 points)
解得($g=9.8m/s^2$)
$$v=\sqrt{2g(-\frac{\rho_{oil}}{\rho_{water}}h_1-h_2)}=9.5m/s$$
(3 points)

注：可以一步到位
$$P_0+\rho_{oil}gh_{oil}+\rho_{water}gh_{water}=1/2\rho_{water}v^2+P_0$$

### 5.11
**题目**
截面A的柱形桶水高度H，水柱最小截面积为S，容器剩一半水和全部流完时间

（1）伯努利方程,其中$v_0=-\frac{dh}{dt},v_0A=vS$
$$\frac{p_0}{\rho g}+\frac{v_0^2}{2g}+h=\frac{p_0}{\rho g}+\frac{v^2}{2g}$$
注：此处一般A较大，导致$v_0$较小，所以一般液面速度可以不考虑，此处先将$v_0$考虑进来，计算最后的结果,
如果此处式子没有$v_0$，同样给分
     （3 points)
解得
$$h=\frac{v_0^2}{2g}((\frac{A}{S})^2-1)$$
      (1 points)
$$\sqrt{2gh}=\frac{dh}{dt}\sqrt{(\frac{A}{S})^2-1}$$

积分可以得到
$$t=\sqrt{\frac{2[(\frac{A}{S})^2-1]}{g}}(C-\sqrt{h})$$
      (3 points)
代入初始条件(h(t=0)=H)
$$t=\sqrt{\frac{2[(\frac{A}{S})^2-1]}{g}}(\sqrt{H}-\sqrt{h})$$
      (1 points)
h=1/2H时
$$t=(\sqrt{2}-1)\sqrt{\frac{H}{g}}\sqrt{(A/S)^2-1}$$ 
忽略时为
$$t=(\sqrt{2}-1)\sqrt{\frac{H}{g}}(A/S)$$ 
      （2 points)
h=0时
$$t=(\sqrt{2})\sqrt{\frac{H}{g}}\sqrt{(A/S)^2-1}$$ 
忽略时为
$$t=(\sqrt{2})\sqrt{\frac{H}{g}}(A/S)$$ 
      (2 points)

### 5.12
**题目**
在20cm,30cm的矩形截面容器深度50cm水，小孔面积2cm2，水流出一半用的时间

使用5.11的结论
$$t=(\sqrt{2}-1)\sqrt{\frac{0.5}{9.8}}(20\times 30/2)=28.07s$$ 
       (10 points)
### 5.13
**题目**
在H的量筒上开一系列h不同的小孔，证明

伯努利方程
$$\frac{p_0}{\rho g}+H=\frac{p_0}{\rho g}+\frac{v^2}{2g}+h$$
    (4 points)
解得
$$v^2=2g(H-h)$$
    (1 points)
因此h处射程为
$$x=v\times \sqrt{2gh}=2g\sqrt{h(H-h)}$$
因此$h=1/2H$时射程最远
     (5 points)
### 5.17
**题目**
桶底部有一洞，水面30cm,桶以120cm/s2加速度上升时，水自洞漏出速度为

在桶的坐标系中会多出一项惯性力，等效为受的合力为惯性力与重力的叠加，同样可以用之前的公式，
但重力加速度$g'=g+a$
         (4 points)
伯努利公式
$$\frac{p_0}{\rho g'}+H=\frac{p_0}{\rho g'}+\frac{v^2}{2g'}$$
         (4 points)
解得水相对桶漏出的速度
$$v=\sqrt{2g'H}=2.57m/s$$
        (2 points)
### 5.18
**题目**
方形截面侧壁有一孔，下缘高度h,容器水平加速度a，液体不会从孔中流出

同样可以转换至桶的参考系，多加了一项惯性力，合成后的重力加速度有一个角度，而水面垂直于合成的重力加速度方向，
因此只要水面高于孔，水就会从孔中漏出，可以从伯努利公式中算出速度
     (5 points)
临界即为液面为于小孔处，此时另外一端高度为2(H-h)
$$a/g=\frac{2(H-h)}{l}$$
     (3 points)
液面角度为
$$\theta=arctan(\frac{2(H-h)}{l}$$
      (2 points)
### 5.25
**题目**
半径0.1cm的小空气泡在液体中上升，终极速度

终极速度气泡浮力与阻力相等
    (2 points)
$$\rho g \frac{4}{3}\pi r^3=6\pi\eta rv$$
    (6 points)
解得
$$v=\frac{2\rho gr^2}{9\eta}=0.0143m/s$$
     (2 points)





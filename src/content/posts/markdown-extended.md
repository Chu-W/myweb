---
title: Test
published: 2025-10-27
updated: 2025-10-27
description: 'Test'
image: ''
tags: [Demo, Example]
category: 'Examples'
draft: false 
---

### 1.1.1 观察反射的情况

设入射振幅为 $A_0$，经过第一个界面的振幅反射/透射系数分别为 $r_1/t_1$，第二个界面为 $r_2/t_2$。

在连续反射的过程中，反射波的振幅为 $A_0 r_1, A_0 t_1 r_2 t_2 e^{i\delta}, A_0 t_1 r_2^3 t_2 e^{2i\delta}, \dots$

其中 $\delta$是相位差（相邻两束反射光），后一次反射比前一次反射在平板内多走了一段路程，表达式为
$$
\delta = \frac{2\pi}{\lambda_0} \Delta
$$

$\Delta$为光程差，表达式为
$$
\Delta = 2n_2 h \cos\theta_2
$$

其中，$\theta_2$是入射角，$\lambda_0$是入射波的真空波长，$h$是平板厚度。所以有$\delta = \frac{4\pi n_2 h \cos\theta_2}{\lambda_0}$

得到的总的反射波振幅为（注意不是光强）
$$
\begin{align*}
A_{\text{r}} &= A_0 \left[ r_1 + t_1 t_2 r_2 e^{i\delta} \left( 1 + r_2^2 e^{i\delta} + r_2^4 e^{2i\delta} + \cdots \right) \right] \\
&= A_0 \left( r_1 + \frac{t_1 t_2 r_2 e^{i\delta}}{1 - r_2^2 e^{i\delta}} \right)
\end{align*}
$$






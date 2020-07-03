含有轨道（或自旋）项的哈密顿量
$$
H=\sum_{k\alpha\beta}c^\dagger_{k\alpha}h^{\alpha\beta}(k)c_{k\beta}
$$
计算松原函数$G_{\alpha\beta}(k,\sigma)=-\langle \hat{T}c_{k\alpha}(\sigma)c^\dagger_{k\beta}\rangle$ .

==Baker-Hausdorff theorem==
$$
e^ABe^{-A}=B+[A,B]+\frac{1}{2!}[A,[A,B]]+\frac{1}{3!}[A,[A,[A,B]]]+...
$$
消灭算符时间依赖关系
$$
\begin{align}
c_{k\alpha}(\sigma)&=e^{\sigma H}c_{k\alpha}e^{-\sigma H}\\&=c_{k\alpha}+(-\sigma)[h(k)]^{\alpha\lambda}c_{k\lambda}+\frac{1}{2!}(-\sigma)[h^2(k)]^{\alpha\lambda}c_{k\lambda}+\frac{1}{3!}(-\sigma)[h^3(k)]^{\alpha\lambda}c_{k\lambda}+...\\&=\left(\delta^{\alpha\lambda}+[h(k)]^{\alpha\lambda}+\frac{1}{2!}(-\sigma)[h^2(k)]^{\alpha\lambda}+\frac{1}{3!}(-\sigma)[h^3(k)]^{\alpha\lambda}+...\right)c_{k\lambda}\\&=e^{-\sigma h^{\alpha\lambda}(k)}c_{k\lambda}
\end{align}
$$
重复指标$\lambda$求和。
$$
\begin{align}
G_{\alpha\beta}(k,\sigma)&=-\langle \hat{T}c_{k\alpha}(\sigma)c^\dagger_{k\beta}\rangle=-\Theta(\sigma)e^{-\sigma h^{\alpha\lambda}(k)}\langle c_{k\lambda}c^{\dagger}_{k\beta}\rangle
+\Theta(-\sigma)e^{-\sigma h^{\alpha\lambda}(k)}\langle c^{\dagger}_{k\beta}c_{k\lambda}\rangle\\&=-e^{-\sigma h^{\alpha\beta}(k)}\left(\Theta(\sigma)-n^{\alpha\beta}_k\right)\end{align}
$$
这里的$n_{k}^{\alpha\beta}=1/(1+e^{\beta_0h^{\alpha\beta}(k)})$ 是费米分布函数。

傅立叶变换得到
$$
G_{\alpha\beta}(k,i\omega_n)=\frac{1}{i\omega_n-h^{\alpha\beta}(k)}
$$
在轨道指标张成的空间看，G是个矩阵，可以写成$\hat{G}(k,i\omega_n)=\frac{1}{i\omega_n-\hat{h}(k)}$. $\hat{h}(k)$ 即是轨道空间张成的哈密顿矩阵，将$\hat{h}(k)$ 对角化
$$
\hat{h}(k)|i,k\rangle=\epsilon_i|i,k\rangle
$$
从而得到
$$
\begin{align}
\hat{G}(k,i\omega_n)&=\frac{1}{i\omega_n-\hat{h}(k)}\\&=\frac{1}{i\omega_n-\hat{h}(k)}\sum_j|j,k\rangle\langle j,k|\\&=\sum_j\frac{|j,k\rangle\langle j,k|}{i\omega_n-\epsilon_j}
\end{align}
$$
==*Bernevig. (3.62)*==
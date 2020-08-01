

平均场近似下的BCS哈密顿量
$$
H=\sum_r\left(h^{\sigma\sigma'}_rc^\dagger_{\sigma r}c_{\sigma'r}+\Delta_rc^\dagger_{\uparrow r}c_{\downarrow r}+h.c\right)
$$



有费米子对易关系
$$
\{c_{\sigma r}^\dagger,c_{\sigma' r'}\}=\delta_{\sigma\sigma'}\delta_{rr'}
$$





南部spinor
$$
\Psi_r=\begin{bmatrix}
c_{r\uparrow}\\ 
c_{r\downarrow}\\ 
c_{r\downarrow}^\dagger\\ 
-c_{r\uparrow}^\dagger
\end{bmatrix}=\begin{bmatrix}
\begin{bmatrix}
c_{r\uparrow}\\ 
c_{r\downarrow}
\end{bmatrix}\\ 
 
i\sigma_y\begin{bmatrix}
c_{r\uparrow}^\dagger\\ 
c_{r\downarrow}^\dagger
\end{bmatrix} 

\end{bmatrix}
$$
从而哈密顿量可以用南部spinor表示
$$
\begin{align}H&=\sum_r\Psi_r^\dagger\mathcal{H}_{BdG}\Psi_r\\&=\sum_{r}\left(\begin{bmatrix}
\begin{bmatrix}
c^\dagger_{r\uparrow} &c^\dagger_{r\downarrow} 
\end{bmatrix} & \begin{bmatrix}
c_{r\uparrow} &c_{r\downarrow} 
\end{bmatrix}\cdot(-i)\sigma_y
\end{bmatrix}\mathcal{H}_{BdG}\begin{bmatrix}
\begin{bmatrix}
c_{r\uparrow}\\ 
c_{r\downarrow}
\end{bmatrix}\\ 
 
i\sigma_y\begin{bmatrix}
c_{r\uparrow}^\dagger\\ 
c_{r\downarrow}^\dagger
\end{bmatrix} 

\end{bmatrix}\right)
\end{align}
$$
==**首先处理对角项**==
$$
\begin{align}
\sum_r h^{\sigma\sigma'}_rc^\dagger_{\sigma r}c_{\sigma'r}&=
\sum_r\lim_{r'\rightarrow r} h^{\sigma\sigma'}_rc^\dagger_{\sigma r}c_{\sigma'r'}\\&=\frac{1}{2}\sum_r\lim_{r'\rightarrow r}\left(h^{\sigma\sigma'}_rc^\dagger_{\sigma r}c_{\sigma'r'}-h^{\sigma\sigma'}_rc_{\sigma'r'}c^\dagger_{\sigma r}+\delta_{\sigma\sigma'}\delta_{rr'}h_r^{\sigma\sigma'}\right)
\end{align}
$$

第二行最后一项$\sum_{r\sigma}h^{\sigma\sigma}_r=E_g$为基态能量。$h_r$为厄米矩阵，所以$h^{\sigma\sigma'}=(h^{\sigma'\sigma})^*$。

所以对角项为
$$
\mathcal{H}_{BdG}=\begin{bmatrix}
\hat{h}_r & \\ 
 & -\sigma_y\hat{h}^*_r\sigma_y
\end{bmatrix}
$$
时间反演算符
$$
\mathcal{T}=i\sigma_yK
$$

$$
 H_h=-\sigma_y\hat{h}^*_r\sigma_y=-\mathcal{T}H_e\mathcal{T}^{-1}
$$


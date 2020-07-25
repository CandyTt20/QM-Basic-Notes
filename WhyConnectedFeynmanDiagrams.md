#### 为什么只需要考虑连接图？

将$n$阶微扰分为$m$阶连接图和$l=n-m$阶真空图。
$$
\begin{align}
G(x,x')&=\frac{\sum_{n=0}^\infty\frac{(-i)^n}{n!}\int_{t_1t_2...t_n}\lang\phi_0|\hat{T}\psi(x)\psi^\dagger(x')V(t_1)...V(t_n)|\phi_0\rangle}{\langle\phi_0|S(+\infty,-\infty)|\phi_0\rangle}\\&=\frac{1}{D}\sum_{n=0}^\infty\sum_{m=0}^\infty\sum_{l=0}^\infty\frac{(-i)^n}{n!}\frac{n!}{m!\cdot l!}\delta_{m+l,n}\int_{t_1t_2...t_m}\lang\phi_0|\hat{T}\psi(x)\psi^\dagger(x')V(t_1)...V(t_m)|\phi_0\rangle_c\\&\times\int_{t_{m+1}t_{m+2}...t_n}\lang\phi_0|\hat{T}V(t_{m+1})...V(t_n)|\phi_0\rangle\\&=\frac{1}{D}\sum_{m=0}^\infty\frac{(-i)^m}{m!}\int_{t_1t_2...t_m}\lang\phi_0|\hat{T}\psi(x)\psi^\dagger(x')V(t_1)...V(t_m)|\phi_0\rangle_c\\&\times\sum_{l=0}^\infty\frac{(-i)^l}{l!}\int_{t_{1}t_{2}...t_{l}}\lang\phi_0|V(t_{1})...V(t_l)|\phi_0\rangle\\&=\frac{1}{D}\langle\phi_0|S(+\infty,-\infty)|\phi_0\rangle\sum_{m=0}^\infty\frac{(-i)^m}{m!}\int_{t_1t_2...t_m}\lang\phi_0|\hat{T}\psi(x)\psi^\dagger(x')V(t_1)...V(t_m)|\phi_0\rangle_c\\&=\sum_{m=0}^\infty\frac{(-i)^m}{m!}\int_{t_1t_2...t_m}\lang\phi_0|\hat{T}\psi(x)\psi^\dagger(x')V(t_1)...V(t_m)|\phi_0\rangle_c\
\end{align}
$$

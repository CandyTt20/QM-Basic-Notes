### density operator

In first quantization, the density operator is $\hat{\rho}(x)=|x\rangle\langle x|$,  **how to obtain the many-body operator?** 
$$
\hat{\rho}(x)=\sum_i \hat{\rho}_i(x)
$$
which can be prove that
$$
\begin{align}
\hat{\rho}(x)&=\sum_i \hat{\rho}_i(x)=\int_{1,2}\psi^\dagger(x_1)\rho_{x_1,x_2}(x)\psi(x_2)\\&=\int_{1,2}\psi^\dagger(x_1)\langle x_1|x\rangle\langle x|x_2\rangle\psi(x_2)\\&=\int_{1,2}\psi^\dagger(x_1)\psi(x_2)\delta(x_1-x)\delta(x-x_2)\\&=\psi^\dagger(x)\psi(x)
\end{align}
$$

 in second quantization. 

**Why we always see the expression like $n(x)=\sum_i\delta(x-x_i)$?**
$$
\rho_i(x)\psi(x)=\langle x_i|x\rangle\langle x|\psi\rangle=\delta(x_i-x)\psi(x)
$$
so obtain the 'density operator' in x_i representation $\rho_i(x)=\delta(x-x_i)$, then the many-body expression is $\rho(x)=\sum_i\rho_i(x)=\sum_i\delta(x-x_i)$. I personally think that this form of expression is extremely irregular. But all textbooks are written like this. The $\rho(x)$ here can not even be called as an operator, ==cause every operator must have two subscripts==. 
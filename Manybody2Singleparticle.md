#### 从二次量子化算符过渡到单粒子算符

==用密度算符举例==

1. 单粒子情况

$$
\rho=\langle\psi|\hat{\rho}|\psi\rangle=\langle\psi|x\rangle\langle x|\psi\rangle=\psi^*(x)\psi(x)
$$

2. 二次量子化情形

   单粒子态$|\lambda\rangle=c_\lambda^\dagger|0\rangle$是哈密顿量的本征态，满足$\hat{H}|\lambda\rangle=\varepsilon_\lambda|\lambda\rangle$,定态薛定谔方程即为$\langle x|\hat{H}|\lambda\rangle=\varepsilon_\lambda\langle x|\lambda\rangle$,即$\hat{H}\psi_\lambda(x)=\varepsilon_\lambda\psi_\lambda(x)$.

   密度算符用$\lambda$的产生湮灭算符写为
   $$
   \hat{\rho}=\int_{\lambda_1\lambda_2}c^\dagger_{\lambda_1}\langle\lambda_1|x\rangle\langle x|\lambda_2\rangle c_{\lambda_2}
   $$
   所以$\lambda$态下的粒子数密度为
   $$
   \begin{split}
   \langle \lambda|\hat{\rho}|\lambda\rangle&=\int_{\lambda_1\lambda_2}\lang\lambda|c_{\lambda_1}^\dagger\langle\lambda_1|x\rangle\langle x|\lambda_2\rangle c_{\lambda_2}|\lambda\rang\\&=\int_{\lambda_1\lambda_2}\lang 0|c_\lambda c_{\lambda_1}^\dagger c_{\lambda_2}c^\dagger_\lambda|0\rangle\varphi^*_{\lambda_1}(x)\varphi_{\lambda_2}(x)\\&=\int_{\lambda_1\lambda_2}\delta_{\lambda_1\lambda}\delta_{\lambda_2\lambda}\varphi^*_{\lambda_1}(x)\varphi_{\lambda_2}\\&=\varphi^*_{\lambda}(x)\varphi_{\lambda}(x)
   \end{split}
   $$
   退回到单粒子情形。


### Current Operator

The form of the current operator can be well understood if you are on top of the bra-ket notation. We can start from the single particle Schrodinger equation acting on the vector $\mid\psi\rangle$ with x-representation, one can obtain the current by performing some calculations


$$
j(x)=\frac{e}{m}\text{Re}\left[\psi^*(x)\hat{p}\psi(x) \right]=\frac{e}{2m}\left(\langle\psi|x\rangle\langle x|\hat{p}|\psi\rangle+\langle \psi |\hat{p}^{\dagger}|x\rangle\langle x|\psi\rangle\right)
$$
where $j(x)$ is the current acting on the state $|\psi\rangle$, name $j(x)=\langle\psi| \hat{j}(x)|\psi\rangle$, here $\hat{j}(x)$ is the single particle current operator expressing as
$$
\hat{j}(x)=\frac{e}{2m}\left(|x\rangle\langle x|\hat{p}+\hat{p}^{\dagger}|x\rangle\langle x|\right)
$$
==How to get the $\delta$-function type expression?==

Let's consider the many body system, the current operator acting on the i-th particle state $\psi(x_i)$ is given as $\langle x_i|\hat{j}(x)|\psi\rangle$, which is given as 
$$
\begin{align}
\langle x_i|\hat{j}(x)|\psi\rangle&=\frac{e}{2m}\left(\langle x_i|x\rangle\langle x|\hat{p}|\psi\rangle+\langle x_i|\hat{p}^{\dagger}|x\rangle\langle x|\psi\rangle\right)\\&=\frac{e}{2m}\left(\delta(x_i-x)\frac{\hbar}{i}\frac{\partial\psi(x)}{\partial x}+\frac{\hbar}{i}\frac{\partial\delta(x_i-x)}{\partial(x_i-x)}\psi(x)\right)\\&=J(x)\psi(x)
\end{align}
$$
where $J(x)$ is the *current operator* 
$$
J(x)=\frac{e\hbar}{2mi}\left(\delta(x_i-x)\frac{\partial}{\partial x}+\frac{\partial}{\partial x_i}\delta(x_i-x)\right)
$$

#### Secondary Quantization 

For an arbitrary many-body operator $\sum_iA_i$ , the creation-annihilation expression is
$$
\sum_i\hat{A}_i
$$


#### Momentum Space


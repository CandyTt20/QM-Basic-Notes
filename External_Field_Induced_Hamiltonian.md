Now considering the system with applied external electric field, by employing the form of the current operator, one can proof that the Hamiltonian can be expressed as $H=H_0+H_{ext}$. where $H_0$ is the unperturbed Hamiltonian, $H_{ext}$ is the Hamiltonian with external field, which is given as
$$
\hat{H}_{ext}=-\int_x \hat{j}(x)\cdot \hat{A}(x)
$$
where $\hat{A}(x)$ is the operator of the external field, as a function of position $\vec{x}=x$, （for simplicity consider the 1-D single particle case).
$$
\hat{H}=\frac{e}{2m}\left(\hat{p}-e\hat{A}(x)\right)^2+\hat{V}(x)
$$
is the total Hamiltonian (choose $c=1$), which gives the current operator with the external field 
$$
\begin{align}
\hat{j}(x)&=\frac{1}{2m}\left(|x\rangle\langle x|\hat{\pi}+\hat{\pi}^{\dagger}|x\rangle\langle x|\right)\\&=\hat{j}_0(x)+\hat{j}_A(x)
\end{align}
$$
where $\hat{\pi}=\hat{p}-e\hat{A}(x)$. Here we just consider the first order of $A$,
$$
\hat{H}_{ext}=-\frac{e}{2m}(\hat{p}\cdot\hat{A}(x)+\hat{A}(x)\cdot\hat{p})
$$
Remember that all the operators we care about in this case behave like $n\times n$ matrices ($n\rightarrow +\infty $), to avoid confusions, one needs to calculate the term like $\langle x_i|-\int_x\hat{j}(x)\cdot\hat{A}(x)|\psi\rangle$ and proof that equals to $\langle x_i|H_{ext}|\psi\rangle$, which is straight by using the expansion of $\hat{j}_0(x)$:
$$
\begin{align}-\int_x\langle x_i|\hat{A}(x)\cdot\hat{j}_0(x)|\psi\rangle&=\int_x\int_y\langle x_i|\hat{A}(x)|y\rangle\langle y|\hat{j}_0(x)|\psi\rangle\\&=-\frac{e}{2m}\int_x\int_y\left(A(y)\delta(x_i-y)\delta(y-x)\frac{1}{i}\frac{\partial\psi(x)}{\partial x}\right)\\&-\frac{e}{2m}\int_x\int_y\left(A(y)\delta(x_i-y)\frac{1}{i}\frac{\partial \delta(y-x)}{\partial(y-x)}\psi(x)\right)\\&=-\frac{e}{2m}\left(A(x)\frac{1}{i}\frac{\partial\psi(x_i)}{\partial x_i}+\frac{1}{i}\frac{\partial A(x_i)\psi(x_i)}{\partial x_i}\right)\\&=\langle x_i|\hat{H}_{ext}|\psi\rangle
\end{align}
$$
Usage.
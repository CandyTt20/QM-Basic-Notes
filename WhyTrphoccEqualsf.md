#### Why $\langle c^\dagger_kc_k\rangle=f(\varepsilon_k)$?

Considering the many-body system with Hamiltonian $H=\sum_k\varepsilon_k c^\dagger_kc_k$, $c_k$ is the annihilation operator of Fermion or Boson. The wave function $|n\rangle=|n_1n_2...n_i...\rangle$ satisfying $H|n\rangle=E_n|n\rangle$ gives the many-body eigen-functions, where $E_n$ is the eigen-energy of the system,  $E_n=\sum_{i}n_i\varepsilon_i$, $\sum_in_i=N$.
$$
\begin{align}
\langle c^\dagger_kc_k\rangle&=\frac{\sum_{n}e^{-\beta E_n}\langle n|c^\dagger_kc_k|n\rangle}{\sum_n e^{-\beta E_n}}\\&=\frac{\sum_{n_1n_2...}n_ke^{-\beta(n_1\varepsilon_1+n_2\varepsilon_2+...)}}{\sum_{n_1n_2...}e^{-\beta(n_1\varepsilon_1+n_2\varepsilon_2+...)}}\\&=\frac{\sum_{n_k}n_ke^{-\beta n_k\varepsilon_k}\sum^{(k)}_{n_1n_2...}e^{-\beta(n_1\varepsilon_1+n_2\varepsilon_2+...)}}{\sum_{n_k}e^{-\beta n_k\varepsilon_k}\sum^{(k)}_{n_1n_2...}e^{-\beta(n_1\varepsilon_1+n_2\varepsilon_2+...)}}
\end{align}
$$
Define $\sum^{(k)}_{n_1n_2...}e^{-\beta(n_1\varepsilon_1+n_2\varepsilon_2+...)}\equiv Z_k(N-n_k)$



##### ==1. Boson==

$$
\begin{align}
\langle c^\dagger_kc_k\rangle&=\frac{\sum_{n_k}n_k e^{-\beta\varepsilon_kn_k}Z_k(N-n_k)}{\sum_{n_k} e^{-\beta\varepsilon_kn_k}Z_k(N-n_k)}\\&=\frac{e^{-\beta\varepsilon_k}Z_k(N-1)+2e^{-2\beta\varepsilon_k}Z_k(N-2)+...+Ne^{-N\beta\varepsilon_k}Z_k(0)}{1+e^{-\beta\varepsilon_k}Z_k(N-1)+e^{-2\beta\varepsilon_k}Z_k(N-2)+...+e^{-N\beta\varepsilon_k}Z_k(0)}\\&=\frac{q+2q^2+...+Nq^N}{1+q+q^2+...+q^N}\\&=\frac{q}{1-q}~~~~~~~~~~(N\rightarrow\infty)
\end{align}
$$

with the relations $Z_k(N-1)/Z_k(N)=e^{\beta\mu}$, $q=e^{-\beta(\epsilon_k-\mu)}$, one obtains the BE distribution 
$$
\langle c^\dagger_kc_k\rangle=\frac{1}{e^{\beta(\varepsilon_k-\mu)}-1}
$$

##### ==2. Fermion==

$$
\begin{align}
\langle c^\dagger_kc_k\rangle&=\frac{\sum^1_{n_k=0}n_k e^{-\beta\varepsilon_kn_k}Z_k(N-n_k)}{\sum^1_{n_k=0} e^{-\beta\varepsilon_kn_k}Z_k(N-n_k)}\\&=\frac{e^{-\beta\varepsilon_k}Z_k(N-1)}{Z_k(N)+e^{-\beta\varepsilon_k}Z_k(N-1)}\\&=\frac{1}{e^{\beta(\varepsilon_k-\mu)}+1}
\end{align}
$$


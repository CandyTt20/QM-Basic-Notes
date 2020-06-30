### Math Basic

==Matsubara Green function== defines as (boson)  $G^T(\sigma)=-\lang \mathcal{T}A(\sigma)B\rang=-\theta(\sigma)\lang A(\sigma)B\rang-\theta(-\sigma)\lang BA(\sigma)\rang$ .

==**<u>Obtain the interval of the imagery time</u>**==
$$
\begin{align}
G^T(\sigma>0)&=-\lang \mathcal{T}A(\sigma)B\rang=-\frac{1}{Z}\text{tr}\left(e^{-\beta H}e^{\sigma H}Ae^{-\sigma H}B\right)\\&=-\frac{1}{Z}\text{tr}\left(e^{(\sigma-\beta) H}Ae^{-(\sigma-\beta) H}e^{-\beta H}B\right)\\&=-\frac{1}{Z}\text{tr}\left(e^{-\beta H}Be^{(\sigma-\beta) H}Ae^{-(\sigma-\beta) H}\right)\\&=G^T\left(\sigma-\beta<0\right)
\end{align}
$$
From this equation one finds that $0<\sigma<\beta$. Similarly, when considered $\sigma<0$, one finds that 
$$
G^T(\sigma<0)=G^T(\sigma+\beta>0)
$$


which gives $-\beta<\sigma<0$. Then we have the imagery time $-\beta<\sigma<\beta$.

==**<u>Fourier Transformation of Matsubara Green function</u>**== (~~In this section I omit the superscript T~~)
$$
G(\sigma)=\sum_\omega e^{-i\omega\sigma}G(i\omega)=G(\sigma+\beta)
$$
which gives $e^{-i\omega\beta}=1\rightarrow \omega=\omega_n=2n\pi/\beta$. Then the summation of the frequency is expressed as 
$$
G(\sigma)=\frac{1}{\beta}\sum_n e^{-i\omega_n\sigma}G(i\omega_n)
$$
**The factor $\frac{1}{\beta}$ is chosen to make the inverse transformation have an unit factor**
$$
G(i\omega_n)=\int_0^\beta  e^{i\omega_n\sigma}G(\sigma)d\sigma
$$
==Retarded Green function== $G^R(t)=-i\theta(t)\langle [A(t),B]\rang$ 
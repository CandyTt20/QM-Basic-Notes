### Current-Current Correlation Function


$$
\begin{align}
G(x_1,x_2,t_1-t_2)&=-i\theta(t_1-t_2)\left\langle[j_i(x_1,t_1),j_j(x_2,t2)] \right\rangle\\&=\int\frac{dq_1dq_2}{(2\pi)^6}G(q_1,q_2,t_1-t_2)e^{iq_1x_1}e^{iq_2x_2}\\&=-i\theta(t_1-t_2)\times\\&\int\frac{dq_1dq_2}{(2\pi)^6}\lang[j_i(-q_1,t_1),j_j(-q_2,t_2)]\rangle e^{iq_1(x_1-x_2)}e^{i(q_1+q_2)x_2}
\end{align}
$$


The third line equation comes frmo the Fourier transformation relation of the current operator
$$
\begin{align}
j(x)=&\int_q e^{-iqx}j(q)\\
j(q)=&\int_x e^{iqx}j(x)
\end{align}
$$
 which is differnt from the original FT relation with a minus sign. This is because the current operator is proportional to momentum $p$ , FT of  momentum is different of the origional position-FT with a minus sign to satisfy the quantization relation. 

Next considering the translation invariance, where $G(x_1,x_2)=G(x_1-x_2)$ only the function of $x_1-x_2$ , 
$$
\begin{align}x_1-x_2=x\\
x_2=y
\end{align}
$$
 then one find that 
$$
\begin{align}
&G(x,y,t_1-t_2)\\&=-i\theta(t_1-t_2)\times\int\frac{dq_1dq_2}{(2\pi)^6}\lang[j_i(-q_1,t_1),j_j(-q_2,t_2)]\rangle e^{iq_1x}e^{i(q_1+q_2)y}\\&=\frac{-i\theta(t_1-t_2)}{V}\times\int\frac{dq_1dq_2}{(2\pi)^6}\lang[j_i(-q_1,t_1),j_j(-q_2,t_2)]\rangle e^{iq_1x}\int dye^{i(q_1+q_2)y}\\&=\frac{-i\theta(t_1-t_2)}{V}\times\int\frac{dq_1dq_2}{(2\pi)^6}\lang[j_i(-q_1,t_1),j_j(-q_2,t_2)]\rangle e^{iq_1x}(2\pi)^3\delta(q_1+q_2)\\=&\frac{-i\theta(t_1-t_2)}{V}\times\int\frac{dq_1dq_2}{(2\pi)^3}\lang[j_i(-q_1,t_1),j_j(q_1,t_2)]\rangle e^{iq_1x}
\end{align}
$$
Comparing to 
$$
G(x,t_1-t_2)=\int\frac{dq}{(2\pi)^3}G(q)e^{iqx}
$$
one find that 
$$
\begin{align}
G(q,t_1-t_2)&=-\frac{i\theta(t_2-t_2)}{V}\langle [j_i(-q,t_1),j_j(q,t_2)]\rangle\\&=-\frac{i\theta(t_2-t_2)}{V}\langle [j^\dagger_i(q,t_1),j_j(q,t_2)]\rangle
\end{align}
$$
This relation is satisfied with **Mahan** ==p165-(3.387)==


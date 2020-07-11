### Proof of the Detailed Balance Relation in Furusaki-Tsukada's paper (1991)

I firstly consider the simplest configuration: the S/I/S junction, where the pair potential of two s-sides have the same amplitude $\Delta$ , the phase of the left side is 0 and the right side is $\varphi$, the insulator region is modified by $Z\delta(x)$ . I obtained the phase relation of the scattering coefficients by directly calculation, wehre $a_i(b,c,d),i=1,2,3,4$ are the same as Furusaki-Tsukada's paper (1991).
$$
\begin{align}
a_1(\varphi)&=a_2(-\varphi)\\
a_3(\varphi)&=a_4(-\varphi)\\
b_i(\varphi)&=b_i(-\varphi)\\
c_1(\varphi)&=c_3(-\varphi)\\
c_2(\varphi)&=a_4(-\varphi)\\
d_1(\varphi)&=d_4(-\varphi)\\
d_2(\varphi)&=d_3(-\varphi)\\
\end{align}
$$
The general case relation can be obtained by particle current conservation. In normal state conductor, the particle current can be viewed as the same as the the electron current, which is only different with the coefficient $e$
$$
j_e=ej_p
$$
However, in superconductors, $j_e$ and $j_p$ are totally different. Considering the wave function of the quasi-particle is written as $\psi=[u,v]^{T}$, where $\psi$ satisfies BdG equation. The particle density is $\rho=\psi^\dagger\psi$, by employing the equation of continuity  
$$
\frac{\partial\rho}{\partial t}+\nabla\cdot j_p=0
$$
One obtain the particle current is 
$$
j_p=\frac{\hbar}{m}\left[\text{Im}(u^*\nabla u)-\text{Im}(v^*\nabla v)\right]
$$

- type 1 process

  - incident particle current: $j_{i1}\propto k_L^+(u_L^2-v_L^2)=k_L^+\Omega_L$ 


  - Andreev reflection particle current: $j_{a_1}\propto a_1^2(\varphi)\cdot k_L^-(v_L^2-u_L^2)=-k_L^-\Omega_La_1^2(\varphi)$


  - particle current without branch crossing: $j_{c1}\propto c_1^2(\varphi)k_R^+\Omega_R$

- type 2 process

  - incident particle current: $j_{i2}\propto -k_L^-(v_L^2-u_L^2)=k_L^-\Omega_L$ 


  - Andreev reflection particle current: $j_{a_2}\propto a_2^2(-\varphi)\cdot (-k_L^+)(u_L^2-v_L^2)=-k_L^+\Omega_La_2^2(-\varphi)$

- type 3 process

   - incident particle current: $j_{i3}\propto k_R^+(u_R^2-v_R^2)=k_R^+\Omega_R$ 

   - particle current without branch crossing: $j_{c3}\propto c_3^2(-\varphi)k_L^+\Omega_L$

- type 4 process

   - incident particle current: $j_{i4}\propto k_R^-(u_R^2-v_R^2)=k_R^-\Omega_R$
   - particle current without branch crossing: $j_{d4}\propto d_4^2(-\varphi)k_L^+\Omega_L$

1. From $j_{a1}/j_{i1}=j_{a2}/j_{i2}$
   $$
   \begin{align}\frac{-k_L^-\Omega_La_1^2(\varphi)}{k_L^+\Omega_L}&=\frac{-k_L^+\Omega_La_2^2(-\varphi)}{k_L^-\Omega_L}\\k_L^-a_1(\varphi)&=k_L^+a_2(-\varphi)\end{align}
   $$


   ​				
   ​					
   ​						

2. From $j_{c1}/j_{i1}=j_{c3}/j_{i3}$
   $$
   \begin{align}\frac{k_R^+\Omega_Rc_1^2(\varphi)}{k_L^+\Omega_L}&=\frac{k_L^+\Omega_Lc_3^2(-\varphi)}{k_R^-\Omega_R}\\k_R^+\Omega_R c_1(\varphi)&=k_L^+\Omega_L c_3(-\varphi)\end{align}
   $$


   ​				
   ​					
   ​						

3. From $j_{d1}/j_{i1}=j_{d4}/j_{i4}$

$$
\begin{align}
\frac{k_R^-\Omega_Rd_1^2(\varphi)}{k_L^+\Omega_L}&=\frac{k_L^+\Omega_Ld_4^2(-\varphi)}{k_R^-\Omega_R}\\
k_R^-\Omega_R d_1(\varphi)&=k_L^+\Omega_L d_3(-\varphi)
\end{align}
$$

These are the relations of equ.(5) in the paper.
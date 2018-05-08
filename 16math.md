
# 16.1

## Problem 1

The tribonacci numbers { $T_n$ }  are defined for non-negative integers n as follows.
$$
\begin{aligned}
\begin{cases}
    T_0 &= T_1 = 0
\\T_2 &= 1 
\\ T_{n+3} &= T_{n+2} + T_{n+1} + T_n  & (n ≥ 0).
\end{cases}
\end{aligned}
 $$
Answer the following questions.
(1) Find the matrix A that satisfies Eq. (1.1) for all non-negative integers n.
$$ \begin{pmatrix}T_{n+3} \\ T_{n+2} \\T_{n+1}\end{pmatrix}
= A\begin{pmatrix} T_{n+2} \\T_{n+1}\\T_{n}  \end{pmatrix}   (1.1)$$

(2) Find the rank and the characteristic equation, i.e., the equation that eigenvalues satisfy, of the matrix A.

(3) Let λ1, λ2, λ3 denote the eigenvalues of the matrix A. Express an eigenvector corre-sponding to each of the eigenvalues using λ1, λ2, λ3.

(4) Prove that the matrix A has only one real number eigenvalue. Letting λ1 correspond to this eigenvalue, prove that 1 < λ1 < 2.
(5) Prove that Tn can be expressed as $T_n = c_1λ_1^n + c_2λ_2^n + c_3λ_3^n$ using constant complex numbers c1, c2, c3. You do not need to find values of c1, c2, c3 explicitly.
(6) Prove$$\lim_{n→∞}\frac{Tn+1}{Tn}= λ_1$$.

## solution 1
(1)
$$ 
\begin{aligned}
   \begin{pmatrix}T_{n+3} \\ T_{n+2} \\T_{n+1}\end{pmatrix}
   &= \begin{pmatrix} a_{11} & a_{12} & a_{13}\\a_{21} & a_{22} & a_{23}\\a_{31} & a_{32} & a_{33} \end{pmatrix} 
         \begin{pmatrix} T_{n+2} \\T_{n+1}\\T_{n}  \end{pmatrix} 
        \\ & = \begin{pmatrix} a_{11}T_{n+2}  & a_{12} T_{n+1} & a_{13}T_{n} \\
a_{21}T_{n+2}  & a_{22} T_{n+1} & a_{23}T_{n} \\
a_{31}T_{n+2}  & a_{32} T_{n+1} & a_{33}T_{n}  \end{pmatrix} 
 \begin{matrix}\leftarrow T_{n+3} = T_{n+2} + T_{n+1} + T_n \\ \\\end{matrix} 
 \\&= \begin{pmatrix} 1*T_{n+2}  & 1* T_{n+1} & 1*T_{n} \\
1*T_{n+2}  & 0* T_{n+1} & 0*T_{n} \\
0*T_{n+2}  & 1*T_{n+1} & 0*T_{n}  \end{pmatrix} 
\end{aligned}
 $$


$$ 
  A= \begin{pmatrix} 
 1 & 1 & 1 \\
1& 0& 0\\
0 & 1 & 0 \end{pmatrix}   $$

(2)
> det(λI − A) = 0 を固有方程式あるいは特性方程式と言う
>
 $$ 
  A= \begin{pmatrix} 
 1 & 1 & 1 \\
1& 0& 0\\
0 & 1 & 0 \end{pmatrix} \longrightarrow 
\begin{pmatrix} 
 1 & 1 & 1 \\
0& 1& 1\\
0 & 1 & 0 \end{pmatrix}\longrightarrow 
\begin{pmatrix} 
 1 & 1 & 1 \\
0& 1& 1\\
0 & 0 & 1\end{pmatrix}   $$
$rank(A)=3$

 $$  det(A-I)=0=\begin{bmatrix}1-\lambda & 1 & 1 \\
 1 & -\lambda & 0\\
 0&1& -\lambda \end{bmatrix}=\lambda^2(1-\lambda)+1-(-\lambda)$$ 

(3)

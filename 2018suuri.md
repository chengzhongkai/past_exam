## 第1問  
$\mathbb{C}$を複素数体とし，$A$を$\mathbb{C}$上のn次正方行列とする. Aの不変部分空間とは, $\mathbb{C}^n$の部分ベクトル空間Uであって, $AU\subseteq U$となるものである. $S_A$をAのすべての不変部分空間からなる集合とする. $S_A$上の半順序$\preceq$を包含関係$\subseteq$により定め，S_Aを半順序集合とみなす.  
  以下の設問に答えよ．束やハッセ図については下の注意も参考にせよ．  

**(1)(1-1) $S_A$は束になることを示せ.**  
(1-2）正則行列Pに対して$S_AとS_{P^{-1}AP}$は半順序集合として同型であることを示せ．  
(1-3）複言語数$\alpha$に対して，$S_A=S_{A＋\alpha I}$を示せ．ただし，Iは単位行列である．  
(2)Aが以下の行列であるときの$S_A$のハツセ図をそれぞれ図示せよ  
$$ 
\begin{pmatrix}
2 & 0 & 0 \\
0 & 3 & 0 \\
0 & 0 & 5 \\
\end{pmatrix},
\begin{pmatrix}
-2 & -1 & -2 \\
4 & 3 & 2 \\
4 & 1 & 4 \\
\end{pmatrix},
\begin{pmatrix}
3 & 1 & 1 \\
-2 & -1 & 0 \\
-3 & -1 & -1 \\
\end{pmatrix}
$$
(3)$S_A$の要素数が有限となる行列Aはどのようなもので，そのときの$S_A$のハツセ関はどのような形をしているか説明せよ．  
（注意）$\preceq$を半順序とする半順序集合$\L$が束であるとは，任意の$x,y\in\L$に対して以下の二つの性質が成り立っときをいう：  
-	集合$｛u\in\L| x\succeq u \preceq y｝$に極大元がただ一つ存在する．
-	集合$｛u\in\L|x\preceq u \succeq y｝$に極小元がただ一つ存在する．
また，$\L$のハツセ図とは，$\L$の要素を頂点とし，以下の性質を満たすすべての異なる要素x,y\in\Lにxからuへ枝を引いて得られる有向グラフである:  
- $x\preceq yかつ｛z\in\mathbb{L} | x\preceq z \preceq y\}=\{x,y\}.$

  
## Problem 1   
Let $\mathbb{C} $ be the field of complex numbers. Let A be an n by n matrix over $\mathbb{C} $. An invariant subspace of A is a subspace U of $\mathbb{C}^n $ such that $AU \subseteq U$. Let $S_A$ denote the set of all invariant subspaces of A. A partial order $\preceq$ on S_A is defined as the inclusion relation $\subseteq$ and SA is regarded as a partially ordered set. 
Answer the following questions. Refer to the remark below for lattice and Hasse diagram. 
**(1)(1-1)Show that $S_A$ is a lattice. **
  


## 第2問  
Rを実数全体の集合とし，R上の二つの確率分布$P_1,P_2$を考える. $P_1,P_2$それぞれに 確率密度関数p1,p2:R→Rが存在し$ Oくp1(x)/p2(x）く\infty(\forall_x \in R.）$を満たすとき， P1のP2に対するKullback-Leiblerダイパージェシスは以下のように定義される・
## Problem 2 
Let $\mathbb{R}$ be the set of real numbers. Suppose that $P_1$ and $P_2$ are probability distributions on $\mathbb{R}$. When  $P_1$ and $P_2$ have probability density functions $p1, p2: \mathbb{R}\to\mathbb{R}$, respectively, satisfying $ O<p1(x)/p2(x）<\infty(\forall_x \in R.)$, the Kullback-Leibler divergence from $P_2$ to $P_1$ is defined by 
$$ D(P1||P2)=\int_{-\infty}^\infty p_1(x)log\left( \frac{p_1(x)}{p_2(x)}\right)  dx$$
The normal distribution with mean $\mu\in R$ and variance $\sigma^2 > 0 $is denoted by $N(\mu, \sigma^2 )$. The expectation of a random variable Z is denoted by E\[Z\]. For a cumulative distribution function $\Psi$, the function $\Psi : (0, 1) \to R $ is defined by $\Psi^{-1}(t) = inf\{x \in R | \Psi > t \}$. Answer the following questions. 

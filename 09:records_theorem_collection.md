Consider an infinite sequence $(X_n)$ of independent observations from a CDF $F$, admitting a density $f$. We say $X_i$ is a record value if $X_i \gt X_j$, for all $0 \leq j \lt i$, where we set $X_0 = 0$.  
Let $I_i$ be the indicator of the event that $X_i$ is a record. Prove that $$(I_i)$$ is an infinite sequence of independent $$\text{Bernoulli}\left(\frac1i\right)$$ rvs.  
Let $T_i$ be the sequence of record times; $$T_1 = 1$; $T_i = \min\limits_{j\gt T_{i-1}} \left[j : Z_j = 1\right].$$ Define $R_k := X_{T_k}$ as the $k$-th record value. Prove that the density $f_r(y)$ of $R_r$ is $$\frac{(-ln(1-F(y)))^{r-1}}{(r-1)!}f(y)$$.  
Let $D_{i+1}:=T_{i+1}-T_i$. Let $r \geq 2$, $k \geq 1$. Prove that $P(D_r = k) = \sum\limits_{i=0}^{k-1}{ (-1)^i \binom{k-1}{i} (i + 2)^{-r} }.$  
Prove that the joint density of the first $n$ record values $R_1,\dots,R_n$ is given by $f_{1,\dots,n}(y_1,\dots,y_n) = f(y_n) \prod\limits_{i=1}^{n-1}{ \frac{f(y_i)} {1 - F(y_i)} I_{y_1\lt\dots\lt y_n} }$.
<!---
Double dollars are because latex in markdown on github shits the bed otherwise.
-->

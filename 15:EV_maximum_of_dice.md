Inspired by [this video][1], prove that the expected value of the maximum of $m$ independently thrown $n$-sided dice equals
$E(M) = n-\frac{1}{m+1}\sum\limits_{\ell=0}^{m}\binom{m+1}{\ell}B_\ell n^{1-\ell}$, where $B_\ell$
is the $\ell$-th Bernoulli number.  
It follows that $E(M) = n\frac{m}{m+1}+\frac12+O_{n\to\infty}\left(\frac1n\right)$ and $E(M) = n+o_{m\to\infty}(1)$.  
If we consider instead the maximum $N_n$ of $n$
independently thrown
$n$-sided dice, find the
constant $\alpha>\frac12$ such that the limiting expected distance of the maximum roll to the maximum value
$\lim\limits_{n\to\infty}E\left(\left|n-N_n\right|\right)=\alpha$.

[1]:https://www.youtube.com/watch?v=X_DdGRjtwAo

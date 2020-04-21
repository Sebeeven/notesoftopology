# Chapter I Basic Homotopy

### Homotopy I
- Definition I :  

$$ 
\begin{aligned}
  F:  X \times I &\rightarrow Y \\
  F(x,0) &= f(x) \\
  F(x,1) &= g(x) \\
  f \ &{\simeq}_{F} \ g
\end{aligned}
$$

`![homotopy1](.\homotopy1.png)`

- Pasting Lemma :

$$ 
\begin{aligned}
  & for \quad F,G :  X \times I \rightarrow Y \\
  & \exists \quad 
  H(x,t) = \begin{cases}
  F(x,2t), & 0 \leqslant t \leqslant  \frac{1}{2} \\
  G(x,2t-1), & \frac{1}{2} \leqslant t \leqslant 1
      \end{cases} \\
   & and \quad F(x,1) = G(x,0) \\
   & s.t. \quad H(x,t)  = F(x,t) + G(x,t)
\end{aligned}
$$

`![homotopy2](.\homotopy2.png)`


### Homotopy II
- Definition II :  

$$
\begin{aligned}
  f_t :  X &\rightarrow Y \\
  f_t(x) &= F(x,t) \\
  f_0(x) &= f(x) \\
  f_1(x) &= g(x)
\end{aligned}
$$

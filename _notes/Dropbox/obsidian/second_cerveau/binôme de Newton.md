#📤 
___
Pour tout $u$, $v$ $\in C$ et $n \in N$ :
$$
(a+b)^n=\sum_{k=0}^n \binom nk u^{n-k} v^{k}
$$
Ce qui se passe : $(a+bi)^{n}=\textit{ligne n du triangle de Pascal } \times a^{n-k} \times (3i)^{n-(n-k)}$
### Triangle de Pascal
$$
\newcommand\cn[2]{\llap{#1}\rlap{#2}\,}
\begin{array}{c}
&&&&&\cn{}{}&\cn{1}{}&\cn{}{}\\
&&&&\cn{1}{}&\cn{}{}&\cn{2}{}&\cn{}{}&\cn{1}{}\\
&&&\cn{1}{}&\cn{}{}&\cn{3}{}&\cn{}{}&\cn{3}{}&\cn{}{}&\cn{1}{}\\
&&\cn{1}{}&\cn{}{}&\cn{4}{}&\cn{}{}&\cn{6}{}&\cn{}{}&\cn{4}{}&\cn{}{}&\cn{1}{}\\
&\cn{1}{}&\cn{}{}&\cn{5}{}&\cn{}{}&\cn{1}{0}&\cn{}{}&\cn{1}{0}&\cn{}{}&\cn{5}{}&\cn{}{}&\cn{1}{}\\
\cn{1}{}&\cn{}{}&\cn{}{6}&\cn{}{}&\cn{1}{5}&\cn{}{}&\cn{2}{0}&\cn{}{}&\cn{1}{5}&\cn{}{}&\cn{}{6}&\cn{}{}&\cn{1}{}
\end{array}$$
---
[[cours_maths_expert]] [[équations polynomiales]]
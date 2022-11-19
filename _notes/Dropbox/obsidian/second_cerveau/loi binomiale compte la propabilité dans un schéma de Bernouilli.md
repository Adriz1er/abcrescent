---
matière:: maths
chapitre:: loi binomiale
---
#excalibrain
___
#spaced/maths 
Sachant que :![[Schéma de Bernoulli#^c9ac30]]Alors on a $n$ un entier naturel non nul et $p$ un réel de l’intervalle [0 ;1].  
On note $X$ la variable aléatoire comptant le nombre de succès obtenu lors dont $p$ est la probabilité du succès. 
On dit alors que $X$ suit la loi binomiale de paramètres $n$ et $p$, qui se note $\beta$ ($n$ ;$p$). 
On peut formaliser l'univers par {$0$ ; $1$}$^n$.

*Exemple* : Lancer une pièce est une [[épreuve de bernoulli]] avec pour succès d'obtenir "face" de probabilité de $\dfrac{1}{2}$. On répète cette expérience $n$ fois dans des conditions *identiques* et *indépendantes*. Donc $X$ la variable aléatoire donnant le nombre de "face" obtenu suit la loi binomiale de paramètres $n$ et $\dfrac{1}{2}$.

---
### nord:: [[Schéma de Bernoulli]]
### sud:: [[loi binomiale compte la propabilité dans un schéma de Bernouilli]]


Soient $k$ un entier naturel *inférieur ou égal* à $n$ et $X$ une variable aléatoire qui suit la [[loi binomiale compte la propabilité dans un schéma de Bernouilli]] de paramètres $n$ et $p$. Alors
$$P(X=k)= \binom n k p^k(1-p)^{n-k}$$
A noter que : ![[binome en écriture factorielle#^7c7830]]
## Pour numworks
$binompdf(k,n,p)$

---
### Nord ::
### Sud:: [[Représentation graphique de la loi binomiale]]
### Ouest ::
### Est ::

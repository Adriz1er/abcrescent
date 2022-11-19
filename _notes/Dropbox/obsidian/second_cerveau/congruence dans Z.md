---
matière:: maths_expertes
chapitre:: Divisibilité et conguence
---
#excalibrain 
___
Sachant $n \in N^*$, $a\in Z$ et $b\in Z$ $a$ et $b$ sont **congrus module $n$** lorsque $a-b$ est divisible par $n$. On note $$a≡b$$
	Exemples :
	$21≡6[5]$ car $21-6 \textit{ divisible par }5$
## Propriété
$$a≡b[n]\iff\textit{a et b ont le même reste par division euclidienne par n}$$
### Démonstration
$a=qn+r$ avec $0 \le r < n$
$b=q'n+r'$ avec $0\le r' < n$
On suppose que $a-b$ divisible par $n$ "->"
	$a-b=(qn+r)-(q'n+r')$$=n(q-q')+(r-r')$$\iff r-r'=(a-b)-n(q-q')$
	donc $r-r'=(a-b)-n(q-q')$
	donc $r-r'$ divisible par $n$
	$-n<-r'\le0$
	$0\le r< n$
	$-n\le r-r'<n$
On suppose que $r=r'$
	$a-b=qn+r-(q'n+r)=qn+q'n=n(q-q')$
	donc divisible par $n$ ($a≡b[n]$)

---
### nord:: [[division euclidienne]]
### sud:: 
### ouest:: 
### est:: 
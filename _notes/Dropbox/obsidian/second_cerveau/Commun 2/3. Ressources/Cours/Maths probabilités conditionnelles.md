[[cours proba seconde.jpg]] 
- [[Maths_p.330-331.png]]
- [[Maths_p.332-333.png]]
- [[Maths_p.334-335.png]]
- [[Maths_p.336-337.png]]
# Chapitre 5 : Probabilités conditionnelles
A et B sont deux évènements non vides
## 1. Définitions et propriétés
### Définition
On appelle **probabilité de A sachant B** le réel, noté $p_B(A)$ qui représente la probabilité que l'évènement A si on sait que l'évènement B est déjà réalisé.
De même on note *$p_A(B)$* la probabilité de B sachant A
#### Remarque
On a : 
$$
A \cap B = B \cap A 
$$
### Propriété 
$p(A) * p_A(B) = p(A \cap B) = p(B \cap A) = p(B) * p_B(A)$
### Propriétés 
1. $0 \le p_A(B) \le 1$
2. $p_A(\overline B) = 1 - p_A(B)$
3. $p_A (A) = 1$
4. $p_A(B) = 0$
#### Exemple :
- On tire au hasard deux cartes successivement  et sans remise dans un jeu de 32 cartes.
	A : "la 1ère carte tirée est un coeur"
	B : "la 2ème carte tirée est un coeur"
[[Arbre pondéré.jpg]]
## 2. Indépendances et probabilités totales
### A. Indépendances 
#### Définition
On dit que A et B sont indépendants quand :
$$ p(A\cap B)=p(A) \times p(B)$$
autrement dit :
 $$p_A(B)=p(B)$$
$$p_B(A)=P(A)$$
Cela signifie que la probabilité de B ne change pas, que l'on sache si A est réalisé ou pas.
#### Propriété
Si $A$ et $B$ sont indépendants alors  $A$ et $\overline B$ le sont aussi
### Probabilités totales 
#### Propriété 
**Si** $A_1$, $A_2$,....., $A_n$ forment une partition de l'univers ; c'est à dire qu'elle n'ont pas de solutions communes. 
**Donc** : 
	- pour tout $i \ne j$ : $A_i \cap A_j =$ [0 barré]
	- $A_1 \cap A_2 \cap A_3 \cap ... \cap A_n = \Omega$

==**Alors** $$p(B)=p(B\cap A_1) + p(B\cap A_2) + ... + p (B\cap A_n)$$==
#### Remarques
- On retrouve pourquoi nous avions le droit d'additionner la probabilité des branches d'un arbre.
- [Schéma] où $A$ et $\overline A$ forment une partition de l'univers.
	*$p(B) = p(B \cap A)+ p(B \cap \overline A)$
- On a : $B=(A \cup B)$


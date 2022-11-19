---
cards-deck: cours::maths
---

#🌱/cours [[Cours_maths]] 

---
Le raisonnement par **récurrence** consiste à *démontrer* que les deux preuves de récurrence sont vraies :
^1662410236644
- {**preuve initiale**} : sur un entier (généralement sur 0 ou 1)
^1662410236651
- **preuve héréditaire** **vérifiée** sur {l'entier $n+1$}
Le raisonnement par récurrence cherche à démontrer un résultat pour {*tout* $n$}, dans une partie {de $I$ (à partir de certain rang jusqu'à $+\inf$)}.
^1663218668569
# Méthode raisonnement par récurrence
1. {*donner un* ***nom***} à la **propriété**
^1662557791907
2. **preuve initiale** : *vérification* {qu'on **puisse** ***commencer***}, en *vérifiant* {que $P_0$ est vrai}.
^1662611635626
3. **preuve héréditaire** : 
	1. ***faire une hypothèse*** de ce qu'il faut {**démontrer**} (⚠️{*si besoin* mettre le français en mathématique)}, 
^1662611635631
		1. on *énonce* la propriété ($P_k$) ==considéré comme vérifié==, et on *écrit* ce que ça ==**implique** ($P_k$ :"$...$")==.
^1663218831355

		2. on *énonce* ce que l'on *veut **démontrer*** ($P_{k+1}$), et ce que ça **impliquerai** ($P_{k+1}$ : "$...$")
^1663512712896

			⚠️ à noter que : si il y a une *lettre paramétrable* cela *implique* {qu'elle n'aura pas la même *valeur*}.
^1663218941134
==démontrer== que si ($P_k$) serait *vrai* alors ($P_k+1$) sera *vrai aussi*, pour cela il faut ==**utiliser le fait que ($P_k$) est considéré comme vrai==** pour ==***prouver*** *l'hypothèse de récurrence*==.

^1663218995287
		⚠️ *à chaque nouveau calcul* ==il faut utiliser ***or***==
^1663044827880
1. **conclusion** : 
	1. sachant que la propriété {est prouvée ***initialement*** et ***héréditairement***}, d'après {le *principe de récurrence*} la propriété {est *vraie*}.
^1662611635644
		 ⚠️ *à **noter** que : {c'est* pour **tout** $n\in N$}
^1662611635649
	2. {*reprise* de l'**énoncé de départ**.}
^1662611635653

## Exemples :

Démontrer que (soit $n \in N$),
	$$
	1+...+n=\dfrac{n(n+1)}{2}
	$$

**on doit nommer la fonction à démontrer**, soit $$P_n : 1+2+...+n=\dfrac{n(n+1)}{2}$$
	On commence alors l'
	 - [ ] initialisation
	: On vérifie que $P_n$ est *vraie* première valeur possible de $n$, **ici** n=0.$$P_0 = \dfrac{0(0+1)}{2}$$ soit$$0=0$$ donc $P_0$ est vraie.
		- Exemple : $P_4$ est-elle vraie ?$$P_4=1+2+3+4=\dfrac{4\times(4+1)}{2}$$comme$$1+2+3+4=10$$ et que $$\dfrac{4(4+1)}{2}=\dfrac{4\times5}{2}=10$$
		donc $P_4$ est *vraie*.

- Exemple :
	Soit $k$ un entier quelconque, supposons que $P_k$ *vraie* et **démontrons** que $P_{k+1}$ l'est aussi. Sachant que$$P_k=1+...+k=\dfrac{k(k+1)}{2}$$ et que :$$P_{k+1}=1+...+k+(k+1)=\dfrac{(k+1)(k+1+1)}{2}$$On remarque qu'on a le même début soit "$1+...+k$" donc on peut ***reprendre le calcul précédent*** pour *ajouter* "$k+1$", on a : $$\dfrac{k(k+1)}{2}+k+1$$soit$$(k+1)(\dfrac{k}{2}+1)$$qu'on essaye de *ramener* à ce qu'on avait trouvé quand on avait simplement appliqué la *formule* pour $P_{k+1}$ $$=(k+1)(\dfrac{k+2}{2})$$$$=\dfrac{(k+1)(k+2)}{2}$$donc $P_{k+1}$ est *vraie*.
	La propriété est {**initialisée**} et {**héréditaire**}, d'après le [[raisonnement par récurrence]], elle est *vraie* pour *tout* $n\in N$.
^1662484740912

---
# Références
- cours lycée
- [Raisonnement par récurrence — Wikipédia](https://fr.wikipedia.org/wiki/Raisonnement_par_r%C3%A9currence)

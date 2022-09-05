#🌱/📝/cours  [[Cours_maths]] 

---
- bla
	- Exemple :
	Soit $k$ un entier quelconque, supposons que $P_k$ *vraie* et **démontrons** que $P_{k+1}$ l'est aussi. Sachant que$$P_k=1+...+k=\dfrac{k(k+1)}{2}$$ et que :$$P_{k+1}=1+...+k+(k+1)=\dfrac{(k+1)(k+1+1)}{2}$$On remarque qu'on a le même début soit "$1+...+k$" donc on peut ==reprendre le calcul précédent== pour ***ajouter*** "$k+1$", on a : $$\dfrac{k(k+1)}{2}+k+1$$soit$$(k+1)(\dfrac{k}{2}+1)$$qu'on essaye de *ramener* à ce qu'on avait trouvé quand on avait simplement appliqué la *formule* pour $P_{k+1}$ $$=(k+1)(\dfrac{k+2}{2})$$$$=\dfrac{(k+1)(k+2)}{2}$$donc $P_{k+1}$ est *vraie*.
	La propriété est 
	- [ ] initialisée
	et **héréditaire**, d'après le [[raisonnement par récurrence]], elle est *vraie* pour *tout* $n\in N$.
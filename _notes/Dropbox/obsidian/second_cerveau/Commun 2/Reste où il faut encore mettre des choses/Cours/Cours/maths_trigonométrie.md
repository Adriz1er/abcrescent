[[cours 2nd trigo.jpg]]
# I. Le cercle trigonométrique
[[cours-trigonométrie-fig1.png]]
## Définition
Le cercle trigonométrique est le cercle de rayon 1 au point de coordonnées (0 ; 0), orienté dans le sens direct = ==sens positif==.
### Par proportionnalité on obtient le tableau suivant
angle en radian|angle en degrés
--|--
$-\pi$ | -180
$\frac {-\pi} {2}$ | -90
0|0
$\frac {\pi} {6}$|30
$\frac {\pi} {4}$|45
$\frac {\pi} {3}$|60
$\frac {\pi} {2}$|90
$\pi$|180
$2\pi$|360
## Propriété
La mesure d'un angle en radian est identique si l'on rajoute où l'on enlève $2\pi$. On peut dire que si $x$ est la mesure d'un angle en radian, alors $x+(2\pi)*k$ où $k \in Z$ est une aussi une mesure du même angle.
### Exemple
$-\frac {\pi} {4}$ est une mesure de l'angle orienté -45° ; mais :
- $-\frac {\pi} {4} -2 \pi = \frac {-9\pi} {4}$ aussi
- $\frac {-\pi} {4} -4\pi = \frac {-17\pi} {4}$ aussi
- $\frac {-\pi} {4} +2\pi = \frac {7\pi} {4}$ aussi
- $\frac {-\pi} {4} + {4\pi} = \frac {15\pi} {4}$ aussi
## Propriété : Mesure principale d'un angle
Parmi toutes les mesures en radian d'un angle, il existe une unique mesure dans $]-\pi$ ; $\pi]$. Elle est appelée mesure principale. [[trouver mesure principale d'un angle]]
### Exemple
Donner la mesure principale de $\frac {-17\pi} {6}$
$$2\pi = \frac {2\pi * 6} {6} = \frac {12\pi} {6}$$
$$\frac {-17\pi} {6} + \frac {12\pi} {6} = \frac {-5*\pi} {6} \in ]-\pi ; \pi[$$
[[exemple écriture radian.jpg]]
# II. Cosinus et Sinus d'un angle
## Définition
Soit un point orthonormé (O, I, J), et *C* le cercle géométrique de centre $O$
Notons $M$ le point associé à la mesure $x$ :
[[sinus et cosinus sur un cercle.png]]
- On appelle *cosinus* de $x$ (noté : $cos(x)$), l'==abscisse== de point $M$.
- On appelle *sinus* de $x$ (noté : $sin(x)$), l'==ordonnée== du point $M$.
### Valeurs particulières
$x$|0| $\frac {\pi} {6}$| $\frac {\pi} {4}$|$\frac {\pi} {3}$| $\frac {\pi} {2}$|$\pi$|$2\pi$
--|--|--|--|--|--|--|--
$cos(x)$|1|$\frac {\sqrt {3}} {2}$|$\frac {\sqrt{2}} {2}$|$\frac {1} {2}$|0|-1|1
$sin(x)$|0|$\frac {1} {2}$|$\frac {\sqrt{2}} {2}$|$\frac {\sqrt {3}} {2}$|1|0|0
#### Propriétés
1) $-1 ≤ sin (x) ≤ 1$ et $-1 ≤ cos (x) ≤ 1$
2) $cos²(x) + sin²(x) = 1$
4) $cos (x) = cos(x + 2k\pi)$ où $k$ *entier relatif*
5) $sin (x) = sin(x + 2k\pi)$ où $k$ *entier relatif*
##### Exemple
- Sachant qu'on a $\frac {19} {3} = \frac {\pi} {3} \times [2\pi]$
$$cos(\frac {19\pi} {3}) = cos (\frac {\pi} {3} + 3 \times \frac {6\pi} {3})= cos (\frac {\pi} {3}) = \frac {1} {2}$$

[[exemple 2 propriété cos, sin.jpg]]
### Propriétés à voir sur le cercle trigonométrique
1. $sin(-x) = - sin (x)$
2. $cos(-x) = cos (x)$
	1. $sin(\pi - x) = sin(x)$
	2. $cos(\pi - x) = - cos (x)$
		1. $cos (x+\pi) = -cos(x)$
		2. $sin(x+\pi)=-sin(x)$
			1. $\cos \left(\dfrac{\pi}{2} – x \right) = \sin(x)$
			2. $\sin\left(\dfrac{\pi}{2}-x \right) = \cos(x)$
				1. $\cos \left(\dfrac{\pi}{2} + x \right) = -\sin(x)$
				2. $\sin \left(\dfrac{\pi}{2} + x \right) = \cos(x)$

[[cercle trigo valeurs.png]]
![[cercle trigo 2.png]]
#### Applications
[[application sinus et cosinus.jpg]]
[[application sinus et cosinus 2.jpg]]

### Parité
- fonction paire : $cos(-x) = cos (x)$
- fonction impaire : $sin(-x) = -sin(x)$
#### Exemple parité [...]
- $(-x)=-(x)$
- $-(x)²=x²$
- $(-x)^3=-x^3$
# III. Résoudre des équations de la forme de 
## $sin(x)=sin(a)$ ou $cos(x)=cos(a)$ **où** $a,x \in \R$ 
## Propriétés
Soient $a,x \in \R$
a. cos(x)=cos(a)
<->   $x=-a+2k\pi$ où $k\in\Z$
		$x=a[2\pi]$
	==ou==
		$x=-a+2k\pi$ où $k\in \Z$
		$x=-a[2\pi]$
b. Soient $a,x \in \R$
<->   $x=a+2k\pi$ où $k \in \Z$
		$x=a[2\pi]$
	==ou==
		$x=\pi-a+2k\pi$ où$k\in\Z$
		$x=\pi-a[2\pi]$
### Applications
[photos]
## Point Méthode
1. Se ramener à $cos(x)=cos(a)$ ou $sin(x)=sin(a)$
2. Connaître le tableau
3. ==Attention== Vérifier l'intervalle demandé pour les solutions
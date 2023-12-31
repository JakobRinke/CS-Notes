- Eine Funktion aus $\mathbb{R}$ in $\mathbb{R}$ ist eindeutig bestimmt durch 2 Dinge
(A1) Angabe einer Menge $D \subseteq \mathbb{R}$ (Definitionsbereich von $f$)
(A2) eindeutige Vorschrift die jedem $x \in D$ genau ein Element $y=f(x)$ aus $\mathbb{R}$ zuordnet aus $\mathbb{R}$

#### Schreibweise
$x \in D \mapsto y=f(x)$            $f:D\rightarrow \mathbb{R}$

##### Mengenprodukt
$m = (mi)_{i\in A}; m:= ...$ aus $Wertebereich$
bzw. m= { i, m: i $\in$ A}
Def: $prod(i\in I) Ai: := \{f: I -> \cup A: f(i)\in A_i; \forall i \in I\}$

**Sind alle A gleich, etwa gleich A, so erhält man:**
$prod(i\in I)A_i = \{f: I->\cup A: f(i) \in A_i; \forall i \in I\}$ 
$prod(i\in I)A_i = \{f: I->\cup A: f(i) \in A; \forall i \in I\}$ 
 -> ist die Menge aller Funktionen von I nach A
 $A^I = prod(i\in I)A$ 
 $R^R =$ Menge alle Funktionen von R nach R  
#### Sprechweisen
$x$ - Argument von $f$, anhängige Variable
$y$ - Abhängige Variable
$f(x)$ - Funktionswerte von $f$ an der Stelle $x=a$; Bild von $f$ and $x=a$

##### Funktionsgraph von $f$
- $\Gamma_f \{(x;y) | x \in D; y=f(x)\}$ = ${x, f(x) }

```functionplot
---
title: Funktionsgraph von F
xLabel: x
yLabel: y
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x) = x
```
##### Wertebereich von $f$ 
$W=\{f(x)|x \in D\}$

##### Nullstelle von $f$
Argument $x$ aus $D$ mit der Eigenschaft $f(x)=0$


#### Beispiele für Funktionen
- [[Identische Abbildung]]
- [[Floor Funktion]]
- [[Ceil Funktion]]
- [[Betragsfunktion]]
- [[Polynomabbildungen]]


#### Operationen mit Funktionen
- Funktionen können miteinander Addiert, Subtrahiert und Multipliziert Werden - [[Arithmetische Operationen für Funktionen ]]
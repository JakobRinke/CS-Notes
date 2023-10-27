

#### Cantor
- Eine Menge ist eine Zusammenfassung bestimmter wohlunterschiedener Objekte unserer Anschauung oder unseres Denkens
- Von jedem Objekt steht fest ob es zu Menge gehört oder nicht
- Reihenfolge und Häufigkeit irrelevant 
- {1,2,3,4} Menge der ganzen Zahlen von 1 bis 4
#### Problem der naiven Mengenlehre
- Wunsch 1: $x \in y$ soll eine y [[Aussageform]] über ein Universum aller Mengen sein sein
	- Für 2 Mengen x, y git $x \in y$ oder $x \notin y$ 
- Wunsch 2: Aussonderung mittels einstelliger [[Aussageform]] 
	- Ist p(x) eine [[Aussageform]] in der Variable x über dem Universum aller Mengen dann soll es eine Menge geben, die aus genau denjenigen Mengen x besteht, für die p(x) war is

 **Problem**
 $p(x):= \lnot (x\in x) = x\notin y$ 
 Wegen Wunsch 2 gibt es eine Menge M die aus allen Mengen x besteht für die das $p(x)$ wahr ist
 *Russels Frage*: $M \in M$ ?
 - Wäre M $\in$ M, so wäre M eine Menge $x \notin x$ , $M \notin M$
 - Wäre $M \notin M$ so wäre M eine Menge x mit $x \notin x$, d. h. $M \in M$
 - Wunsch1 uns Wunsch2 führen zu Widerspruch 

#### Korrektur
- Aussonderung nur aus einer bereits gesicherten Menge
- Nicht mehr aus dem Universum alle Mengen
- Wunsch 2‘: Ist A eine Menge und p(x) eine [[Aussageform]] über dem Universum aller Mengen, Dann gibt es eine Menge B die aus denjenigen Mengen besteht, die zu A gehören, die das p(x) erfüllen.
- Die Gesamtheit aller Mengen die das Prädikat p(x) erfüllen wird ebenfalls mit {x: p(x)} notiert, ist aber keine Menge, sie heißt *Klasse* und *Echte Klasse, wenn sie keine Menge ist*
- Für p(x) = $x \in x \lor x \notin x$ erhält man die echte Klasse alle Mengen

##### Wunsch 3
- Zwei Mengen sind Gleich, wenn sie die selben Elemente enthalten 
- $A=B \iff \forall x (x \in A \iff x \in B)$  
- Somit gilt für 2 Prädikate p(x), q(x) und eine Menge M
- ${x \in M: p(x)} = {x\in M: q(x)}$ *genau dann wenn* $p(x) \iff q(x)$

##### Wunsch0
 **Wie kommt man überhaupt zu Mengen, wie zu „größeren“**
- Es gibt eine Menge
- Folgerung: Es gibt eine Menge, die keine andere Menge als Element enthält, leere Menge; $\emptyset$ 

##### Wunsch 4
Zu jeder Menge $A$ gibt es eine Menge die aus genau denjenigen Mengen besteht, die Teilmenge von $A$ sind
Potenzmenge von a: $\mathfrak{P}(A) \equiv \mathfrak{p}(A) \equiv 2^A$ enthält alle Teilmengen
$\mathfrak{P}(\emptyset) = \{\emptyset\}$
$\mathfrak{P}(\{\emptyset\}) = \{ \emptyset, \{\emptyset\} \}$

##### Wunsch 5
Zu jeder Menge nichtleeren Menge A von Mengen gibt es eine Menge, die aus genau denjenigen Mengen besteht, die zu jeder Menge aus A Angehören. 

Wunsch 5
Zu jeder Menge nichtleeren Menge A von Mengen gibt es eine Menge, die aus genau denjenigen Mengen besteht, die zu wenigstens einer Menge aus AAngehören. 
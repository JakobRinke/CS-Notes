
(x, y) = {{x}, {x, y}} für Mengen x, y


Man findet (x, y) = ( x‘, y‘) <-> x = x‘ und y=y‘

Für zwei Mengen A,B sei $A x B := \{(x,y): x \in A \land y \in B\}$


(x, y) = {{x}, {x, y}} $\subseteq$ P(A $\cup$ B)       also     (x, y) = P(P($A \cup B$))

***Eine Relation R von A nach B ist eine Teilmege von A x B***

#### Unkehrrelation
Ist $R \subseteq A x B$  so ist $R^{-1} = \{(y, x)  (x, y) \in R \} \subseteq  BxA$ 
Im Fall A=B,     $R \subseteq AxA$ heißt relation auf A

**Abkürzung xRy    statt    (x, y) $\in R$**
#### Relationen der Menge A
$\emptyset \subseteq A xB$
2. Allrelation: AxA $\subseteq$ AxA
3. Gleichrelation: R:={(x, x): x $\in$ A} $\subseteq$ AxA        „=„ statt R
	- Auch Identität auf A $id_A$ 
4. A Menge von Zahlen ; R:= {(x, y): x, y $\in$ A; x höchstens so groß wie y}
	schreibe <= statt R
5. A Sind die Ecken eines Netzwerks: R := {(x, y) $\in$ AxA: Es gibt eine direkte Verbindung von x nach y }


### Äquivalenzrelation
Eine Äquivalenzrelation auf A ist eine Reflexive symetrische transitive Relation auf 

C $\in P(A)$ ist eine Partition von A wenn gilt:
	- UC = A
	- $\emptyset \notin C$ 
	- $\forall$ X,Y $\in$ C ist X, Y oder $X \cap Y = \emptyset$ 
Die Elemente einer Partition heißen Teile oder auch Klassen


Satz: Sei ~ eine Äquivalenzrelation auf A 
Für $x \in A$ setze $[x]_{\~} := \{y\in A, x~y\}$
	$[x]$ heißt Äquivalenzklasse von x	
Die Menge $C_N := \{[x]_\~; x \in A\}$ 

Satz: Sei C eine Partition von A. Dann ist durch x~y mit x, y Ganze Zahlen eine Äquivalenzrelation auf A definiert 


### Ordnungen
- Reflexiv, Tranisitiv, Antisymmetrisch
- <= ist Ordnung auf X
A $\subseteq X$ ; $b \in A$
b minimal in A $\iff$ $b \in A$ und $(c <= b \implies c=b) \forall c \in A$ 
b maximal in A $\iff$ $b \in A$ und $(b <= c) \implies c=b) \forall c \in A$ 
b kleinstes Element in A $\iff$ $b\in A$ und b<=c   $\forall c \in A$     -> *Einmalig*
b größtes Element in A $\iff$ $b \in A$ und c<=b    $\forall c \in A$     -> *Einmalig*
b untere Schranke in A $\iff$ b <= c $\forall c \in A$
b obere Schranke in A $\iff$ c <= b $\forall c \in A$

Kleinste Obere Schranke: b Obere Schranke und b kleinstes Element aller oberen Schranke       -> b ist supremum (sup A)

Größte Untere Schranke: b Untere Schranke und b größtes Element aller unteren Schranke       -> b ist Infimum A (inf A)


#### Satz
$\subseteq$ ist eine Ordnung von P(X) für a $\subseteq$ P(X)
	- sup a = $\cup a$ ; 
	- inf a = $\cap a$ 

### Ordnungen in Hasse Diagrammen
- Regel1: Ist *x <= y* so zeichne *x unterhalb von y*
- Regel2: *Verbinde zwei verschiedene Punkte* durch eine Stracke von x nach y falls *x<= y* gilt und es *kein z gibt mit x<=z<=y*

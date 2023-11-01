
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


Eine Äquivalenzrelation
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
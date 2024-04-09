
Eine Operation auf einer Menge A ist eine Funktion vom AxA nach A
f: AxA->A
Schreibweise: z=f(x,y)
Schreibweise: z=xfy

**Eine Menge G mit einer Operation # auf G heißt Gruppe, falls Folgende Aussagen gelten**
	1. a#(b#c) = (a#b)#c   für alle a,b,c    (# ist assoziativ)
	2. Es gibt eine e in G, a#e = a    und  e#a = a    für alle a
	3. Sei e das Element aus 2. das sogenannte neutrale Element dann gilt
		1. zu jedem a gibt es ein b: a#b=e

### Kommutative / abelische Gruppen
- Eine Gruppe heißt kommutativ / abelsch wenn man die Argumente der Gruppe tauschen kann;    a* b = b * a
#### Satz
Sei A Menge und SA die menge alle Bijektionen von A nach A, dann ist (SA, * ) eine Gruppe
- Das neutrale Element in SA ist die Identität
- Das inverse Element zu alpha ist die Umkehrabbildung

##### Zyklenschreibweise Permutationen
Für paarweise verschiedene $a_1, …, a_l \in A$ bezeichnet $\alpha :=(a_1,a_2, …, a_l)$ die Permutation  $\alpha: A-> A$ mit
$$\alpha(x) = \{a_{i+1} falls x=a; für i \in (1…,l-1);; a_1 \iff x=a_l;; x, sonst\}$$

Jede Permutation der obigen Form heißt Zyklus der Länge l

Jede Permutation eine Endlichen Menge läßt sich als Verkopplung von elementfremden Zyklen darstellen


$|S_A|$ wächst schnell mit |A|, es ist n!


### Gruppen transformieren
#### Produktgruppen
Sei (Gi, @i) eine Gruppe eine Familie von Gruppen
Sei produkt(i in I; Gi )  =     { f: f: I -> UGi,   f(i) in Gif. a. i in I  }

Für f,g in G definieren
f * g in G durch (f *  g)(i)  =  f(i) @i    g(i)         f. a. i in I

Dann ist (G, @) eine Gruppe

Das Neutrale Element vor (GI, @i)  wird als 1 bezeichnet, so wird durch 1(i):=1 f. a. i in I definiert
Für f in G sei g in G definiert durch g(i)=(f(i))$^{-1}$ 


#### Untergruppen
Sei (G, @) eine Gruppe und U eine Teilmenge von G.
(U, @) ist eine Untergruppe von (G, @) wenn gilt:
![[Pasted image 20231128093259.png]]


Schreibweise:
< S > statt 
$\cap\{H\le G: S \subseteq H\}$
Es ist die kleinste Gruppe mit allen Elementen von S


#### Homorphismen
Seien (G, $\#_g$) und (H $\#_h$) Gruppen
Die Abbildung f: G-> H heißt Homorphismus falls gilt
1. f(a $\#_g$ b)   = f(a)   $\#_h$    f(b)
2. $f(G_0) = H_0$
3. $f(e^{-1}) = f(e)^{-1}$

Satz:
1. f(G) = { f(x): x in G} <= H
3. f surjektiv <-> f(G) = H
4. Kern f := { x in G: f(x)=1h} <= G
5. f injektiv wenn <-> Kern f = {1g}

Ein Homorphismus heißt Isomorphismus wenn er Bijektiv ist
(G, @g) ~= (H, @h)

#### Satz 
- Jede Gruppe (G, @) ist Isomorph zu einer Untergruppe einer Permutationsgruppe (SG, * )

### Natürliche Zahlen
- +: NxN -> N
- m+0 := m
- $m+n^+$ =$(m+n)^+$

- * : NxN -> N
- m * 0 := 0
- $m * n^+ := m*n + m$ 

### Ringe
Ein Ring (R, +, * )  besteht aus einer menge und zwei Operationen mit folgenden Eigenschaften
1. (R, + ) ist Gruppe
2. *  ist Assoziativ, (Manchmal Kommutativ)
3. a * (b + c)  =  (a * b) +  (a * c)
4. (b + c)  * a =  (a * b) +  (a * c)
*R heißt ein Ring mit 1 != 0 falls außerdem gilt*
	5. Es gibt ein Element 1 in R \ {0}   mit 1 * a = a und a * 1
*R heißt Kommutativ falls außerdem gilt*
	6. a * b = b * a    für jedes a!=0


### Körper
Ein Ring heißt Körper falls gilt
7. Z. j.   a in R \ {0}  existiert   b in R   mit   a * b = 1   und b * a = 1 

**Zu jedem Ring gilt: a mal 0  = 0    **


#### Satz
Ring der kommutativ aber kein Körper ist gegeben
Z_m = {r mod m für r in Z} 

+:   Z_m x Z_m -> Z_m,  a mod m + b mod m = (a + b) mod m

 m Primzahl <-> Z_m Körper


#### Satz
Durch (a, b) ~ (c, d)  <-> a * d = b * c werden die Rationalen Zahlen definiert
-> Äquivalenzzahlen sind die Klassen
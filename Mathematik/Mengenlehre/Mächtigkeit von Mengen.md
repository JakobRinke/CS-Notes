
- Zwei Mengen A, B heißen *gleichmächtig*, falls es eine *Bijektion* von A -> B gibt
- Es gilt:
	- A ~= A                                    (Reflexiv)
	- A~=B $\land$  B~=C -> A~=C        (Transitiv)
	- A~=B $\iff$ B~=A                  (Symmetrisch)

*A heißt höchstens so mächtig wie B, falls es eine Injektion f: A->B gibt*
$\equiv$ A ist gleichmächtig zu einer Teilmenge von B
Schreibweise: A verschnörkeltes Kleinerzeichen B
- Diese Abbildung ist:
	- Reflexiv
	- Transitiv
- Quasiordnung nach Menge
	-> Ist auch antisymmetrisch, denn es gilt folgender Satz:
		- Für 2 Mengen gilt: A höchstens so mächtig wie B und B höchstens so Mächtig wie A, dann sind A und B gleichmächtig


**Satz**
Auswahlaxiom: Zu jeder Familie Ai von Mengen existiert eine Funktion f->I=UA mit f(i) $\in$ A

Wohlordnungssatz: Zu jeder Menge M existiert eine Wohlordnung von M, d. h. eine totale Ordnung, in der jede nichtleere Teilmenge X $\subseteq$ M ein kleinstes Element hat

Lemma von Zorn: Besitzt in einer durch <= geordneten nichtleeren Menge M jede Kette eine Obere Schranke, so besitzt M ein maximales Element

Für Zwei Menge A B ist eine Entweder Mächtiger als die Andere, oder sie sind Gleichmächtig


#### Dedekindmächtigkeit
Eine Menge heißt Dedekindunendlich, falls sie gleichmächtig zu einer echten Teilmenge B von A ist, $B \subset A$


#### Natürliche Zahlen
$A^+ = A \cup \{A\}$ 
0 = {}
1 = {0} = {{}}
2 = {0, 1} = {{}, {{}}}
...
### Induktivität
- Eine Menge N heißt Induktiv wenn:
	- {} in M und n* in M für alle n in M
*Daher ist auch $\mathbb{N} \cup \{N\subseteq M_ N$ induktiv}, für beliebiges induktives M*
Ist M eine Induktive Menge so ist M'=M $\cup M$ auch Induktiv

### Satz der Vollständigen Induktion
Sei p(n) ein Prädikat natürlicher Zahlen, ist p(0) wahr und p($n^+$) wahr, dann ist das Prädikat war für jedes n aus N

#### Satz 
1. Für m,n = Natürliche Zahlen gilt: $m \in  n \iff m \subset n$ 
2. $\subseteq$ ist eine Totalordnung auf $\mathbb{N}$

#### Satz
Jede Teilmenge von $N$ hat ein kleinstes Element

#### Satz Vollständige Induktion II
Sei p(n) Prädikat einer Natürlichen Zahl
Für jedes n in N impliziert die Wahrheit von p(x) f. a. x\<n
die Wahrheit p(n)
Dann ist p(n) wahr für alle n $\in$ N


Sei $a_n, b_n, c_n$ Folgen über $\mathbb{R}$ $a,b,c \in \mathbb{R} U {\infty, -\infty}$ 
1. $a_n$ -> a, $b_n = a_n$ *—>* $b_n$ -> a
2. Jede Teilfolge $b_n$ von $a_n$ hat den selben Grenzwert wie $a_n$
	1. Wenn 2 Teilfolgen von einer Folge unterschiedliche Grenzwerte haben, ist die Folge selbst divergent
3. Grenzwertübergang:
	1. besitzen $b_n, c_n$ Grenzwerte so gilt:
	2. $\forall n\ge n_0: b_n \le c_n$ => $lim(b_n) \le lim(c_n)$
	3. sowie: $\forall n\ge n_0: b_n \le a_n \le c_n, lim(b_n) = lim(c_n) = g$ => $lim(a_n) \le g$
4. Fehlerfolge
	- $a_n -> g$ <=> $f_n = |a_n - g| -> 0$
	- A geht gegen g, wenn der Fehler von a bis g gegen null geht
1. Nullfolge / Kehrwert
	- $a_n$ -> 0, $a_n$ > 0=> $1/a_n -> \infty$ 
	- $a_n$ -> 0, $a_n$ < 0=> $1/a_n -> -\infty$ 


#### 6. Rechnen mit Grenzwerten
1. Gilt $a_n -> a; b_n->g$ gelten folgende aussagen

| -     | a reel, b reel     | a unendl, b reel            | a reel b unendl             | beide unendl |
| ----- | ------------------ | --------------------------- | --------------------------- | ------------ |
| an+bn | a+b                | unendl                      | unendl                      | unendl       |
| an-bn | a-b                | unendl                      | -unendl                     | ?            |
| anxbn | axb                | unendl mit vorzeichen von b | unendl mit vorzeichen von a | unendl       |
| an/bn | a/b wenn b nicht 0 | unendl mit vorzeichen von b | 0   wenn a nicht 0          | ?            |
| an^bn      |      a^b, außer a,b=0              |         undendlich oder 0 je nach Vorzeichen                    |          Unendl wenn a>1 und 0 wenn 0<a<=1                  |       unendlich       |

- Unbestimmte Ausdrücke:
	- $\infty - \infty$
	- $0 * \infty$
	- $0/0$
	- $\infty/\infty$
	- $0^0$
	- $\infty^0$
	- $1^\infty$

7. Grenzwerte von Wurzeln
	- Sei $a_n$ eine Folge $a_n \ge 0 \forall n \ge 1$
	- Ist $lim \frac{(a_n+1)}{a_n}= q$   dann ist    $lim \sqrt[n]{a_n}$ = q

8. e folge
	- $x_n$ Folge geht gegen Unendlich
	- $(1+(1/x_n))^{x_n} \rightarrow e$ 
= Beschränkung nach oben
### Große-O-Notation
Für eine Folge f:N definiert man die Klasse O(f)
$O(f):= {g:N->R| \exists c \in \mathbb{R}}  \exists n_0 \forall n \ge n_0: |g(n)| \leq c *|f(n)|$ 
- g kann durch ein Vielfaches c von f begrenzt werden

*Bemerkung:* 
Richtig: $g \in O(f)$
Benutzung: $g(n) = O(f(n))$ 
g von n ist Groß O von f von n

#### Kriterium
1. ist der $lim_{n->\infty}\frac{f(n)}{g(n)} = g \in R$ so gilt $g(n) = O(f(n))$
2. Ansonsten nicht


### Rechenregeln
1. Addition 
	- $g_1(n) = O(f_1(n))$
	- $g_2(n) = O(f_2(n))$
	- $g_1(n) * g_2(n) = O(f_1(n) * f_2(n))$
	- $g_1(n) + g_2(n) = O(f_1(n) + f_2(n)) = O(max(f_1(n),  f_2(n)))$
2. $c * f(n) = O(f(n))$
3. $h(n) = O(g(n)), g(n)=O(f(n)) \implies h(n) = O(f(n))$
4. $g(n) = O(f(n)) \iff O(g(n)) \subseteq O(f(n))$ 


### Weitere Landau Symbole
$\Omega(f)= {g: N->R | f \in O(g) }$ 
$\theta(f) = O(f) \cap \Omega(f)$ 
$o(f) = \{g: N->R| gegen O\}$
$\omega(f) = \{g: N->R| f = o(g)\}$
$g ~ f \iff g(n)/f(n)=1$

#### Regeln
- g(n) = o(n)  =>  g(n) = O(n)
- g(n) = $\omega$(n) =>   g(n) = $\Omega$(n)
- g(n) ~ f(n) => g(n) $\theta$(f(n))

#### Stirlings Formel
n! = ~ $\sqrt{2 * \pi *n} * (n/e)^n$ 

### Anwendung
a) Laufzeitanalyse
	T(n) von Algorithmen 
	T(n) := Anzahl der Elementarschritte des Algorithmus bei Eingabe eines Beispiels der Größe n
	T(n): Natürliche Zahlen -> Rationale Zahlen
b) Asymptotisches Verhalten von Folgen
	also Verhalten für n->unendlich


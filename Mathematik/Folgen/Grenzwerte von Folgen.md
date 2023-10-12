### Limesschreibweise
- Konvergenz von [[Folgen]]
- $lim_{n\rightarrow \infty} a_n = g$
- Limes (*Grenzwert*) von $a_n$ für n gegen unendlich ist g
- Folge ($a_n$) konvertiert gegen g für n gegen unendlich

#### Approximation einer Zahl
a) $x \in \mathbb{R}$ heißt $\epsilon$ Näherung von g falls 
$$abs(x-g) < \epsilon$$
- x-g ist absoluter Fehler der Näherung
- $\epsilon$ ist die Fehlerschranke

__Bsp__
$g = \sqrt{2} \approx 1.4142$
$x=\frac{17}{12}$
x-g ist keine Dezimalzeit
Obere Schranke:
$|x-g| < 0.003 = \epsilon$
$x \in (g-\epsilon, g+\epsilon) =: U_{\epsilon}(g)$

#### Definiton des Limes
$lim_{n->\infty}a_n = g$ 
Bedeutung: 
	- Für jede Fehlerschranke wird der Fehler kleiner
	- $a_n \in U(g)$
	- für fast alle $n \in \mathbb{N}$
	- (Alle bis auf Endlich viele Ausnahmen)
	- Es gibt einen Index N = $N_{\epsilon}$ so dass für alle $n > \epsilon$ gilt $|a_n - g| < \epsilon$ 
	- Ab N gilt die Näherung

**Def:** Folge($a_n$) Zahl $g \in \mathbb{R}$
$$lim_{n\rightarrow\infty}a_n = g \leftrightarrow \forall \epsilon > 0 \exists N=N(\epsilon)\in\mathbb{N} \forall n: n>N =>|a_n-g|>\epsilon $$
- *Egal wie nah man eine Innere Schranke setzt, ab einen gewissen Punkt wird der Abstand zwischen $a_n$ und $g$ kleiner, als diese Schranke*

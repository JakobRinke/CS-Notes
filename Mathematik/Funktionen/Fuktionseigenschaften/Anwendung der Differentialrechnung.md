
### 1. Grenzwertregel von l'Hospital
Betrachten Grenzwert der Form $lim_{x->x_0} f(x)/g(x)$ wobei
$lim f(x)$ = $lim g(x) = \infty$ oder  $lim f(x)$ = $lim g(x) = 0$
sind f und g ist der Umgebung von $x_0$ differenzierbar so gilt: 
$$lim \frac{f'(x)}{g'(x)} = a \implies lim \frac{f(x)}{g(x)} = a$$

### 2. Zwei Hauptsätze
#### Zwischenwertsatz
Ist f stetig auf dem Intervall [a, b] und gilt f(a) < c < f(b) oder f(a) > c > f(b) so hat die Gleichung f(x) = c mindestens eine Lösung x im Inneren des Intervalls [a, b]


#### Mittelwertsatz der Differentialrechnung
ist f stetig auf [a, b] und diffbar auf (a, b) so gibt es ein x in (a, b) mit
f'(x) = $\frac{f(b)-f(a)}{b-a}$ 

### 3. Monotonie
Vor: f stetig auf I = [a, b] und diffbar auf (a, b)
Aus dem Mittelwertssatz folgt, dass $x_1, x_2 \in I$ mit $x_1 < x_2$ so ist
$f(x_2)-f(x_1) / (x_2-x_1)  = f'(x_0)$ mit $x_1<x_0<x_2$ 
##### Injektivitätstest
f ist Injektiv auf I wenn f stetig und f streng Monoton Wachsend oder Fallend


### 4. Extremwertberechnung
#### Maximum/Supremum bzw Minimum/Infimum
Geg: $A \subseteq R; A\neq \emptyset; s \in R$ 
Def:
- s heißt Obere Schranke von A wenn $\forall X \in A x \leq s$
- s heißt supremum, falls s die kleinste obere Schranke ist
- s heißt Maximum von A max(A) = s wenn s das größte Element von a ist
**Regeln**
R1: sup(A) existiert
R2: sup(A) < infinity <=> A hat obere Schranke s in R
R3: sup(A) = s in A => s=max(A)

-> Untere Schranke andersherum
#### Globale / Lokale Extremwerte von f
geg: f: D $\subseteq$ R -> R
		I $\subseteq$ D
Globale Extremwerte f auf I
Suchen: max {f(x)  | x $\in$ I}
Ist a in I und gilt:
	- f(a) = max(f(x) | x in I)
	- so heißt x=a globale Maximalstelle von f auf I

##### Lokale Extremwerte
Lokale Maximalstelle ist eine Stelle, wo es ein interval gibt, wo die Funktion f ein Maximum oder Minimum hat

#### Satz von Weirstraß
Ist I = [a,b] abgeschlossenes interval und f stetig auf I, so gelten folgende Aussagen:
- A = {f(x)| x in I} ist abgeschlossenes Intervall
- max(f(x), x aus I) und min(f(x), x aus I) existieren
- Ist x_0 in I und f(x_0) ein Maximum, so ist x_0=a oder x_0 =b oder (x_0 in (a, b) und x_0 ist lokales Minimum oder Maximum)
 

#### Lokale Extremstelle, notwendig:
- Vor: f in x_0 diffbar
- Beh: f(x_0) lokales Maximum ->   f‘(x_0)=0

#### Lokale Extremstelle, Hinreichende Bedingungen

- (1)   f´(x_0)=0
- (2)  $\exists \epsilon$ derart, dass gilt:
	- f´(x) =
		- <0   x in (x_0-$\epsilon$, x_0)
		- >0   x in (x_0, x_0+$\epsilon$)   (für Minimum)

oder

(1) f‘(x_0) = 0
(2) f‘‘(x_0) > 0  (für Minimum)
dabei muss f‘‘ in einer Umgebung von x_0 muss existieren und stetig sein


#### Krümmung, Wendepunkte
Konvexe Kurve: Linkskurve, Sekante liegt über Funktion
Konkave Kurve: Rechtskurve, Sekante liegt unter Funktion
**Def**
Die Funktion f ist Konvex bzw Konkav bzw Streng Konvex oder Streng Konkav auf I, falls $\forall x_1, x_2: x_1 < x_2$       $\forall \alpha \in (0,1): f(x_1 + \alpha (x_2-x_1)) < f(x_1) + \alpha f(x_2 - x_1)$  für Konvex; Konkav mit > 
##### Kriterium
Wenn f stetig auf [a, b] und diffbar auf (a, b) Dann ist f 
-  f Konvex <-> f‘(x) monoton wachsend
- f Konkav <-> fˋ(x) monoton fallend
- Ergo: f‘‘(x) (> bzw <) 0

##### Satz
Sei I = [a, b] abgeschlossen und sei f stetig auf I und streng konvex auf I so gilt:
1. max( f(x) )= max{f(a), f(b)}
2. Auch mit min und konkav

#### Wendestelle
- Stelle an der sich das das Krümmungsverhalten der Funktion ändert
##### Wendestellen test
- Vor f ist in Umgebung von x_0 differenzierbar
**Satz**
a) x_0 Extremstelle von f‘
b) Notwendig:  x_0 ist Wendestelle wenn f‘‘(x) = 0
c) Hinreichend: f´´´(x) != 0

**Satz**
Stelle f‘(x)=f‘‘(x)=$f^{(n-1)}(x)$    und $f^n(x)!=0$
a) x_0 Wendestelle von n ungerade
b) x_0 lokale Maximalstelle wenn n gerade und x < 0
c) x_0 lokale Minimalstelle wenn n  gerade und x > 0



### Taylorreihen und Potzenreihen
#### Taylorpolynome
Geg: f: D $\subseteq$ R -> R
- x_0: Werte: f(x_0), f‘(x_0), …
Ges: Näherung für f(x) wenn x nahe x_0
##### Satz
Sei p(x) = $a_n *(x-x_0)^n + a_{n-1}*(x-x_0)^{n-1} + …$ 
ein Polynom vom Grad <= n Dann gilt: $p(x_0)=k! a_k$
- d.h. Koeffizienten sind berechenbar: a_k = p(x_0)/k!
##### n-tes Taylorpolynom
Das Polynom $T_{f, n, x_0} = sum(a_k * (x-x_0)^k)$ mit a_k = …
heißt n-tes Taylorpolynom an der Entwicklungsstelle x_0 


##### Satz
Tangente $T_1$(x) = f(x0) + f‘(x0) (x-x0)
ist due beste affine Näherung für f an der Stelle x_0, d.h. ist G(x) = f(x0) + a(x-x0) eine Gerade durch den Punkt (x0, f(x0)) und gilt
lim (f(x)-G(x))/(x-x_0) = 0
so ist a = f‘(x0) und damit G(x) = $T_1$(x)

### Restgliedformel von Lagrange
Ist f n+1 mal stetig diffbar auf D
Dann gibt es für jedes x in D ein xs zwischen x0 und x so dass gilt
$$R_{d, n, x_0}(x)= \frac{(f^n+1)*x_s}{(n+1)!} * (x - x_0)^{n+1}$$

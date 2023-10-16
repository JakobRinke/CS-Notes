### Definition
Eine Abbildung wo $a: \mathbb{N} \subseteq \mathbb{R} \rightarrow \mathbb{R}$
heißt unendliche Folge über $\mathbb{R}$
man nennt $a_n$ das n-te Folgeglied der Folge a
man schreibt: $a=\{a_1; a_2; a_3; ...\}$
*Es gibt auch Folgen über andere Mengen*

### Bildungsvorschriften
#### Verbale Bildung
- $a_n$ ist die n-te Primzahl

#### explizit
- $a_n = c + d * n$          $n>0$          $c, d \in R$    **arithmetische Folge**
- $a_n = d*x^n$               $n>0$         $x,d \in R$    **geometrische Folge**

#### rekursiv
$a_1 = 1; a_2 = 1;$
$a_n = a_{n-1} + a_{n+1}$                 $n\geq3$


### Arten
#### Konvergent
- Wenn a einen endlichen [[Grenzwerte von Folgen]] hat
#### Divergent
- Wenn a einen keinen [[Grenzwerte von Folgen]] hat
	- bestimmt divergent wenn Grenzwert Unendlich ist

#### Nullfolge
- Folge mit Grenzwert von 0
#### Beispiel
$a_n$ ist eine Folge mit: $a_n = 2 + \frac{cos(n)}{n}$
Beh: $lim_{a_n} = 2$ 
Bew: zu zeigen: $\forall \epsilon>0 \exists N=N(\epsilon) \forall n: n>N(\epsilon) => |a_n - 2| < \epsilon$ 
$fn:=|a_n-2| => |cos(n)|/n \le 1/n$
- Nach n auflösen
- n wird berechenbar wenn $\epsilon$ gegeben


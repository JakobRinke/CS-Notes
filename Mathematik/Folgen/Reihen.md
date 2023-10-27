
Ist $a_k$ = (a0; a1; …) eine Folge, so heißt

die summe von allen an

die n-te Partialsumme über $a_k$ 
Die Folge sn wird dann unendliche Reihe über $a_k$ genennt

*Die Summe kann auch bei k=1,2,… anfangen*

#### Reihen sind spezielle Folgen
__Bezeichnungen__
	sum(ak, k=0): Reihe über ak = Partielsummenfolge sn; ak heißt k-tes Glied der Reihe
	sum(ak, k=0) = S; S = lim n->inf a, S heißt summe der Reihe
	sum(ak, k=0) ist Konvergent wenn sie endlichen Grenzwert hat
							ist bestimmt divergent falls die Summe der Reihe gegen + oder - unendlich geht
							ist unbestimmt divergent falls Grenzwert nicht existiert


Geometrische Reihe
sum(k, inf) $x^k$ 
a) Partialsumme sn=$1*x+x^2+…x^n$ 
		$\frac{(1-x^{n+1})}{1-x}$
		n+1



#### Kriterium von Grenzwert
- Notwendiges Konvergenzkriterium:
	- sum(k=0, inf, ak) konvergent => lim k->inf ak geht gegen 0
- Satz: Sei ak eine Folge, dann gilt ist bei der entscheidung der konvergenz egal ob die summe konvergent ist


#### Reihen mit nichtnegativen Gliedern
sum(ak) mit ak >= 0
a) Partiellsumme: Sn = sum(ak bis n) wächst monoton
b) Ist die Reihe nach oben Beschränkt ist sie konvergent
	Ansonsten bestimmt divergent gegen + unendlich


#### Harmonische Reihe
- sum(1 bis k,  1/k)
- Geht gegen unendlich


#### Vergleichskriterium
Gegeben seien Folgen mit ak und bk mit ak <= bk
sn1 ist summe mit ak und sn2 ist summe mit bk
entsprechenden Partialsummenfolgen
Dann gilt lim sn1 <= lim sn2

a) *Majorantenkriterim*
	- summe über bk konvergent -> summe über ak ist auch konvergent
	- summe über bk ist konvergente mayorante von summe über ak
b) *Minorantenkriterium*
	- summe von ak divergent -> summe über bk auch unendloch
	- summe über ak ist divergente minorante von summe über bk

Erweiterung
	Satz 1:
		Bei 2 Reihen die beide größer 0 sind
		ak = O(bk)      analog(bk $\Omega$ ak)
		Dann  gelten die folgenden Aussagen
		a) Summe bk Konvergent, dann bk auch Kovergent
		b) wenn ak bestimmt divergent dann bk auch
- G = (V, E) besteht aus einer Menge von Ecken V und Kanten E=E(G)$\subseteq$ {{x,y}, x!=y aus V}
- x,y aus V hezßen benachbart wenn x,y in E(G)
- x aus V und e aus E heißen inzident falls x in e, für e in E schreibe auch V(e) = e für die Menge der beiden Endecken von e
- Eine Folge von P = x_0,…, von paarweise verschiedenen Ecken heißt Weg der länge l von x_0 nach x_l falls x_{i-1}, x_{i} in E
- Ein Graph H heißt Teilgraph des Graphen G  H<=G 
- Falls die E von H  in G   und Kanten H auch in G
 - Sind G und H Graphen heißt eine Bijektion f: V(G) -> V(H) ein Graphisomorphismus, falls für x,y aus V(g) gilt das x, y in E genau dann wenn f(x), f(y) in E(H)
- Ein Weg heißt Kreis der Länge l+1 falls x_l  x_0 in E(G)
- Ein Baum ist ein Zusammenhänger Graph ohne Kreise
- Ein Wald ist ein Graph ohne Kreise
- Die Zusammenhangs-Komponenten eines Waldes sind Bäume
- Ein zusammenhängender Wald ist ein Baum

### Satz:
Für alle Graphen G |V(G)| > 0, sind äquivalent
1. G ist ein Baum
2. G ist zusammenhängend und G-e ist Unzusammenhängend 
3. G hat keine Kreise, G+xy hat Kreis für je zwei nicht Benachbarte Ecken x!=y

### Satz für einen Graphen G  mit |V(G)| > 0 sind äquivalent
1. G Baum
2. G zusammenhängend
3. G hat keine Kreise und |V(G)| = |E(G)| + 1

### K Färbung
Eine k-Färbung des Graphen G ist eine Abbildung f:V(G)->{1…k} mit f(x) != f(y) für alle xy in E(G). G heißt k Färbbar, wenn G eine k-Färbung besitzt
Die kleinste Zahl k für die eine k-Färbung existiert für G heißt chromatische Zahl von G
$\chi ^{(G)}$ 


### Aufspannender Baum
Ein aufspannender Baum B von G heißt Spannbaum von G
Jeder zusammenhängende Graph enthält einen Minimal zusammenhängenden aufspannenden Graph, also einen Spannbaum
Für einen Graphen G und zwei Ecken a,b bezeichnet d(a, b) die Länge eines Kürzesten a,b Weg
d(a, b) heißt auch der Abstand von a,b in G
d: V(G) x V(G) -> N ist eine Metrik 
Eis Spannbaum T eines Zusammenhängenden Graphen G heißt Breitensuchbaum bei x_0, falls gilt
d_T(y, x_0) = d(y, x_0), f.a.  in V(G)
Ein *Breitensuchbaum* entsteht, in dem man angehend von x_0 bzw T=({x_0}, {}) den Graphen entdeckt: Ein Entdeckungsschritt besteht aus dem Hinzufügen einer Ecke y in V(G) \ V(T) und einer Kante zy in E (G) und z in V(t) 
Bei der Breitensuche wird ein möglichst altes z gewählt
Ein *Tiefensuchbaum* dabei wird ein möglichst “junges“ z gewählt
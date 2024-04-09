
Ein (endlicher) *Wahrscheinlichkeitsraum* (Wkt-Raum) $(\Omega, p)$ ist eine Endliche Menge zusammen mit einer Abbildung $p: \Omega -> [0, 1]$ 
für die gilt sum(o in Omega, p(o)) = 1
*p heißt Verteilung auf Omega*
Die Elemente aus Omega heißen *Elementarereignisse*
A $\subseteq \Omega$ heißt Ereignis, die Zahl p(A) = sum(a in A, p(a))

Es gilt für Ereignisse A, B, A_1, A_
1. $A \subseteq B \implies p(A) \le p(B)$ 
2. $p(A \cup B) = p(A) + p(B) - p(A\cap B)$ 
3. Sind $A_1 … A_k$ Paarweise Disjunkt so gilt $p(A_1 \cup … \cup A_k) = p(A_1) +… p(A_k)$ 
4. $p(\Omega / A) = 1 - p(A)$ 
5. $p(A \cap A_2 …) \le p(A_1) + p(A_2) …$ 

p((w1, .., wm)) := prod(pj(wj)) für (w1… wj) in Omega^m eine Verteilung auf Omega:= Omega1 x … x Omegam
Es gilt für A1 in Omega, …, Am in Omegam   p(A1 x … x Am) = prod(m, j1) 
spezielles Ereignis in Omega, Rechteckmenge


Satz: p(A | B) = P(B | A) * p(A) / p(B)
p(B) = sum(p(B, Aj) * Aj)

Abbildung von $X: \Omega -> \mathbb{R}$  ist reelwertige Zufallsvariable
— Werten Eines Ergeignis

Neue Zufallvariable für Varianz
Var(X) := $E((X-E(X))^2)   =  E(X^2) - E(X)^2$ 
$Cov(X, Y) := E((X-E(X))* (Y-E(Y)))$ 
$Var(X+Y) = Var(X) + Var(Y) + 2 Cov(X, Y)$ 

Eine ZVA X: $\Omega -> R$ heißt Bernoulli Verteilung im Parameter p in [0, 1] falls p(X=1)=p und p(X=0)=1-p
Schreibweise
X ~ Lr(p) ist E(x) = p
X ~ Lr(1-p)

Gegeben: $f(x):D\subseteq \mathbb{R}->\mathbb{R}$    $I\subseteq D$ Intervall

f heißt Injektiv auf $I$, falls $\forall x_1,x_2\in I: x_1 \neq x_2 \implies f(x_1)\neq f(x_2)$ 
Weiterhin ist J = f(I) = {f(x); $x \in I$}
Ist $f:I\subseteq R->R$ injektiv auf I und $J=f(I)$ das Bild von I bzgl. f, so gibt es eine Fkt $J\subseteq R -> R$ mit $\forall x \in I \forall y \in J: y=f(x) \iff x=g(y)$ 
g nennt man die Umkehrfunktion von f: $g=f^{-1}$ 

```functionplot
---
title: Umkehrfunktion
xLabel: 
yLabel: 
bounds: [0,10,0,10]
disableZoom: false
grid: true
---
f(x)=x^2+1
h(x)=x
g(x)=(x-1)^(1/2)

```
**Es gilt:**
$\forall x \in I: g(f(x))=x$
$\forall y \in I: f(g(y))=y$ 

Insbesondere gilt auch:
f: I -> J    und    g: J->I           sind bijektiv

Für die Ableitung von $g=f^{-1}$ gilt dann g'(y)=$\frac{1}{f'(x)}=\frac{1}{f'(g(x))}$ 
wobei g in (x, y) differenzierbar ist $\iff$ f'(x) $\neq$ 0

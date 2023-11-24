- "Ich kann den Funktionsgraphen zeichnen, ohne den Stift abzusetzen"
a) f ist stetig an der Stelle $x_0 \in D$ falls gilt:
	1. f ist in einer Umgebung von $x_0$ definiert
	2. $lim_{x->x_0}f(x)=f(x_0)$

b) f ist links\rechtsseitig stetig an der Stelle $x_0 \in D$ falls gilt:
	1. $lim_{x->x_0-0}f(x)=f(x_0)$   \   $lim_{x->x_0+0}f(x)=f(x_0)$

c) f stetig auf dem Intervall I=\[a, b) falls gilt:
 1. I $\subseteq$ D
 2. f stetig $\forall x \in (a, b)$
 3. f rechtseitig stetig in $x_0=a$
*Analog für I = \[a, b],       I = (a, b],    I = (a,b)*


### Hauptsatz über stetige Funktionen
Folgende Elementare Funktionen sind stetig in $x_0 \in R$ sofern sie in einer Umgebung von $x_0$ definiert sind
$f(x) = x^n$        $n\in Z$
$f(x) = \sqrt[m]{x}$      $m\in Z$
$f(x) = c$
sin, cos, tan; $f(x)=e^x$
sind g,h stetige Funktionen in $x_0$ so ist $f$ stetig in $x_0$ für
$f(x )\pm h(x)$ 
$f(x) = g(x)/h(x)$;                    h(x)!=0
f(x) = c \* g(x)

Sing g und h stetig in $x_0$ so ist f stetig in $x_0$ mit f(x)=g(h(x))


```functionplot
---
title: Stetige Funktion zeichnen
xLabel: 
yLabel: f(x)
bounds: [-4,4,-4,4]
disableZoom: true
grid: true
---
g(x)=1/x
h(x)=-1/x
f(x)=sin(x)/x
```
lim x->0 ist unbestimmt 


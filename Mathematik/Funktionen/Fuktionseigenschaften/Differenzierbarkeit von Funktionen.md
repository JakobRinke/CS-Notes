### Ableitung
- Geg: $f:D\in \mathbb{R}-> \mathbb{R}$ 
- Motivation: Anstieg an beliebiger Stelle ermitteln, Beliebig genau gemessen
- Ableitung von f an der Stelle $x_0$ ist $lim_{h->0}\frac{f(x_0+h)-f(x_0)}{h}$
- Ist endlich und Differenzierbar

### Geometrische Interpretation

```functionplot
---
title: 
xLabel: 
yLabel: 
bounds: [-10,10,-10,10]
disableZoom: false
grid: true
---
f(x)=x^2
f(x)=2x-1
f(x)=4x - 3
P(1, 1)
```

Immer genauer werdene Sekante -> Tangente
Anstieg der Sekante: 
$$dy = df(x_0 + h) - f(x_0)$$
$$ dx = (x_0+h) - x_0 = h$$
$$f'(x_0) = lim_{dx->0}\frac{dy}{dx}$$


### Ableitung von f
f heißt differenzierbar auf dem Intervall $I \subseteq D$ falls f'(x) für alle i $x \in I$ existiert
Die Funktion $x\in I \implies f'(x) \in R$ heißt Ableitung von bzw. 1. Ableitung von f auf I

- Ableitung von f: f'; D(f) df/dx
- Ableitung an der Stelle x: f'(x); D(f)(x); df/dx | x


$$ df(x_0, h) = f'(x_0)*dy$$

#### Satz
Ist f in $x_0$ differenzierbar, so ist f' stetig in $x_0$ 
über Universen $U_1, U_n$ Satz mit Variablen $x_1, x_n$ der bei Ersetzung jeden x durch ein Objekt aus U stets zu ein [[Aussagen]] wird

- „x ist prim“ ist AF mit Variablen x über die Natürlichen Zahlen



**Nach Ersetzung von x durch eine konkrete Zahl entsteht eine Aussageform mit weniger Variablen** 

Sei $p(x)$ eine Aussageform über eine Variable x über dem Universum U

$\forall x: p(x)$ ist die Aussage: *„Für alle x aus U ist p(x) war“*
Ihr Wahrheitswert ist {w falls alle x p(x) erfüllen; f falls nicht}

$\exists x: p(x)$ ist die Aussage: *„Für ein x aus U ist p(x) war“*
Ihr Wahrheitswert ist {w falls es ein x gibt was p(x) erfüllt; f falls nicht}


**Für das Leere Universum gilt:**
- $\forall x: p(x)$ -> Tautologie
- $\exists x: p(x)$ -> Kontradiktion

**Endliche Universen U mit Objekten $O_1,…, O_n$**
$\forall x: p(x) \equiv p(O_1) \land … \land p(O_n)$
$\exists x: p(x) \equiv p(O_1)\lor … \lor p(O_n)$


### Regeln
- Verwandt  mit [[Logische Rechenregeln]]
$\forall x: (p(x) \land q(x)) \equiv (\forall x: p(x)) \land (\forall x:q(x))$
$\exists x: (p(x) \lor q(x)) \equiv (\exists x: p(x)) \lor (\exists x:q(x))$
$\lnot(\forall x: p(x)) \equiv \exists x: \lnot p(x)$
$\lnot(\exists x: p(x)) \equiv \forall x: \lnot p(x)$
- Gleichartige Quantoren sind Vertauschbar
- 
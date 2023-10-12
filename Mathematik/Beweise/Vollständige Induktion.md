= Methode um ein [[Prädikat]] zu Beweisen


### Arten
#### Tiefe 1
- Wenn $A(1)$ und $A(1) \implies A(2)$ dann $A(2)$
- Wenn $A(n-1)$ und $A(n-1) \implies A(n)$ dann $A(n)$
- $\equiv \forall n: A(n)$ 

A(1) = *Induktionsanfang*
A(n-1) -> A(n) = *Induktionsschritt*

1. Erste Aussage beweisen
2. Induktionsschritt (Induktiv Step)


#### Tiefe 2
- Aussage A soll für alle $\mathbb{N}$ gelten

1. Erste Beiden Aussagen beweisen
2. Bedingung $(A(n-2)) \land A(n-1)) \implies A(n)$ beweisen


#### allgemein
- $A(1) \land \forall n \in \mathbb{N} (A(1) \land … \land A(n)) \implies A(n+1)$


### Schema
__Induktionsanfang__
	__Beh.__
	__Bew__
__Induktionsschritt__
	__Vor__
	__Beh.__
	__Bew__
	
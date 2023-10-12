
Sind $p$ und $q$ [[Aussagen]], so auch

#### Syntax
$p \wedge q$  („und“)
$p \vee q$  („oder“)
$\neg p$ („nicht“)
$p \implies q$  („impliziert“)
$p \iff q$ („genau dann wenn“)

**Immer Klammern verwenden!**

#### Semantik
Die Wahrheitswerte ergeben sich aus den Wahrheitswerten com $p$ und $q$ 

| $p$   | $q$  | $p \land q$ | $p \lor q$ | $\neg p$ | $p \implies q$ | $p \iff q$ |
| --- | --- | ----------- | ---------- | -------- | -------------- | ---------- |
| f   | f   | f           |   f         |    w      |        w        |    w        |
| f   | w   | f           |       w     |    w      |      w          |     f       |
| w   | f   | f           |     w       |     f     |      f          |    f        |
| w   | w   | w           |      w      |    f      |     w           |    w        |



#### Tautologie: Formel die konstant w ist
#### Kontraktion: Formel die konstant f ist

#### Logische Äquivalenz
- Formeln sind Logisch Äquivalent, wenn sie den gleichen Wahrheitswerteverlauf haben
- $p \equiv q$  falls $p\iff q$ Tautologie
	- Satz von der Kontraposition
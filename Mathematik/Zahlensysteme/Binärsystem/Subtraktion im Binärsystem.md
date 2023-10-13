- Zu subtrahierende Zahl Umkehren ( 0 -> 1; 1 -> 0)
- eins auf diese Zahl addieren
- Erste Zahl Plus die Modifizierte Zahl
- Beim Ergebnis den ersten Bit streichen
- -> Ergebnis nach dem Streichen ist Ergebnis der Subtraktion




101010 -
001101

001101 -> muss in eine Negative Zahl umgewandelt werden
110010 -> Alles umgekehrt **Auf die Anfangsnullen achten!**
110011 -> 1 draufaddiert

1110011 ist -1101

101010 + 0011 rechen -> Lösung
Siehe [[Addition im Binärsystem]]

   1   0   1   0   1   0
   1   1   0   0   1   1
1                  1
________________________
1  0  1   1   1   0    1

Erste Ziffer Streichen
1 1 1 1 0 1


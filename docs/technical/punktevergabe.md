# Punktevergabe

Zur automatischen Punktevergabe stehen verschiedene Regeln bzw. Rechenvorschriften zur Auswahl. Grundsätzlich basiert die im Programm enthaltene Logik zur Punktevergabe auf der Annahme, dass mehr Punkte besser sind, d.h. die Kandidatin mit am Ende den meisten Punkten gewinnt.

## Punkte relativ nach Abstand der Werte voneinander (Punkte von 1 bis 10)

Die Kandidatin mit dem besten Ergebnis erhält 10 Punkte, die letztplatzierte Kandidatin 1 Punkt. Kandidatinnen, deren Ergebnis dazwischen liegt, erhalten Punkte relativ (linear skaliert) dazu, wie nah ihr Ergebnis dem besten bzw. schlechtesten ist. Gerundet wird dabei auf eine Nachkommastelle.

Diese Art der Punktevergabe hat den Vorteil, dass sie weitestgehend unabhängig von der Anzahl der Kandidatinnen funktioniert, für Ergebnisse in einem kalkulierbaren Rahmen sorgt und zugleich das genaue Ergebnis berücksichtigt (also nicht nur eine Platzierung). Nachteilig ist jedoch sicherlich, dass die Berechnung vergleichsweise kompliziert und damit dem Publikum nicht intuitiv verständlich sein könnte. Zudem ergeben sich die Punktzahlen erst durch den Vergleich mit den anderen Kandidatinnen, können also erst berechnet werden, wenn die letzte Kandidatin das Spiel beendet hat.

Falls alle Kandidatinnen das gleiche Ergebnis haben, erhalten alle 10 Punkte.

Beispiele:

* Lautstärkemessung; 4 Kandidatinnen mit 90,2 dB(A), 89,4 dB(A), 87,6 dB(A), 84,5 dB(A) → 10,0 Punkte, 8,7 Punkte, 5,9 Punkte, 1,0 Punkte
* Kirschen-Schätzspiel; 3 Kandidatinnen mit 150g, 180g, 214g → 10,0 Punkte, 5,8 Punkte, 1,0 Punkte

## Punkte nach Platzierung (1 pro Platz + 1)

Die letztplatzierte Kandidatin erhält einen Punkt, mit jedem besseren Platz gibt es einen zusätzlichen Punkt. Die Anzahl der auf diese Weise erreichbaren Punkte ist somit von der Anzahl der Kandidatinnen abhängig.

Beispiel bei 3 Kandidatinnen:

1. Platz → 3 Punkte
2. Platz → 2 Punkte
3. Platz → 1 Punkt

Im Falle eines Gleichstands erhalten gleichplatzierte Kandidatinnen die gleiche Punktzahl und es werden entsprechend der Anzahl von gleichplatzierten Kandidatinnen darauffolgende Plätze übersprungen - es gibt also z.B. zwei erste Plätze, dafür dann aber keinen zweiten Platz.

## Punkte nach Platzierung (2 pro Platz + 1)

Die letztplatzierte Kandidatin erhält einen Punkt, mit jedem besseren Platz gibt es zwei zusätzliche Punkte. Die Anzahl der auf diese Weise erreichbaren Punkte ist somit von der Anzahl der Kandidatinnen abhängig.

Beispiel bei 3 Kandidatinnen:

1. Platz → 5 Punkte
2. Platz → 3 Punkte
3. Platz → 1 Punkt

Im Falle eines Gleichstands erhalten gleichplatzierte Kandidatinnen die gleiche Punktzahl und es werden entsprechend der Anzahl von gleichplatzierten Kandidatinnen darauffolgende Plätze übersprungen - es gibt also z.B. zwei erste Plätze, dafür dann aber keinen zweiten Platz.

## Punkte nach Wert (gerundet; 1 Nachkommastelle(n))

Das Spielergebnis wird 1:1 als erreichte Punktzahl betrachtet, wobei eine Rundung auf eine Nachkommastelle stattfindet. Die Anzahl der auf diese Weise erreichbaren Punkte ist somit von der Anzahl der Kandidatinnen unabhängig, aber ergibt nur bei bestimmten Spielen Sinn.

Beispiele Lautstärkemessung:

* 89,64 dB(A) → 89,6 Punkte
* 89,65 dB(A) → 89,7 Punkte

## Punkte nach Wert (gerundet; 0 Nachkommastelle(n))

Das Spielergebnis wird 1:1 als erreichte Punktzahl betrachtet, wobei eine Rundung auf ganze Zahlen stattfindet. Die Anzahl der auf diese Weise erreichbaren Punkte ist somit von der Anzahl der Kandidatinnen unabhängig, aber ergibt nur bei bestimmten Spielen Sinn.

Beispiele Lautstärkemessung:

* 89,49 dB(A) → 89 Punkte
* 89,50 dB(A) → 90 Punkte

## Punkte nach Wert (5x multipliziert, gerundet)

Die erreichte Punktzahl wird direkt vom Spielergebnis der einzelnen Kandidatin abgeleitet; es ergibt multipliziert mit dem Faktor 5 und gerundet auf eine Nachkommastelle die Punktzahl. Die Anzahl der auf diese Weise erreichbaren Punkte ist somit von der Anzahl der Kandidatinnen unabhängig, aber ergibt nur bei bestimmten Spielen Sinn.

Beispiele Lautstärkemessung:

* 87,4 dB(A) → 437,0 Punkte
* 83,3 dB(A) → 416,5 Punkte

## Punkte nach Wert (Differenz untereinander 3x multipliziert)

Die erreichte Punktzahl wird vom Vergleich mit dem Spielergebnis der anderen Kandidatinnen abgeleitet. Die Differenz multipliziert mit dem Faktor 3 und gerundet auf eine Nachkommastelle ergibt das Ergebnis.

Beispiele:

* Lautstärkemessung; 4 Kandidatinnen mit 90,2 dB(A), 89,4 dB(A), 87,6 dB(A), 84,5 dB(A) → 17,1 Punkte, 14,7 Punkte, 9,3 Punkte, 0,0 Punkte
* Kirschen-Schätzspiel; 3 Kandidatinnen mit 150g, 180g, 214g → 192,0 Punkte, 102,0 Punkte, 0,0 Punkte
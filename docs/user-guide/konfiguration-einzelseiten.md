# Konfiguration einzelner Seiten

## Titelseite

Der Seitentyp "Titelseite" zeigt lediglich ein wählbares Bild und zeigt die Überschrift nach dem Schema `Wahl der Kirschenkönigin {Jahr}` an.

In der Praxis fungiert diese Seite meistens als eine Art Platzhalter, wenn nichts Wichtigeres auf dem Bildschirm angezeigt werden soll.

![Titelseite](images/010-titelseite.png)

Die Überschrift kann nicht geändert werden, lediglich das gezeigte Titelbild kann frei gewählt werden. Die Auswahl des Titelbildes kann über den Button "Resource auswählen" gestartet werden. Wichtig: Nachdem ein Bild ausgewählt wurde, muss die Auswahl über den Button "Konfiguration übernehmen" (am unteren Bildschirmrand) bestätigt werden.

Für das Titelbild kann eine "Stretch-Option" gewählt werden. Diese Auswahl beeinflusst, wie das Bild in den auf dem Bildschirm verfügbaren Platz "eingepasst" wird. Welche Optionen es diesbezüglich gibt, erläutert das Kapitel [Stretch-Optionen](../technical/stretch-optionen.md). Eine Änderung der Stretch-Option wird sofort sichtbar und erfordert keinen zusätzlichen Klick auf "Konfiguration übernehmen".

Diese Seite zeigt Veranstaltungslogo und Hintergrund aus den Projekteinstellungen _nicht_ an.

## Kandidatenübersicht

Der Seitentyp "Kandidatinneübersicht" zeigt eine tabellarische Übersicht aller Kandidatinnen mit zuvor erfassten Daten (siehe Kapitel [Konfiguration->Kandidatinnen verwalten](konfiguration.md#kandidatinnen-verwalten)) an.

![Kandidatinnenübersicht](images/011-kandidatinnenuebersicht.png)

Die einzige Konfigurationsoption für diese Seite ist die Änderung des angezeigten Titels. Eine Änderung des Titels muss über den Button "Konfiguration übernehmen" bestätigt werden.

Diese Seite zeigt Veranstaltungslogo und Hintergrund aus den Projekteinstellungen an.

## Kandidatinnen Profilseite

Der Seitentyp "Kandidatinnen Profilseite" sieht zunächst ähnlich aus, wie auch die Titelseite: Sie zeigt zunächst ein wählbares Titelbild mit ebenfalls wählbarer [Stretch-Option](../technical/stretch-optionen.md) an.

Wie auch bei der Titelseite gilt: Nachdem ein Bild ausgewählt wurde, muss die Auswahl über den Button "Konfiguration übernehmen" bestätigt werden, während eine Änderung der Stretch-Option sofort sichtbar wird.

Anders als bei der Titelseite ist der Titel der Seite frei wählbar, wobei der vorausgefüllte Text dem Schema der Titelseite (`Wahl der Kirschenkönigin {Jahr}`) entspricht. Eine Änderung des Titels muss via "Konfiguration übernehmen" bestätigt werden.

![Kandidatinnenübersicht](images/012-kandidatinnen-profilseite-1.png)

In der Administrationsansicht zeigt diese Seite zudem noch eine Liste der Kandidatinnen (wie erfasst gemäß [Konfiguration->Kandidatinnen verwalten](konfiguration.md#kandidatinnen-verwalten)) an. Mit einem Rechtsklick auf den Namen der betreffenden Kandidatin und anschließendem Klick auf "Profil einblenden" wird das Profil der Kandidatin für das Publikum angezeigt:

![Kandidatinnenübersicht](images/013-kandidatinnen-profilseite-2.png)

Der Button "Anzeige zurücksetzen" blendet das Profil wieder aus.

Diese Seite zeigt Veranstaltungslogo und Hintergrund aus den Projekteinstellungen _nicht_ an.

## Lautstärkemessung

Bei der Lautstärkemessung handelt es sich um die wahrscheinlich wichtigste und zugleich komplexeste der im Programm enthaltenen Seiten.

Die Seite zeigt das Veranstaltungslogo, nicht aber den Hintergrund aus den Projekteinstellungen an. Beim Spiel-Icon handelt es sich (nicht veränderlich) um einen High-Heel.

### Einstellungen

Als Einstellungen der Seite verändert werden können der Seitentitel, die Dauer der Messung in Sekunden, sowie die Anzahl der Nachkommastellen der gemessenen Schalldruckpegel. Die Änderung der angezeigten Nachkommastellen hat keine Auswirkungen auf die Punktevergabe! Änderungen allen diesen Einstellungen müssen via "Konfiguration übernehmen" bestätigt werden, bevor sie wirksam werden.

Auf der Seite für die Lautstärkemessung selbst gibt es _keine_ Einstellungen die Mikrofone betreffend. Diese müssen wie im Kapitel [Konfiguration->Lautstärkemessung vorbereiten](konfiguration.md#lautstärkemessung-vorbereiten) beschrieben eingerichtet werden.

### Profil einblenden

Ähnlich wie bei der [Kandidatinnen Profilseite](#kandidatinnen-profilseite) gibt es in der Administrationsansicht eine Liste der Kandidatinnen, für die mit einem Rechtsklick und folgendem Klick auf "Profil einblenden" das Profil eingeblendet werden kann.

Ein Klick auf den Button "Anzeige zurücksetzen" blendet das Profil wieder aus.

### Lautstärkemessung

Im Ausgangszustand (oder nach dem Zurücksetzen) zeigt diese Seite neben dem Titel bereits eine Vorschau auf die während der Messung angezeigte Visualisierung. Bei der groß dargestellten Zahl handelt es sich um die Anzahl der in der Messung verbleibenden Sekunden.

![Lautstärkemessung: Ausganszustand](images/014-lautstaerkemessung-01.png)

Der Button "Test-Messung beginnen" startet die Lautstärkemessung. Die Test-Messung ist identisch zur einer "richtigen" Messung (auch die Visualisierung für das Publikum ist identisch), der Unterschied besteht darin, dass der gemessene Schalldruckpegel nicht (zwecks Punktevergabe) einer Kandidatin zugeordnet wird.

Während die Messung läuft, zeigt die Visualisierung den Verlauf des gemessenen Schalldruckpegels an und der Countdown bis zum Ende der Messung zählt runter. Die Visualisierung ändert ihre Skalierung dynamisch, passt also den Bereich der Y-Achse so an Minimal- und Maximalwert an, dass der Graph immer einen möglichst grossen Bereich des Bildschirms ausfüllt (und so steil wie möglich erscheint).

Unter dem Diagramm sind während der Messung der aktuelle Schalldruckpegel (links) und der bisherige Durschnitt (rechts) zu sehen.

![Lautstärkemessung: Testmessung aktiv](images/015-lautstaerkemessung-02.png)

Am Ende der Messung bleibt die Anzeige hauptsächlich einfach stehen. Statt dem aktuellen Schalldruckpegel wird links unter dem Diagramm jedoch der Maximalwert während der vorangegangenen Messung eingeblendet. Dieser ist jedoch rein informativer Natur und hat _keine_ Relevanz für die Punktevergabe - diese basiert ausschließlich auf dem Durchschnitt über gesamte Dauer der Messung hinweg.

![Lautstärkemessung: Testmessung beendet](images/016-lautstaerkemessung-03.png)

Die "richtige" Messung für eine Kandidatin kann mit einem Rechtsklick auf ihren Namen in der Liste der Kandidatinnen in der Administrationsansicht ausgelöst werden - wie auch die Einblendung des Profils, nur anschließend natürlich mit einem Klick auf "Lautstärkemessung ausführen".

Wie zuvor bereits erwähnt, besteht der wichtige Unterschied zur Testmessung darin, dass nur auf diesem Wege das Ergebnis der Kandidatin zugeordnet wird bzw. Punkte automatisch vergeben werden können. Der einzige sichtbare Unterschied bei der Messung ist der angezeigte Titel, welcher bei der "richtigen" Messung noch um den Vornamen der betreffenden Kandidatin ergänzt wird.

![Lautstärkemessung: Kandidatin-Messung beendet](images/017-lautstaerkemessung-04.png)

Der dritte Eintrag im Kontextbenü bei Rechtsklick auf den Namen einer Kandidatin ist "Lautstärke manuell erfassen/korrigieren" - bei welcher ein Ergebnis manuell eingetragen werden kann. Diese Funktion kann genutzt werden, falls z.B. versehentlich eine Testmessung ausgeführt wurde, um das Ergebnis der Kandidatin "gutzuschreiben". Aber Achtung - jegliches zuvor möglicherweise vorhandene Ergebnis wird überschrieben.

Für die automatische und üblicherweise verwendete Punktevergabe zu nutzen, muss der Button "Punkte berechnen" angeklickt werden. Auch beim Wechsel auf die nächste Seite im Ablauf werden keine Punkte automatisch eingetragen.

> ⚠️ **Punktevergabe nicht vergessen!**
>
> Es werden vom Programm keine Punkte "stillschweigend" eingetragen/gespeichert. 
> Die Punktevergabe muss vom Benutzer gezielt ausgelöst und bestätigt werden.

![Lautstärkemessung: Kandidatin-Messung beendet](images/018-lautstaerkemessung-05.png)

Spätestens vor dem Klick auf "Punkte berechnen" sollte nochmals ein kurzer prüfender Blick auf die links davon ausgewählte Regel zur Punktevergabe gehen. Für eine detaillierte Auflistung und Erläuterung aller wählbarer Regeln siehe Kapitel [Punktevergabe](../technical/punktevergabe.md). Nach dem Klick auf den "Punkte berechnen"-Button öffnet das Programm eine Dialogbox und zeigt darin, wie viele Punkte welcher Kandidatin gutgeschrieben werden (siehe Screenshot). Nach der Bestätigung dieser Nachfrage speichert das Programm die Punkte dann.

> ℹ️ **Keine Sorge...**
>
> Es besteht keine Gefahr, dass das Programm Punkte doppelt gutschreiben könnte.
> Das Programm verwaltet, welche Kandidatin für welches Spiel bereits wie viele Punkte erhalten hat. Eine doppelte oder erneute Punktevergabe ersetzt lediglich die zuvor ggfs. bereits gespeicherte Punktzahl - diesbezüglich kann also nicht wirklich etwas schiefgehen.

## Kirschen-Schätzspiel

## Allgemeine Spielergebnisseite (sofort aufdecken)

## Allgemeine Spielergebnisseite (gesammelt aufdecken)

## Diashow

## Webseite anzeigen

## Bild anzeigen

## Zwischenergebnisseite

## Endergebnisübersicht

## Endergebnisseite
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

Um die automatische und üblicherweise verwendete Punktevergabe zu nutzen, muss der Button "Punkte berechnen" angeklickt werden. Auch beim Wechsel auf die nächste Seite im Ablauf werden keine Punkte automatisch eingetragen.

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

Die Seite "Kirschen-Schätzspiel" dient -offensichtlich- der Begleitung des Kirschen-Schätzspiels, bei dem die Kandidatinnen das Gewicht eines Behälters voll Kirschen schätzen müssen. Es gewinnt die Kandidatin, bei der die Differenz zwischen Schätzung und realem Gewicht am geringsten ist.

Die Seite zeigt sowohl Veranstaltungslogo als auch Hintergrund aus den Projekteinstellungen an. Beim Spiel-Icon handelt es sich (nicht veränderlich) um eine Kirsche.

Die einzige Einstellung der Seite ist der frei wählbare Titel. Änderungen daran müssen via "Konfiguration übernehmen"-Button bestätigt werden.

![Kirschen-Schätzspiel: Ausgangzustand](images/019-kirschen-schaetzspiel-01.png)

Die Zuschauer sehen im Ausgangszustand der Seite die Namen, dahinter jeweils einen Strich und drei grosse Fragezeichen hinter dem Text "Gemessenes Gewicht der Kirschen".

In der Administrationsansicht wird eine Liste aller Kandidatinnen eingeblendet (wie erfasst gemäß [Konfiguration->Kandidatinnen verwalten](konfiguration.md#kandidatinnen-verwalten)). Mit einem Rechtsklick auf den Namen einer Kandidatin und einem Klick auf "Abgegebene Schätzung eingeben" öffnet sich ein Eingabefenster. Die Schätzung muss in Gramm eingegeben werden.

Sobald für eine Kandidatin eine Schätzung erfasst wurde, wird diese für das Publikum anstatt des Strichs hinter ihrem Namen sichtbar:

![Kirschen-Schätzspiel: Schätzung eingegeben](images/020-kirschen-schaetzspiel-02.png)

Nachdem für alle Kandidatinnen ihre geschätzten Werte eingegeben wurden, kann in das Eingabefeld "Geben Sie das per Waage gemessene Gewicht der Kirschen ein [g]" das tatsächliche Gewicht in Gramm eingegeben werden.

Der Klick auf den Button "Abweichungen berechnen und anzeigen" berechnet anschliessend die Differenzen zu den jeweiligen Schätzungen und macht sowohl die Differenzen als auch das Gewicht für das Publikum sichtbar:

![Kirschen-Schätzspiel: Ergebnis](images/021-kirschen-schaetzspiel-03.png)

> ℹ️ **Falls es mal wieder hektisch wird...**
>
> Falls es während der Veranstaltung etwas hektisch werden sollte, kein Problem: 
> Es ist auch möglich, zuerst das reale Gewicht einzugeben und im Anschluss noch Schätzungen nachzureichen oder zu korrigieren. Die Reihenfolge der Eingabe spielt für das Programm keine Rolle.
> Lediglich die Anzeige auf dem Bildschirm könnte das Publikum entsprechend kurzzeitig irritieren.

Um die automatische und üblicherweise verwendete Punktevergabe zu nutzen, muss der Button "Punkte berechnen" angeklickt werden. Auch beim Wechsel auf die nächste Seite im Ablauf werden keine Punkte automatisch eingetragen.

> ⚠️ **Punktevergabe nicht vergessen!**
>
> Es werden vom Programm keine Punkte "stillschweigend" eingetragen/gespeichert. 
> Die Punktevergabe muss vom Benutzer gezielt ausgelöst und bestätigt werden.

Spätestens vor dem Klick auf "Punkte berechnen" sollte nochmals ein kurzer prüfender Blick auf die links davon ausgewählte Regel zur Punktevergabe gehen. Für eine detaillierte Auflistung und Erläuterung aller wählbarer Regeln siehe Kapitel [Punktevergabe](../technical/punktevergabe.md). Nach dem Klick auf den "Punkte berechnen"-Button öffnet das Programm eine Dialogbox und zeigt darin, wie viele Punkte welcher Kandidatin gutgeschrieben werden (siehe Screenshot). Nach der Bestätigung dieser Nachfrage speichert das Programm die Punkte dann.

## Allgemeine Spielergebnisseite (sofort aufdecken)

Die "Allgemeine Spielergebnisseite" kann genutzt werden, um die Ergebnisse von Spielen zu erfassen, die nicht über dieses Programm errechnet werden (also anders als bei Lautstärkemessung oder dem Kirschen-Schätzspiel).

Der Zusatz "sofort aufgecken" bedeutet, dass ins Programm eingegebene Ergebnisse bzw. Punktzahlen _sofort_ für das Publikum sichtbar gemacht werden. Beim Kirschenmarkt wird dieser Seitentyp üblicherweise für das Glücksrad verwendet.

Als Einstellungsmöglichkeiten bietet die Seite ein Eingabefeld für den Seitentitel und einen Auswahlfeld für das Spiel-Icon. Eine Änderung des Seitentitels muss über den Button "Konfiguration übernehmen" bestätigt werden, bevor sie für das Publikum sichtbar wird. Eine Änderung des Spiel-Icons hingegen wird sofort für das Publikum sichtbar. Als Spiel-Icon können lediglich die in der Auswahl verfügbaren Icons verwendet werden - die Verwendung einer eigenen Grafik (z.B. aus einer Datei) ist nicht möglich. Sofern in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) die entsprechende Einstellung gesetzt ist, wird das Spiel-Icon nicht nur auf der Seite des Spiels, sondern auch in den Ergebnistabellen verwendet (siehe auch: [Zwischenergebnisseite](#zwischenergebnisseite) und [Endergebnisseite](#endergebnisseite)).

Im Ausgangszustand sieht das Publikum die Namen der Kandidatinnen und dahinter einen Strich:

![Allgemeine Spielergebnisseite (sofort aufdecken): Ausganszustand](images/022-allgemeine-spielergebnissseite-sofort-aufdecken-01.png)

In der Administrationsansicht wird eine Liste aller Kandidatinnen eingeblendet (wie erfasst gemäß [Konfiguration->Kandidatinnen verwalten](konfiguration.md#kandidatinnen-verwalten)). Mit einem Rechtsklick auf den Namen einer Kandidatin und einem Klick auf "Punkte eingeben" öffnet sich ein Eingabefenster. Nach der Eingabe der Punktzahl und Bestätigung wird diese Zahl sofort für das Publikum sichtbar:

![Allgemeine Spielergebnisseite (sofort aufdecken): Erste Punktzahl eingegeben](images/023-allgemeine-spielergebnissseite-sofort-aufdecken-02.png)

Weil die Punktevergabe auf dieser Seite ohnehin manuell vom Benutzer ausgeführt wird, muss sie -anders als bei Lautstärkemessung und Kirschen-Schätzspiel- _nicht_ noch gesondert bestätigt werden, um in die Ergebnistabelle übertragen zu werden. Aus dem gleichen Grund spielen auch die [Regeln für die automatische Punktevergabe](../technical/punktevergabe.md) hier keine Rolle.

## Allgemeine Spielergebnisseite (gesammelt aufdecken)

Die "Allgemeine Spielergebnisseite" kann genutzt werden, um die Ergebnisse von Spielen zu erfassen, die nicht über dieses Programm errechnet werden (also anders als bei Lautstärkemessung oder dem Kirschen-Schätzspiel).

Der Zusatz "gesammelt aufgecken" bedeutet, dass ins Programm eingegebene Ergebnisse bzw. Punktzahlen _erst nach Bestätigung_ für das Publikum sichtbar gemacht werden. Das ermöglicht es, die Ergebnisse eines Spiels für alle Kandidatinnen gleichzeitig sichtbar zu machen. Beim Kirschenmarkt wird dieser Seitentyp üblicherweise für das Telefonvoting verwendet.

Die Einstellungsmöglichkeiten sind identisch zur [Variante der Seite zum sofortigen Aufdecken](#allgemeine-spielergebnisseite-sofort-aufdecken):
Als Einstellungsmöglichkeiten bietet die Seite ein Eingabefeld für den Seitentitel und einen Auswahlfeld für das Spiel-Icon. Eine Änderung des Seitentitels muss über den Button "Konfiguration übernehmen" bestätigt werden, bevor sie für das Publikum sichtbar wird. Eine Änderung des Spiel-Icons hingegen wird sofort für das Publikum sichtbar. Als Spiel-Icon können lediglich die in der Auswahl verfügbaren Icons verwendet werden - die Verwendung einer eigenen Grafik (z.B. aus einer Datei) ist nicht möglich. Sofern in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) die entsprechende Einstellung gesetzt ist, wird das Spiel-Icon nicht nur auf der Seite des Spiels, sondern auch in den Ergebnistabellen verwendet (siehe auch: [Zwischenergebnisseite](#zwischenergebnisseite) und [Endergebnisseite](#endergebnisseite)).

Im Ausgangszustand sieht das Publikum die Namen der Kandidatinnen und dahinter einen Strich:

![Allgemeine Spielergebnisseite (gesammelt aufdecken): Ausganszustand](images/024-allgemeine-spielergebnissseite-gesammelt-aufdecken-01.png)

In der Administrationsansicht wird eine Liste aller Kandidatinnen eingeblendet (wie erfasst gemäß [Konfiguration->Kandidatinnen verwalten](konfiguration.md#kandidatinnen-verwalten)). Mit einem Rechtsklick auf den Namen einer Kandidatin und einem Klick auf "Punkte eingeben" öffnet sich ein Eingabefenster. Der Unterschied zur [Variante der Seite zum sofortigen Aufdecken](#allgemeine-spielergebnisseite-sofort-aufdecken): Nach der Eingabe der Punktzahl und Bestätigung wird diese Zahl _noch nicht_ für das Publikum sichtbar. Erst ein Klick auf den Button "Präsentationsansicht aktualisieren" macht das Ergebnis für das Publikum sichtbar:

![Allgemeine Spielergebnisseite (sofort aufdecken): Ergebnis freigeschaltet](images/025-allgemeine-spielergebnissseite-gesammelt-aufdecken-02.png)

Hierbei besteht ein weiterer (kleiner) Unterschied zur [Variante der Seite zum sofortigen Aufdecken](#allgemeine-spielergebnisseite-sofort-aufdecken): Diese Variante der Seite hier sortiert die Namen der Kandidatinnen bei Freischaltung des Ergebnisses gemäss der Rangfolge in diesem Spiel von oben (die meisten Punkte) nach unten (die wenigsten Punkte).

Weil die Punktevergabe auf dieser Seite ohnehin manuell vom Benutzer ausgeführt wird, muss sie -anders als bei Lautstärkemessung und Kirschen-Schätzspiel- _nicht_ noch gesondert bestätigt werden, um in die Ergebnistabelle übertragen zu werden. Aus dem gleichen Grund spielen auch die [Regeln für die automatische Punktevergabe](../technical/punktevergabe.md) hier keine Rolle.

## Diashow

Die Diashow seite zeigt -ihrem Namen entsprechend- wechselnde Bilder. Beim Kirschenmarkt wird dies genutzt, um Sponsoren-Logos einzublenden, teilweise auch um Impressionen bzw. Fotos aus der vergangenen Amtszeit der noch aktuellen Kirschenkönigin revuepassieren zu lassen.

Die Seite zeigt das in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) festgelegte Veranstaltungs-Logo und solange die Diashow pausiert ist auch immer das Hintergrundbild.

### Einstellungen

Die Seite erlaubt zunächst das Festlegen eines Seitentitels, eines Texts, der während pausierter Diashow angezeigt wird. Änderungen an diesen beiden Einstellungen müssen durch Klick auf "Konfiguration übernehmen" bestätigt werden, bevor sie übernommen werden.

![Diashow-Seite: Ausganszustand](images/026-diashow-01.png)

Die nachfolgend beschriebenen Einstellungen werden immer beim Starten der Diashow übernommen (also _nicht_ durch den Klick auf "Konfiguration übernehmen").

Die Diashow-Seite zeigt grundsätzlich immer die Bilder eines bestimmten [Bilder-Pools](konfiguration.md#bilder-laden) - folglich muss dieser ebenfalls als Teil der Einstellungen ausgewählt werden. Darüber hinaus lässt sich die Anzahl der Sekunden konfigurieren, nach der jeweils zum nächsten Bild gewechselt wird. Bei gesetztem Haken für die Option "Diashow beim Aufrufen der Seite automatisch starten" wird der auf dem vorherigen Screenshot abgebildete Pausen-Zustand (von dem die Diashow manuell gestartet werden kann) übersprungen und es geht sofort los mit dem ersten Bild. Was das erste Bild ist, bestimmt (egal ob manuell oder automatisch gestartet) die Option "Diashow mit einem zufälligen Bild starten". Wenn deaktiviert, beginnt die Abfolge der Bilder immer mit dem ersten Bild aus dem Bilderpool - bei gesetztem Haken hingegen startet sie mit einem zufällig ausgewählten. Dies ändert jedoch nur den Startpunkt der Abfolge - die Reihenfolge ist immer gleich und entspricht der der Bilder im Pool.

Ebenfalls konfiguriert werden kann ("Caption (Metadaten) anzeigen"), ob die beim Hinzufügen des Bildes ggfs. gespeicherten Metadaten angezeigt werden sollen und ob das Projekt-Hintergrundbild auch während der laufenden Diashow eingeblendet werden soll. Beide Optionen sind bei der Einblendung von Fotos tendenziell sinnvoll, für Sponsoren-Logos aber eher nicht:

![Diashow-Seite: Diashow mit problematischen Einstellungen](images/028-diashow-03.png)

Viele Logos werden leider nicht mit transparentem Hintergrund, sondern einem hellen Hintergrund zur Verfügung gestellt. Das sorgt dann dafür, dass das Logo nicht wie vor dem Hintergrund erscheint, sondern der Hintergrund nur irgendwo am Rande wie willkürlich platziert zu sehen ist. Bei der Einblendung von Caption/Metadaten wird eine leicht grauer, hauptsächlich Transparente Box vor dem Bild platziert, mit den entsprechenden Metadaten zum Bild darin. Während dies für Fotos sinnvoll sein kann, dürfte es beim Logo eines Sponsor eher unerwünscht sein: In den Metadaten sind dort keine relevanten Informationen enthalten (der Firmenname geht hoffentlich bereits aus dem Logo hervor, muss also nicht noch dazugeschrieben werden), und Datum sowie Beschreibung sind keine relevanten zusätzlichen Informationen. Im Gegenteil: Als Datum dürfte sich hier kaum ein sinnvoller Wert finden (während bei Fotos der Zeitpunkt der Erstellung für den Zuschauer interessant sein kann).

Werden die beiden genannten Optionen deaktiviert, wird während der Diashow nicht mehr als das jeweilige Bild selbst eingeblendet:

![Diashow-Seite: Laufende Diashow](images/027-diashow-02.png)

### Interaktion

Eine Diashow kann jederzeit gestartet oder pausiert werden. Dafür stehen die Buttons "Diashow starten", "Diashow pausieren" und "Diashow" beenden zur Verfügung. Während die Diashow bereits gestartet ist, ist der Button zum Starten logischerweise deaktiviert - analog dazu verhält es sich mit den anderen beiden Buttons.

Der Unterschied zwischen "pausieren" und "beenden" liegt darin, wo die Diashow fortgesetzt wird, falls sie wieder gestartet wird: Beim pausieren beginnt die Diashow mit dem nächsten in der Reihenfolge passenden Bild, beim Beenden beginnt die Diashow wieder mit dem ersten (oder je nach Einstellung -siehe oben- zufälligen Bild).

In der Administrationsansicht wird eine Liste aller Bilder im gewählten Pool angezeigt, die somit von der Diashow berücksichtigt werden. Mit einem Rechtsklick auf ein Bild und Klick auf "Bild präsentieren" kann sofort zum jeweiligen Bild gesprungen werden, ohne erst alle sonst davor gezeigten abzuwarten. Die Diashow wird anschliessend der Reihenfolge entsprechend ab dem jetzt "angesprungenen" Bild fortgesetzt.

## Webseite anzeigen

Diese Seite erlaubt das Anzeigen einer beliebigen Webseite. Dementsprechend gibt es als Einstellungsmöglichkeiten die Adresse der anzuzeigenden Webseite und den Seitentitel.

Beide Einstellungen erfordern die Bestätigung durch Klick auf "Konfiguration übernehmen". Wenn sich das Programm im Präsentationsmodus befindet, wird dann auch umgehend die entsprechende Webseite geladen.

![Webseite anzeigen](images/029-webseite-anzeigen.png)

Als Browser kommt "WebView2" zum Einsatz. Das entspricht, grob gesagt, dem Microsoft-Edge-Browser in der aktuell auf dem PC installierten Version.

Der Speicher des Browsers ist jedoch vom "normalen" Browser auf dem PC separiert. Das heisst, dass beispielsweise bei Webseiten, die einen Login erfordern, ein Login in Edge nicht ausreichend ist, sondern der Login auch in Kirschenkrönung separat erfolgen muss. Der Benutzer kann jedoch mit der angezeigten Webseite ganz normal interagieren, wie in jedem anderen Browserfenster auch. Auch die Anzeige von PDF-Dateien (siehe Screenshot) usw. ist möglich - alles, was im normalen Webbrowser geht, geht auch hier.

Die Seite zeigt das in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) festgelegte Veranstaltungs-Logo, nicht aber das Hintergrundbild an.

## Bild anzeigen

Diese Seite ermöglicht das Anzeigen eines einzelnen Bildes. Weil es hier nur um ein einzelnes Bild geht, muss dieses _nicht_ zuvor zum Teil eines Bilder-Pools gemacht werden.

![Einzelbild anzeigen](images/030-bild-anzeigen.png)

Dementsprechend überschaubar sind die Einstellungsmöglichkeiten dieser Seite: Über den entsprechend beschrifteten Button kann ein anzuzeigendes Bild ausgewählt werden, eine [Stretch-Option](../technical/stretch-optionen.md) für das Bild ausgewählt, ein Seitentitel eingegeben und die Anzeige des in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) festgelegten Hintergrundbilds aktiviert oder deaktiviert werden. Das ebenfalls in den Projekteinstellungen wählbare Veranstaltungs-Logo wird auf dieser Seite immer angezeigt. Die Auswahl eines anderen Bildes oder die Änderung des Seitentitels muss via "Konfiguration übernehmen"-Button bestätigt werden. Änderungen der Stretch-Option oder Ein-/Ausblenden des Hintergrundbilds werden ohne Bestätigung sofort wirksam.

## Zwischenergebnisseite

Der Zweck dieser Seite ist -wenig überraschend- die Anzeige des jeweils gerade aktuellen Zwischenstands in tabellarischer Form:

![Zwischenergebnistabelle nach einem Spiel](images/031-zwischenergebnisseite-01.png)

Spiele, die zum jeweiligen Zeitpunkt in der Veranstaltung noch nicht gespielt wurden, haben noch keine Spalte in der Tabelle. Diese wird erst erzeugt, sobald Ergebnisse vorliegen. So füllt sich diese Tabelle deshalb im Verlauf der Veranstaltung:

![Zwischenergebnistabelle später](images/032-zwischenergebnisseite-02.png)

Wenn in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) die Verwendung der Spiel-Icons deaktiviert oder auf die Seite des jeweiligen Spiels beschränkt ist, wird der Titel der Spielseiten statt dem Icon verwendet. Vor allem, wenn sich die Tabelle nach einigen Spielen füllt, wirkt dies jedoch unübersichtlich und wird deshalb nicht empfohlen:

![Zwischenergebnistabelle mit Text](images/033-zwischenergebnisseite-03.png)

In der für das Publikum nicht sichtbaren Administrationsansicht werden jedoch _immer_ Texte verwendet, niemals die Icons.

Die einzige Einstellung für diese Seite ist die Vergabe eines Titels (standardmäßig: "Zwischenstand"). Änderungen am Titel müssen mit "Konfiguration übernehmen" bestätigt werden.

Die Seite zeigt das in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) festgelegtes Veranstaltungs-Logo und Hintergrundbild an.

## Endergebnisübersicht

Die Endergebnisübersicht hat einen ähnlichen Zweck wie die [Zwischenergebnisseite](#zwischenergebnisseite) und zeigt die gleichen Informationen, wird jedoch am Ende der Veranstaltung aus dramaturgischen Zwecken bevorzugt, da sie über eine zusätzliche Funktion verfügt: Im Ausgangszustand zeigt die Seite zwar bereits alle Namen und Spiele an, jedoch noch keine Punktzahlen.

![Endergebnistabelle: Ausgangszustand](images/034-endergebnisuebersicht-01.png)

Mit einem Klick auf den Button "Zeile einblenden" in der Administrationsansicht werden jeweils die Punktzahlen einer weiteren Kandidatin eingeblendet. Die Summe bleibt dabei jedoch vorerst noch verdeckt!

![Endergebnistabelle: Erste Zeile aufgedeckt](images/035-endergebnisuebersicht-02.png)

Nachdem die Zeilen für alle Kandidatinnen eingeblendet wurden, stehen somit die Ergebnisse aller Spiele auf dem Bildschirm, noch nicht jedoch die Gesamtsummen.

![Endergebnistabelle: Beide Zeilen aufgedeckt](images/036-endergebnisuebersicht-03.png)

Die Gesamtsummen werden erst mit einem Klick auf "Summen anzeigen" eingeblendet. Bei Bedarf kann alternativ von jedem beliebigen Zwischenzustand mit einem Klick auf "ALLES anzeigen" zu diesem Zustand gesprungen werden:

![Endergebnistabelle: Alles aufgededeckt](images/037-endergebnisuebersicht-04.png)

Wie auch die Zwischenergebnisseite verwendet Endergebnisübersicht den Titel des Spiels in Textform, falls in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) die Verwendung der Spiel-Icons deaktiviert oder auf die Seite des jeweiligen Spiels beschränkt ist. Am Ende der Veranstaltung gilt jedoch erst recht, dass dies unübersichtlich wirkt und daher nicht empfohlen wird.

Die Seite zeigt das in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) festgelegtes Veranstaltungs-Logo und Hintergrundbild an.

## Endergebnisseite

Die Endergebnisseite hat keine konfigurierbaren Einstellungen und steht typischerweise am Ende der Veranstaltung. Sie zeigt automatisch eine Gratulation für die Siegerin bzw. neue Kirschenkönigin, basierend auf den zuvor ermittelten Punkten.

Die dabei angezeigten Informationen entsprechen denen, die zuvor im Menü [Konfiguration->Kandidatinnen verwalten](konfiguration.md#kandidatinnen-verwalten) erfasst wurden.

![Endergebnisseite: Siegerin steht fest](images/038-endergebnissseite-01.png)

Falls noch keine Siegerin gekürt werden kann, weil es zwei punktgleich Erstplatzierte gibt, zeigt die Seite statt Glückwünschen einen Hinweis auf die notwendige Verlängerung an:

![Endergebnisseite: Unentschieden](images/039-endergebnissseite-02.png)

Die Seite zeigt das in den [Projekteinstellungen](konfiguration.md#projekteinstellungen) festgelegtes Veranstaltungs-Logo und Hintergrundbild an.
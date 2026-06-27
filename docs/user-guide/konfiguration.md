# Konfiguration

## Begrifflichkeiten

Einige in dieser Dokumentation und im Programm immer wieder verwendete Begriffe sind im Kapitel [Begrifflichkeiten](../begrifflichkeiten.md) beschrieben und möglicherweise für das Verständnis hilfreich.

## Projekt erstellen/öffnen

Nach dem Programmstart muss zunächst für die entsprechende Veranstaltung ein neues Projekt erstellt oder ein bereits existierendes geöffnet werden. Dies geht über die Menüleiste am oberen Rand des Fensters: "Datei" > "Neu"/"Öffnen". In beiden Fällen muss ein Ordner angegeben werden, in dem die zugehörigen Dateien abgelegt werden, bzw. aus dem sie gelesen werden.

## Kandidatinnen verwalten

Eine essenzielle Information für den korrekten Ablauf der Wahl sind natürlich die Kandidatinnen. Das Menü zur Verwaltung der Kandidatinnen kann in der Menüleiste über "Kandidatinnen" > "Liste bearbeiten" geöffnet werden.

![Kandidatinnen verwalten](images/003-kandidatinnen-verwalten.png)

Solange das Programm sich nicht im Wahl- sondern im Vorbereitungsmodus befindet, können jederzeit Kandidatinnen hinzugefügt, bearbeitet und entfernt werden.

Während die Eingabefelder Name, Wohnort, Alter, Name des Prinzen vermutlich selbsterklärend sind, noch ein paar Anmerkungen zu den weiteren Feldern:

* Majestätischer Name: Gemeint ist der Name, den die Kandidatin im Falle ihrer Wahl als Kirschenkönigin tragen würde (sollte also dem Schema `{Vorname} {Römische Ziffer}.` folgen.). Diese Information wird auf der Endergebnisseite angezeigt.
* Name abgekürzt: Dabei handelt es sich meistens um den Vornamen, muss es aber nicht zwangsläufig. Dieser Name wird an den meisten Stellen im Programm verwendet, um eine Kandidatin zu referenzieren: Beispielsweise bei der tabellarischen Anzeige der (Zwischen-)ergebnissen. Eleganterweise sollte dies daher dem Namen entsprechen, mit dem auch der Moderator die Kandidatin anspricht.
* Profilbild: Dieses Bild wird bei der Vorstellung der Kandidatin und ggfs. nach ihrer Wahl auf der Endergebnisseite angezeigt. Über den Button "Bild auswählen" kann ein Bild ins Programm geladen werden.

Mit einem Klick auf "Hinzufügen" wird die Kandidatin der Liste hinzugefügt werden. Bestehende Kandidatinnen können via Rechtsklick (siehe Screenshot) bearbeitet oder entfernt werden.

## Projekteinstellungen

Für den im Programm hinterlegten Veranstaltungsablauf ("Projekt") können mehrere grundlegende Einstellungen getätigt werden. 

![Projekteinstellungen](images/004-projekteinstellungen.png)

Anhand des folgenden Screenshots lassen sich die meisten der verfügbaren Einstellungsoptionen zeigen:

![Projekteinstellungen](images/005-projekteinstellungen-praesentationsansicht-1.png)

* Generisches Hintergrundbild: Dieses wird, auf vielen Seiten im Hintergrund angezeigt. Manche Seiten verwenden jedoch ein individuell für diese Seite festzulegendes Bild - und manche Seiten zeigen widerum grundsätzlich keine Hintergrundbilder an. Über die entsprechenden Buttons kann ein (anderes) Bild festgelegt oder das Bild entfernt werden.
* Das Veranstaltungslogo wird auf den meisten Seiten oben rechts angezeigt. Über die entsprechenden Buttons kann ein (anderes) Bild festgelegt oder das Bild entfernt werden.
* Spiele können über Icons verfügen - dieses ist je nach Spiel fest vorgegeben oder kann aus einer Vorauswahl ausgewählt werden. (Das Laden eines beliebigen Spiel-Icons aus einer Datei wird derzeit nicht unterstützt.) Dazu gibt es die folgenden Optionen:
    * "Aktiviert" blendet die Spiel-Icons sowohl auf der Spiel-Seite, als auch in der tabellarischen (Zwischen-)Ergebnisseiten ein.
    * "Deaktiviert" zeigt die Spiel-Icons nirgendwo an. Der entsprechende Platz auf den Spiel-Seiten bleibt frei, in der (Zwischen-)ergebnistabelle wird der Name des Spiels textuell aufgeführt.
    * "Nur auf Ergebnisseite" zeigt das Spiel-Icon in (Zwischen-)ergebnistabellen an, aber nicht während dem Spiel selbst.
    * "Nur auf Spielseite" hingegen zeigt das Spiel-Icon genau umgekehrt während dem Spiel an, in den (Zwischen-)ergebnistabellen aber nicht und somit den textuellen Namen des jeweiligen Spiels stattdessen.
* Die Auswahl des für die Präsentationsansicht verwendeten Bildschirms legt fest, auf welchem Bildschirm die Präsentationsansicht beim Klick auf "Wahl starten" geöffnet wird. Da die gezeigten Bezeichnungen der Bildschirme etwas kryptisch sind, ist die pragmatische Vorgehensweise, sie schlicht durchzuprobieren, bis der bevorzugte Bildschirm gefunden ist. Weil sich die Präsentationansicht bei Auswahl des falschen Bildschirms vor die Administrations "drängelt" und somit den Button "Wahl beenden" verdeckt, mit dem sie wieder geschlossen werden kann, ist die Empfehlung in diesem Fall der folgende Workaround: Die Tastenkombination Alt+F4 verwenden, um das Fenster der Präsentationsansicht zu schließen und anschliessend mit Klick auf den "Wahl beenden" den Präsentationsmodus noch "richtig" verlassen.

## Bilder laden

Viele Bilder (z.B. wenn sie als Teil einer Diashow angezeigt werden) sind in sog. Bilder-Pools organisiert - sozusagen Fotoalben. Das Menü zur Verwaltung der Pools kann über die Menüleiste "Projekt" > "Bilder-Pools" geöffnet werden.

![Bilder-Pool hinzufügen](images/006-bilderpools-1.png)

Bevor Bilder in einen Pool geladen werden können, muss dieser zunächst erstellt werden. Dies lässt sich mit einem Klick auf den Button "Neuen Bilder-Pool erstellen", anschliessender Auswahl des Typs ("Projekt-Bilderpool"; in früheren Programmversionen existierten noch weitere Typen, aktuell ist dies jedoch der einzige wählbare), Eingabe eines Namens (dieser wird nirgendwo für das Publikum sichtbar angezeigt, sondern ist nur für den Bediener) und Klick auf "Bilder-Pool erstellen" bewerkstelligen.

Anschliessend kann der neu erstellte Pool in der Pool-Auswahl ausgewählt und bearbeitet werden.

![Bilder-Pool bearbeiten](images/007-bilderpools-2.png)

Nach der Auswahl eines Pools zeigt die Bild-Auswahl eine Liste _aller_ bereits in das Programm geladenen Bilder (also z.B. auch in den Projekteinstellungen als Hintergrundbild oder Logo festgelegte Bilder, Profilbilder der Kandidatinnen, usw.). Über den Button "Neues Bild hinzufügen" kann ein neues Bild hinzugefügt werden.

Nach der Auswahl einer Bilddatei öffnet sich ein neuer Dialog, um Zusatzinformationen zum Bild einzugeben. Dieser Schritt kann übersprungen werden ("Ohne Metadaten fortfahren"), die Eingabe wird jedoch empfohlen: Je nach Einstellungen der entsprechenden Seite _können_ diese Metadaten zusammen mit dem Bild dem Publikum angezeigt werden. In jedem Fall aber erleichtert insbesondere der vergebene Titel das spätere Wiederfinden des Bildes in der Liste aller Bilder (falls kein Titel vergeben wird, erscheint dort nur die ID, also fortlaufende Nummer, des Bildes). Ein Klick auf "Metadaten speichern" speichert Bild sowie Metadaten und schliesst das Dialogfenster.

Achtung: Mit dem Laden eines Bildes ist dieses jedoch noch nicht automatisch Teil eines Bilder-Pools! Das Bild ist jetzt dem Programm sozusagen bekannt und taucht in der Liste der verfügbaren Bilder auf, muss jetzt allerdings erst noch durch das Setzen eines Hakens vor dem betreffenden Bild dem entsprechenden Pool zugeordnet werden. (Bilder können auch Teil von mehreren Pools sein, das ist kein Problem.) Nachdem für alle gewünschten Bilder ein Haken gesetzt (oder ggfs. wieder entfernt) worden ist, müssen die Änderungen schliesslich noch über den Button "Änderungen am Bilder-Pool speichern" bestätigt werden.

Wird die Maus über einen Eintrag in der Bild-Auswahl bewegt, wird das betreffende Bild rechts als Vorschau angezeigt. Diese Funktion dient lediglich dem einfacheren Identifizieren von Bildern, insbesondere falls für diese kein Titel festgelegt wurde.

Ein Bilder-Pool kann über den Button "Bilder-Pool löschen" natürlich auch wieder gelöscht werden (aber Achtung: falls eine Seite im Veranstaltungsablauf die Bilder des Bilder-Pools verwendet, wird diese anschliessend nicht mehr funktionieren).

Etwas erklärungsbedürftig ist schliesslich noch die Auswahloption "Der Bilder-Pool besteht _nur aus den ausgewählten Bildern._" bzw. "Der Bilder-Pool besteht _aus allen verfügbaren außer den ausgewählten Bildern._". Die Einstellung kann in den meisten Fällen einfach ignoriert werden - bei Auswahl der zweiten Option wird die Auswahl-Logik umgekehrt und es sind anschliessend alle Bilder, für die KEIN Haken gesetzt wurde, Teil des Bilder-Pools. Der Ursprung dieser Einstellung liegt in anderen Typen von Bilder-Pools, die in früheren Programmversionen vorhanden waren und ggfs. dynamisch ihren Inhalt verändern konnten (so dass hier dann sozusagen eine "Sperrung" von Bildern möglich war).

## Ablauf konfigurieren

Der grösste Teil der Vorbereitung ist die Konfiguration des hinterlegten Wahlablaufs.

![Überblick Administrationsansicht](images/008-administrationsansicht-ueberblick.png)

Auf der linken Seite der Administrationsansicht ist der geplante Wahlablauf, bzw. die Abfolge der einzelnen Seiten zu sehen. Um eine Seite hinzuzufügen, kann einfach die gewünschte Seite aus der Liste der verfügbaren neuen Seiten (oben rechts) an die passende Stelle in den Wahlablauf gezogen werden.

Die meisten Seiten können über diverse Einstellungen angepasst werden bzw. erlauben Steuerung/Interaktion während der Veranstaltung. Beides befindet sich für die gerade ausgewählte (also nach Anklicken blau hinterlegte) Seite im Bereich unten rechts.

Seiten können auch innerhalb des Wahlablaufs beliebig verschoben werden. Das Entfernen ist über einen Rechtsklick auf die betreffende Seite und anschliessenden Klick auf "Entfernen" möglich.

Eine detaillierte Übersicht über die einzelnen Seitentypen und ihre Konfigurationsoptionen liefert das Kapitel [Konfiguration einzelner Seiten](konfiguration-einzelseiten.md).

## Lautstärkemessung vorbereiten

Um die Lautstärkemessung vorzubereiten, sollte zunächst eine Kalibrierung ausgeführt werden und anschliessend eine Testmessung ausgeführt werden.

Das entsprechende Menü kann über die Menüleiste "Plugins" > "Lautstärkemessung" > "Einstellungen" geöffnet werden.

![Einstellungen der Lautstärkemessung](images/009-einstellungen-lautstärkemessung.png)

Der Kalibrierungs-Assistent, der Schrittweise durch die Mikrofonkalibrierung führt, kann über den Button "Kalibrierungs-Assistent starten" erreicht werden. Der Button "Kalibrierung zurücksetzen" löscht die bei der Kalibrierung ermittelten Korrekturfaktoren für _alle_ Mikrofone bzw. Signalquellen.

Eine Test-Messung kann, nachdem in der Auflistung der verfügbaren Mikrofone darüber das/die gewünschte(n) Mikrofon(e) bzw. Signalquelle(n) durch das Setzen eines Hakens ausgewählt wurde(n), über den Button "Test-Messung ausführen" direkt gestartet werden. Wichtig: Die hier getroffene Auswahl der Mikrofone bzw. Signalquellen gilt nicht nur für die Testmessung, sondern wird für alle Messungen verwendet, auch die "richtigen" während der Veranstaltung!

Der Ablauf der Kalibrierung ist detailliert beschrieben im Kapitel [Kalibrierung](konfiguration-kalibrierung.md).

# Installation

Dieses Kapitel gibt einen Überblick über die erforderlichen Schritte, die vor dem Start der Software ausgeführt werden müssen.

## Systemanforderungen

Die durch die Software gestellten Systemanforderungen sind moderat und sollten durch aktuelle, handelsübliche Laptops erfüllt werden. Dennoch nachfolgend auch einige Anmerkungen zu Erfahrungen aus der Praxis.

### Grundfunktionen

Die Erstversion der Software wurde mit der folgenden Systemkonfiguration mehrfach problemlos eingesetzt:

* 8 GB RAM oder mehr
* Dual-Core-CPU mit 1,9 GHz oder schneller (vgl. Intel Core i5-4300U)

Im Laufe der Zeit wurden jedoch zusätzliche Features implementiert, welche Einfluss auf die Systemanforderungen haben könnten. Die Empfehlung, basierend auf der zuletzt verwendeten Systemkonfiguration, wäre daher eher diese:

* 32 GB RAM oder mehr
* Hexa-Core-CPU mit 2,6 GHz oder schneller (vgl. Intel Core i7-9850H)
* Windows 11 25H2

### Präsentation

Während der Präsentationsphase, also der eigentlichen Veranstaltung, werden mehrere Bildschirme benötigt:

* 2 Bildschirme (Laptop: Laptopbildschirm + 1 zusätzlicher Bildschirm)
* Für den Bediener sollten jedoch beide Bildschirme einsehbar sein, um die Bedienung zu erleichtern. Abhängig von den konkreten Räumlichkeiten kann ein dritter Bildschirm daher sinnvoll sein.
* Die ersatzweise Verwendung eines iPads (via "[Duet Display](https://www.duetdisplay.com/)") als Bildschirm hat sich als unproblematisch erwiesen.

### Lautstärkemessung

* Für Lautstärkemessung: mindestens 1 Mikrofon
* Je nach Anforderungen an die Messung wird die Verwendung mehrerer (2 oder mehr) gleichmäßig verteilter und ausgerichteter Mikrofone empfohlen, entweder separat oder über ein mehrkanaliges XLR-Interface mit dem PC verbunden, via USB 3.0 oder höher
* In der Praxis bewährt hat sich die Verwendung von Messmikrofonen, verbunden über ein Scarlett 6i6-Audiointerface
* WICHTIG: Falls die Signale mehrerer Mikrofone gleichzeitig verarbeitet werden sollen, müssen diese unbedingt über die gleiche Abtastrate verfügen! Ansonsten können die Signale nicht korrekt synchronisiert und damit auch nicht korrekt kombiniert werden.
* Die Mikrofone sollten zudem auch über eine mindestens ähnliche Charakteristik (Frequenzgang so linear wie möglich und geeignet für die erwartete Grössenordnung von Schalldruckpegel) verfügen, da auch die im Programm verfügbare Kalibrierungsfunktion physikalische Grenzen nicht überwinden kann

> ⚠️ Achtung: Nicht jedes Mikrofon hat eine geeignete Charakteristik! Keinesfalls geeignet sind z.B. im Laptop enthaltene Mikrofone!

> ⚠️ Sämtliche von Windows oder Drittanbieternsoftware bereitgestellte Softwarefunktionen zur automatischen Pegelkompensation, Rauschunterdrückung, "Audioverbesserungen" o.Ä. müssen unbedingt deaktiviert werden, da sie die Messungen unbrauchbar machen!

> ℹ️ Weitere Informationen zur Vorbereitung für Lautstärkemessungen und technische Hintergründe finden sich auf den Seiten LINK FOLGT und LINK FOLGT

### Zusatzfunktionen

* Einbetten von Webseiten: Stabile, schnelle Internetverbindung

## Eigentliche Installation

Grundsätzlich ist eine Installation zur Ausführung von Kirschenkrönung nicht zwingend nötig: Ein Klick auf die Datei `Launcher4711.exe` reicht, und die Software startet. Aus Gründen der Bequemlichkeit wird eine Installation dennoch empfohlen.

Das Installationsprogramm kann unter folgender Adresse heruntergeladen werden: [https://go.studio-4711.com/kk-download](https://go.studio-4711.com/kk-download)

![Installationsprogramm](images/001-installer.png)

Das Installationsprogramm entpackt alle für die Ausführung benötigten Datein in das Verzeichnis `%localappdata%\Kirschenkroenung\App`, legt eine Desktop-Verknüpfung an und startet das Programm. Administratorrechte werden _nicht_ benötigt.

Bei jedem Programmstart wird automatisch geprüft, ob es eine aktuellere Programmversion gibt. Falls ja, wird das Update automatisch heruntergeladen und installiert, bevor das Programm gestartet wird (sofern dieser Prozess nicht vom Benutzer abgebrochen bzw. übersprungen wird.)

## Zusatzprogramme

In vielen Fällen wird für die Verwendung der Mikrofone (zwecks Lautstärkemessung) die Installation von zusätzlicher Software vom jeweiligen Hersteller benötigt. Dies gilt insbesondere, wenn es sich dabei um "Spezialhardware" gilt, die nicht per USB angeschlossen wird.

Ohne die passende Software kann es sein, dass Kirschenkrönung die Mikrofone nicht gar nicht erst sehen kann oder nicht korrekt mit ihnen kommunizieren kann. Auskunft über etwaige nötige Zusatzsoftware gibt die Anleitung der Hardware bzw. die Webseite des jeweiligen Herstellers.

## Mikrofonkonfiguration

Wie oben bereits erwähnt, ist es wichtig, dass sämtliche von Windows oder Drittanbieternsoftware bereitgestellte Softwarefunktionen zur automatischen Pegelkompensation, Rauschunterdrückung, "Audioverbesserungen" o.Ä. unbedingt deaktiviert werden! Diese verfälschen andernfalls die Messungen oder machen sie komplett unbrauchbar, weil dabei Teile der Audiosignale verstärkt oder abgeschwächt werden.

Unter Windows 11 findet sich entsprechende Einstellungen unter "Einstellungen" > "System" > "Sound" > "Mikrofon" (der Eintrag unter "Eingabe" für das betreffende Mikrofon) > "Audioverbesserungen".

Darüber hinaus sollte die Lautstärke/Empfindlichkeit des Mikrofons auf 100% eingestellt werden (im zuvor bereits erwähnten Einstellungsmenü unter "Einganslautstärke").

![Windows Audioeinstellungen](images/002-windows-audioeinstellungen.png)

Es ist jedoch möglich, dass in weiteren Programmen, insbesondere falls für die Verwendung der Mikrofone Zusatzsoftware installiert worden ist, ähnliche Funktionen vorhanden sind, die ebenfalls deaktiviert werden müssen!
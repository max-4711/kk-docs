# Häufige Fragen und Antworten (FAQs)

## Deinstallation / Zurücksetzen

Das Programm bei der Installation entpackt in das Verzeichnis `%localappdata%\Kirschenkroenung\`. Alle Dateien, die das Programm selbst im Hintergrund erzeugt, werden in das Verzeichnis `%appdata%\Kirschenkroenung\` abgelegt. Durch das Löschen dieser beiden Verzeichnisse sowie der bei der Installation auf dem Desktop angelegten Verknüpfung wird das Programm restlos deinstalliert.

## Kann ein Projekt für das nächste Jahr kopiert und wiederverwendet werden?

Technisch ist das grundsätzlich möglich, allerdings ist es bislang noch nie getestet worden. 

Weil aus dem Projektordner keine Dateien (wie Bilder) gelöscht werden, auch wenn sie im konfigurierten Veranstaltungsablauf nicht mehr verwendet werden, würde sich der Projektordner unweigerlich mehr und mehr aufblähen.

Aus diesem Grund lautet die Empfehlung daher, den Veranstaltungsablauf lieber wieder "von vorne" zu konfigurieren. Möglich wäre ansonsten aber evtl. eine Art "Template" zu erstellen und von diesem für jedes Jahr eine Kopie zu erstellen.

## Die Installation eines Updates schlägt immer wieder fehl, bzw. nach der Installation erscheint statt der neuen Programmversion eine Fehlermeldung

Im ersten Schritt prüfen, ob im Installationsverzeichnis (also typischerweise `%localappdata%\Kirschenkroenung\App`) ein Ordner `Updatetemp` existiert. 

Wenn ja, den gesamten Inhalt bis auf diesen Ordner löschen und den Inhalt aus dem `Updatetemp`-Ordner eine Ebene nach oben schieben, also dorthin, wo eben die anderen Dateien gelöscht wurden.

Wenn nein, hier prüfen, ob es einen neuen kompletten Installer zum Download gibt.

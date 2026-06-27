# Stretch-Optionen

An vielen Stellen im Programm kann, wenn es um die Anzeige von Bildern geht, eine als "Stretch-Option" bezeichnete Auswahl getroffen werden.

Diese bestimmt, wie das Bild in die auf dem Bildschirm verfügbare Fläche "eingepasst" wird. Die nachfolgenden Optionen stehen zur Verfügung:

## None

![Stretch "None"](images/001-stretch-none.png)

Das Bild wird ohne jegliche Veränderungen an der Grösse eingefügt - egal, wie gross die zur Anzeige verfügbare Fläche ist.

## Fill

![Stretch "Fill"](images/002-stretch-fill.png)

Das Bild wird so "gedehnt" bzw. verzerrt, bis es die verfügbare Fläche komplett ausfüllt. Je nach Seitenverhältnis des Bildes und der Fläche kann dies eine stärkere oder schwächere Verzerrung zur Folge haben.

Diese Option ist typischerweise nicht die gewünschte.

## Uniform

![Stretch "Uniform"](images/003-stretch-uniform.png)

Dabei wird das Bild vergrössert (oder verkleinert), bis die zur Anzeige verfügbare Höhe _oder_ Breite voll ausgeschöpft ist. Das Bild wird dabei nicht verzerrt, sein originales Seitenverhältnis bleibt erhalten. Entweder neben oder über/unter dem Bild bleibt deshalb im Regelfall Anzeigefläche leer.

## UniformToFill

![Stretch "UniformToFill"](images/004-stretch-uniformtofill.png)

Dabei wird das Bild vergrössert (oder verkleinert), bis die zur Anzeige verfügbare Höhe _und_ Breite voll ausgeschöpft sind. Das Bild wird dabei nicht verzerrt, sein originales Seitenverhältnis bleibt erhalten. Statt dass Anzeigefläche leer bleibt (wie bei "Uniform"), wird hierbei meistens ein Teil des Bildes abgeschnitten.
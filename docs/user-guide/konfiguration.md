# Konfiguration

## Projekt erstellen/öffnen

Nach dem Programmstart muss zunächst für die entsprechende Veranstaltung ein neues Projekt erstellt oder ein bereits existierendes geöffnet werden. In beiden Fällen muss ein Ordner angegeben werden, in dem die zugehörigen Dateien abgelegt werden, bzw. aus dem sie gelesen werden.

## Ablauf 

## Beispielstruktur

### Option `example.enabled`

- **Typ:** `boolean`
- **Default:** `false`
- **Pflicht:** nein

Aktiviert die Beispiel-Funktion.

```yaml
example:
  enabled: true
```

### Option `example.endpoint`

- **Typ:** `string`
- **Default:** kein Wert
- **Pflicht:** ja, wenn `example.enabled = true`

Definiert den Zielendpunkt fuer die Beispiel-Funktion.

## Pflegehinweise

- Jede Option sollte Typ, Default und Seiteneffekte dokumentieren.
- Konfigurationen mit Abhaengigkeiten sollten diese direkt auf der Seite benennen.

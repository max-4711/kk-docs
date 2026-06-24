# Konfiguration

Diese Seite dient als Vorlage fuer benutzerrelevante Konfiguration.

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

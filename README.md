# Kirschenkroenung Dokumentation

Dieses Repository enthaelt die Dokumentation fuer die Software Kirschenkroenung.
Die Inhalte werden in Markdown gepflegt und mit MkDocs Material als statische HTML-Seiten gebaut und ueber GitHub Pages veroeffentlicht.

## Struktur

- `docs/`: Inhalt der Dokumentation
- `.github/workflows/docs.yml`: CI/CD fuer Build und Deployment
- `mkdocs.yml`: Navigations- und Build-Konfiguration
- `requirements.txt`: Python-Abhaengigkeiten fuer lokale Vorschau und CI

## Lokal starten

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
mkdocs serve
```

Die Vorschau ist anschliessend unter `http://127.0.0.1:8000/` erreichbar.

## Statischen Build erzeugen

```powershell
mkdocs build
```

Das Ergebnis liegt danach im Verzeichnis `site/`.

## Deployment

Pushes und Pull Requests bauen die Dokumentation in GitHub Actions.
Pushes auf `main` deployen zusaetzlich nach GitHub Pages.

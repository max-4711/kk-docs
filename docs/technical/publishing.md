# Veröffentlichungsprozess

Die Dokumentation wird lokal mit MkDocs gebaut und in GitHub Actions validiert und veröffentlicht.

## Lokal prüfen

```powershell
python -m venv .venv
.venv\Scripts\Activate.ps1
pip install -r requirements.txt
mkdocs build --strict
```

## CI/CD

- Pull Requests und Pushes bauen die Dokumentation als Validierung.
- Pushes auf `main` veröffentlichen den statischen Build nach GitHub Pages.

## Hinweise zu GitHub Pages

Im Repository muss GitHub Pages so konfiguriert sein, dass die Quelle **GitHub Actions** ist.

# AGENTS.md — Demo Interactiv

Proiect static: un `index.html`, fără npm.

## Verificare

1. Introdu un nume → salutul se actualizează.
2. **+1** / **−** / **Reset** → contor și istoric.
3. La 10, 20… apăsări → confetti.
4. **Copiază** → text în clipboard.
5. Reîncarcă pagina → datele rămân (`localStorage`).
6. **Exportă** → descarcă fișier `.json`; **Importă** → restaurează starea.
7. PWA: `manifest.json` + `sw.js` — instalabil / cache offline (HTTPS).

## Rulare locală

```bash
python3 -m http.server 8080
```

## Deploy

GitLab CI → `public/`; GitHub Pages din `main`.

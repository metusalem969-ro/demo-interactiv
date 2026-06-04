# AGENTS.md

## Cursor Cloud — Exemplu Web

Proiect static minimal: un singur `index.html`, fără package manager.

### Rulare locală

```bash
python3 -m http.server 8080
```

### Verificare

1. Click pe **Apasă aici** → contorul crește.
2. Schimbă tema (cercurile colorate) → accentul paginii se actualizează.

### Deploy

- GitLab CI (`.gitlab-ci.yml`) copiază `index.html` în `public/` pentru Pages.
- GitHub Pages: branch `main`, root `/`.

# Exemplu Web

Pagină web statică exemplu — creată cap-coadă cu Cursor Cloud Agent pe **GitHub** și **GitLab**.

## Ce face pagina

- Contor la click pe buton
- 4 teme de culoare
- Un singur fișier `index.html` (fără npm, fără backend)

## Linkuri site (după deploy)

| Platformă | URL |
|-----------|-----|
| **GitHub Pages** | https://metusalem969-ro.github.io/exemplu-web/ |
| **GitLab Pages** | *(vezi Settings → Pages după primul pipeline pe `main`)* |

## Repository

| Platformă | Link |
|-----------|------|
| **GitHub** | https://github.com/metusalem969-ro/exemplu-web |
| **GitLab** | https://gitlab.com/Hercules-metusalem969/exemplu-web |

## Structură proiect

```
exemplu-web/
├── index.html       # pagina web
├── README.md        # acest fișier
├── .gitlab-ci.yml   # deploy GitLab Pages
├── .nojekyll        # necesar pentru GitHub Pages
└── AGENTS.md        # ghid pentru agenți Cursor
```

## Deploy

- **GitLab**: push pe `main` → job CI `pages` publică în `public/`
- **GitHub**: Settings → Pages → branch `main`, folder `/ (root)`

## Dezvoltare locală

```bash
python3 -m http.server 8080
```

Deschide http://127.0.0.1:8080/

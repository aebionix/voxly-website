# CLAUDE.md - voxly-website

## Voxly Projekt-Struktur (WICHTIG!)

**Voxly besteht aus drei separaten Repositories/Verzeichnissen:**

| Verzeichnis | Zweck | GitHub Repo | Zugriff |
|-------------|-------|-------------|---------|
| **X:\Wisper** | Source Code, Development | github.com/aebionix/Wisper | Privat |
| **X:\voxly-releases** | Releases, update-info.json | github.com/aebionix/voxly-releases | Öffentlich |
| **X:\voxly-website** | Website (index.html) | github.com/aebionix/voxly-website | Öffentlich |

## Dieses Repo (voxly-website)

**Zweck:** Öffentliche Website für Voxly (voxly.ch)

**Inhalt:**
- `index.html` - Hauptseite (Single-Page)
- `favicon.svg` - Logo

**Premium-Features aktualisieren:**

Wenn neue Premium-Features hinzugefügt werden, die Premium Edition Liste in `index.html` aktualisieren:

```html
<!-- Zeile ~1168: Premium Edition Features -->
<li>
    <svg class="check" ...></svg>
    <strong>Feature-Name</strong>
</li>
```

**Deployment:**

Website wird via GitHub Pages gehostet:
- Push zu `main` Branch → Automatisches Deployment
- URL: https://voxly.ch (oder GitHub Pages URL)

## Andere Repos

- **Source Code:** `X:\Wisper`
- **Releases:** `X:\voxly-releases`

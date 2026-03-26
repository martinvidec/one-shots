# One-Shots — Projektkontext

## Was ist dieses Repo?

Sammlung von Webseiten, die jeweils in einem einzigen Prompt erstellt werden. Jeder One-Shot lebt in seinem eigenen Ordner.

## Ordnerstruktur

Jeder One-Shot bekommt einen eigenen Ordner im Root:
```
<name>/
├── PROMPT.md      # Der Original-Prompt
└── index.html     # Das Ergebnis (+ ggf. Assets)
```

## Regeln für One-Shots

- **Keine externen Dependencies** außer Google Fonts oder vergleichbare CDN-Ressourcen
- **Kein Build-Step** — alles muss direkt im Browser lauffähig sein
- **Ein Prompt, ein Ergebnis** — kein iteratives Nachbessern im selben One-Shot
- **State-of-the-Art** — moderne CSS-Features (Container Queries, View Transitions, Scroll-Driven Animations), modernes JS (Intersection Observer, Web Animations API etc.)
- **Responsive und barrierefrei** — `prefers-reduced-motion`, semantisches HTML, ARIA wo nötig
- **Sprache**: Prompts und Inhalte können deutsch oder englisch sein

## Beim Anlegen eines neuen One-Shots

1. Ordner im Root erstellen (kebab-case, beschreibender Name)
2. `PROMPT.md` mit dem verwendeten Prompt anlegen
3. Ergebnis als `index.html` (+ Assets falls nötig) ablegen
4. `README.md` im Root aktualisieren — neue Zeile in der Beispiel-Tabelle mit:
   - Laufende Nummer
   - Link zum Ordner: `` [`name/`](./name) ``
   - Live-Link als voller URL (kein Linktext): `https://martinvidec.github.io/one-shots/<name>/`
   - Der verwendete Prompt als Text (nicht die Beschreibung)
5. Committen und auf `main` pushen — GitHub Pages deployt automatisch via `.github/workflows/pages.yml`

## GitHub Pages

- Pages ist aktiviert auf `main` Branch, Root `/`
- Deploy läuft automatisch per GitHub Actions bei jedem Push auf `main`
- Jeder One-Shot ist direkt erreichbar unter: `https://martinvidec.github.io/one-shots/<ordnername>/`
- Nach dem Push dauert es ca. 1-2 Minuten bis die Seite live ist

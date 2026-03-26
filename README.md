# One-Shots

Sammlung von Webseiten, die in einem einzigen Prompt erstellt wurden — kein Framework-Setup, kein Build-Step, kein Nachbessern. Jeder One-Shot ist eine eigenständige, produktionsreife Webseite aus purem HTML, CSS und JavaScript.

## Konzept

Ein Prompt rein, eine fertige Webseite raus. Das Ziel ist es zu zeigen, was mit einem einzelnen, gut formulierten Prompt möglich ist — State-of-the-Art clientseitiges Web ohne Abhängigkeiten.

## Beispiele

| # | Ordner | Live | Prompt |
|---|--------|------|--------|
| 1 | [`portfolio/`](./portfolio) | https://martinvidec.github.io/one-shots/portfolio/ | Erstelle bitte eine Portfoliowebseite für einen Webdesigner. Verwende state-of-the-art clientside JS, CSS und HTML. |
| 2 | [`apple-narrative/`](./apple-narrative) | https://martinvidec.github.io/one-shots/apple-narrative/ | Baue eine Apple like Website mit narrative scrolling und 3D oder pseudo 3D Effekten. |
| 3 | [`racing-driver/`](./racing-driver) | https://martinvidec.github.io/one-shots/racing-driver/ | Baue diese Seite nach: https://charlesleclerc.com/en/ . Verwende Bilder von Unsplash, falls du Platzhalter brauchst. |

## Struktur

```
one-shots/
├── README.md
├── CLAUDE.md
├── portfolio/
│   ├── PROMPT.md          # Der verwendete Prompt
│   └── index.html         # Das Ergebnis
├── beispiel-2/
│   ├── PROMPT.md
│   └── index.html
└── ...
```

Jeder Ordner enthält:
- **`PROMPT.md`** — Der exakte Prompt, der zur Erstellung verwendet wurde
- **`index.html`** — Das unveränderte Ergebnis (ggf. weitere Assets)

## Lokal ansehen

Einfach die `index.html` im Browser öffnen — kein Server nötig.

## Lizenz

MIT

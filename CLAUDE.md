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
4. `README.md` im Root aktualisieren (Tabelle der Beispiele)

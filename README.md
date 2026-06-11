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
| 4 | [`data-science-fractal/`](./data-science-fractal) | https://martinvidec.github.io/one-shots/data-science-fractal/ | Baue eine Websiteportfolio für einen Data-Science Researcher. Verwende ein Fraktal als Hintergrund, das live berechnet wird und in das während des Scrollens immer tiefer eingetaucht wird. Betreibe Research um eine geeignete JS Bibliothek dafür zu finden (z.B. processing.js). Vermeide AI-slop Farbpaletten! |
| 5 | [`ai-assistant/`](./ai-assistant) | https://martinvidec.github.io/one-shots/ai-assistant/ | Erstelle eine AI-Assistant Site und verwende dabei den Halo Effekt von https://github.com/tengbao/vanta |
| 6 | [`portfolio-fable5-high/`](./portfolio-fable5-high) | https://martinvidec.github.io/one-shots/portfolio-fable5-high/ | Erstelle bitte eine Portfoliowebseite für einen Webdesigner. Verwende state-of-the-art clientside JS, CSS und HTML. |
| 7 | [`apple-narrative-fable5-high/`](./apple-narrative-fable5-high) | https://martinvidec.github.io/one-shots/apple-narrative-fable5-high/ | Baue eine Apple like Website mit narrative scrolling und 3D oder pseudo 3D Effekten. |
| 8 | [`racing-driver-fable5-high/`](./racing-driver-fable5-high) | https://martinvidec.github.io/one-shots/racing-driver-fable5-high/ | Baue diese Seite nach: https://charlesleclerc.com/en/ . Verwende Bilder von Unsplash, falls du Platzhalter brauchst. |
| 9 | [`data-science-fractal-fable5-high/`](./data-science-fractal-fable5-high) | https://martinvidec.github.io/one-shots/data-science-fractal-fable5-high/ | Baue eine Websiteportfolio für einen Data-Science Researcher. Verwende ein Fraktal als Hintergrund, das live berechnet wird und in das während des Scrollens immer tiefer eingetaucht wird. Betreibe Research um eine geeignete JS Bibliothek dafür zu finden (z.B. processing.js). Vermeide AI-slop Farbpaletten! |
| 10 | [`ai-assistant-fable5-high/`](./ai-assistant-fable5-high) | https://martinvidec.github.io/one-shots/ai-assistant-fable5-high/ | Erstelle eine AI-Assistant Site und verwende dabei den Halo Effekt von https://github.com/tengbao/vanta |

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

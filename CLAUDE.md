# CLAUDE.md — nantu-website

Führe `/prime` zum Sessionstart aus.

## Kontext aus dem Workspace lesen

Lies zuerst diese Dateien aus dem parallelen Workspace:
- `../claude-nantu-starter-workspace/reference/design-guidelines.md`
- `../claude-nantu-starter-workspace/reference/ci-guidelines.md`
- `../claude-nantu-starter-workspace/reference/ci-application-guide.md`
- `../claude-nantu-starter-workspace/context/business-info.md`
- `../claude-nantu-starter-workspace/context/strategy.md`

## Projekt

nantu.net — Hauptwebsite von nantu.

## Tech Stack

- **Framework:** Next.js 16 (App Router) · TypeScript
- **Styling:** Tailwind CSS v4 (nantu CI-Farben in globals.css definiert)
- **Fonts:** Nunito (Display/Headlines) + Open Sans (Body) via next/font/google
- **Deploy:** Vercel oder eigener VPS

## CI-Farben (als Tailwind-Klassen verfügbar)

```
bg-beech-green    #8DBF38   Herzfarbe, CTA, .net
bg-forest-green   #4A7A30   Waldgrün, tief
bg-moss-green     #6A8A3E   Übergänge
bg-earth-brown    #7A5535   Wärme
bg-dark-earth     #2E1D0E   Fundament, Primärtext
bg-parchment      #F5F0E8   Hintergrund (statt Weiß!)
bg-morning-gold   #D4A843   Licht, goldene Akzente
bg-spring-light   #C8DDA8   Licht durch Blätter
bg-sky-far        #A8C8DC   Geistiges (immer dezent)
bg-bark           #8B6240   Rinde, warme Mitte
bg-humus          #4A3020   Tiefe Erde
bg-mist-green     #E8F0D8   Atmosphärisch hell
bg-milk-white     #FAF8F2   Hellster Hintergrund
```

## Regeln

- Hintergrund immer `parchment` (#F5F0E8), nie reines Weiß
- Kein border-radius: 0 bei sichtbaren Elementen
- Blautöne (sky-far) nur als ferner Akzent — nie dominant
- Organische Formensprache: Blätter, Erdwellen, Lichtflecken
- font-display für Headlines (Nunito), font-body für Fließtext (Open Sans)

# 🎬 LTX Prompt Builder

**Crea prompt per LTX-Video con solo click — zero tastiera.**

> A zero-keyboard prompt builder for [LTX-Video](https://github.com/Lightricks/LTX-Video) (v2.3). Pick options, get a ready-to-use prompt.

🔗 **[→ Apri l'app](https://TUO-USERNAME.github.io/ltx-prompt-builder)**

---

## ✨ Features

- **⬡ Costruttore** — 6 sezioni guidate: inquadratura, ambientazione, azione, personaggi, camera, audio
- **⚄ Shuffle** — genera combinazioni casuali con un click, copia istantanea
- **↓ Importa** — incolla un prompt esistente e genera 5 varianti automatiche
- **IT / EN** — interfaccia completamente bilingue (il prompt è sempre in inglese)
- **Formato corretto** — ogni riga = un clip, un solo punto finale, commenti con `#`
- **Zero dipendenze** — singolo file HTML, nessun server, funziona offline

## 📋 Formato output

```
Wide establishing shot - Cinematic - Film noir
Neon glow
Urban street
Night time
Fog
# Slow motion
The shot opens on a lone figure
Someone walks slowly into frame
The camera pushes in
Sound: City noise
"Wait...".
```

Ogni riga diventa un video separato nel tuo pipeline LTX-Video.

## 🚀 Deploy su GitHub Pages

1. Fork o upload di questo repo
2. **Settings → Pages → Source: Deploy from branch → main → / (root)**
3. Aspetta ~1 minuto → il link è live

## 📁 Struttura

```
/
├── index.html      ← tutta l'app (standalone)
├── README.md
└── .nojekyll       ← evita che GitHub processi il file con Jekyll
```

## 🛠️ Sviluppato con

- HTML / CSS / Vanilla JS — nessun framework
- [IBM Plex Mono](https://fonts.google.com/specimen/IBM+Plex+Mono) + [Bebas Neue](https://fonts.google.com/specimen/Bebas+Neue) + [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts

---

*Made for [LTX-Video](https://github.com/Lightricks/LTX-Video) open source model by Lightricks*

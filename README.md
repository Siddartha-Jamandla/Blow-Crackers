# 🪔 Blow Crackers — Interactive Diwali Fireworks

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Blow%20Crackers-orange?style=for-the-badge)](https://siddartha-jamandla.github.io/Blow-Crackers/)
[![100 Crackers](https://img.shields.io/badge/Crackers-100-gold?style=for-the-badge)](#-cracker-categories)
[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](#-tech)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](#-tech)
[![No Dependencies](https://img.shields.io/badge/Dependencies-None-brightgreen?style=for-the-badge)](#-tech)

**Blow 100 crackers yourself in your browser — no download, no install, and it runs smoothly even on a 2GB phone.**

👉 **Live demo:** https://siddartha-jamandla.github.io/Blow-Crackers/

## 🎬 Demo Video

Watch the full demo (43.8s) — every cracker category, Sky Writing, and the Grand Finale:

▶️ **[Watch on LinkedIn](https://www.linkedin.com/feed/update/urn:li:activity:7525162144934604800/)**

## 📖 Contents

- [What it is](#-what-it-is)
- [Cracker categories](#-cracker-categories)
- [Sky Writing](#-sky-writing)
- [Themes](#-themes)
- [How to use](#-how-to-use)
- [Run locally](#-run-locally)
- [Tech](#-tech)
- [Project structure](#-project-structure)
- [Author](#-author)

## ✨ What it is

An interactive Diwali night sky where you pick a cracker and light it. Built by Siddartha Jamandla — B.Tech AI & ML student, Python / JavaScript developer.

- **100 crackers** — real-market favourites plus new ones, across Sky / Aerial, Ground, Sound / Bombs, Novelty and Power
- **Sky Writing Text Cracker** — type up to 40 characters and watch it written in spark letters in the sky
- **5 themes** — Classic Night Sky, Golden Diwali, Royal Purple, Green / Eco Diwali, Colourful Festival
- **Realistic physics** — gravity, drag, cooling sparks, willows, splitting stars, smoke, shockwave rings
- **Real cracker sounds** — whistle, boom, sizzle, crackle, garland pops — rebuilt to play start to end, with no mid-show silence
- **Smooth on small phones** — auto-detects 2GB / low-end devices and scales particles, resolution and audio, so even the Grand Finale doesn't hang
- **Responsive** — mobile + desktop, 3 columns on phone, 6 on desktop, no overlap

## 🎇 Cracker categories

Filter the grid by category. Filter counts overlap — Power crackers are the loudest picks from across the other categories.

| Category | Count | Examples |
| --- | --- | --- |
| Sky / Aerial | 37 | Rocket, Sky Shot, Roman Candle, Helicopter, Parachute |
| Ground | 32 | Flower Pot / Anar, Chakra, Snake, Peacock Fountain, Colour Smoke |
| Sound / Bombs | 27 | Atom Bomb, Hydrogen Bomb, Sutli Bomb, Lakshmi Bomb, Red Bijili |
| Novelty | 41 | Butterfly, Crackling Ball, Pop Pop, 100-Shot Cake |
| Power / Loudest | 13 | Titan Rocket, Mega Shell, Thunder King, Sultan Bomb, 10000 Wala Ladi, Volcano Eruption, Earthquake Bomb, Tsunami Cake, Dragon Shell, Phoenix Rocket, 20000 Wala Ladi, Supernova Shell |

## ✍️ Sky Writing

Type your wish (up to 40 characters) and the Text Cracker writes it in the sky in spark letters — **"Happy Diwali" first, then your text underneath** about 2.4 seconds later.

Try it: tap **Happy Diwali** and the sky shows `HAPPY DIWALI`, then `FOR ALL OF YOU`.

## 🎨 Themes

| Theme | Vibe |
| --- | --- |
| Classic Night Sky | Deep night blue, classic fireworks |
| Golden Diwali | Warm golds — the Diwali glow |
| Royal Purple | Rich purple night |
| Green / Eco Diwali | Fresh greens, eco-friendly feel |
| Colourful Festival | Bright multi-colour celebration |

## 🎆 How to use

1. Open the [live demo](https://siddartha-jamandla.github.io/Blow-Crackers/)
2. Pick a cracker from the grid (or filter by category)
3. Tap the sky to light it — turn sound on 🔊
4. Try the Text Cracker, then finish with the **Grand Finale**

## 💻 Run locally

No build step, no install — just open the file:

```bash
git clone https://github.com/Siddartha-Jamandla/Blow-Crackers.git
cd Blow-Crackers
# then open index.html in any browser, or serve it:
python3 -m http.server 8000
# open http://localhost:8000
```

## 🛠 Tech

Single-file HTML + CSS + JavaScript. Canvas fireworks, WebAudio synthesised sounds (pre-rendered buffers, no external audio files). No build step, no dependencies.

## 📁 Project structure

```
Blow-Crackers/
├── index.html   # The whole app — HTML, CSS, JavaScript, 100 crackers
└── README.md    # This file
```

## 👤 Author

**Siddartha Jamandla** — B.Tech AI & ML student, Python / JavaScript developer

- GitHub: https://github.com/Siddartha-Jamandla
- LinkedIn: https://www.linkedin.com/in/siddartha-jamandla-97350b384
- Portfolio: https://siddartha-jamandla.github.io/MY-Portfolio/

Happy Diwali! 🪔

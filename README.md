<h1 align="center">Hi, I'm Shoaibul Hoque 👋</h1>
<p align="center"><b>I design and ship full products</b> — AI apps, backends, browser games — directing AI-assisted development and automation (Claude Code) to go from idea to real, deployed, working software.</p>

<p align="center">
  <a href="https://www.linkedin.com/in/shoaibul-hoque-456632252"><img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="https://shoaibul0926.github.io/chat-buddy/"><img src="https://img.shields.io/badge/Live%20Demo-Chat%20Buddy-6E56CF?style=flat-square&logo=vercel&logoColor=white" alt="Chat Buddy live"></a>
  <a href="https://shoaibul0926.github.io/PixelDeck/"><img src="https://img.shields.io/badge/Play-PixelDeck-FF5252?style=flat-square&logo=itchdotio&logoColor=white" alt="PixelDeck live"></a>
  <a href="https://github.com/shoaibul0926/PixelDeck/releases/download/latest/PixelDeck.apk"><img src="https://img.shields.io/badge/Download-Android%20APK-3DDC84?style=flat-square&logo=android&logoColor=white" alt="PixelDeck Android APK"></a>
</p>

---

### 🚀 Featured build — [Chat Buddy](https://github.com/shoaibul0926/chat-buddy)

An AI-assisted chat and document assistant, live at **[shoaibul0926.github.io/chat-buddy](https://shoaibul0926.github.io/chat-buddy/)**. It runs entirely in the browser: no login, no server, and everything you save stays on your own device.

- 📄 Document Q&A over PDF/DOCX/TXT — text extracted client-side (pdf.js, mammoth) and searched by keyword relevance
- 🕵️ Image intelligence: OCR (Tesseract.js), object detection (TensorFlow.js COCO-SSD), captioning
- 💬 Multi-conversation chat UX — folders, search, rename/delete, light/dark theme, a personal knowledge base, and an agent-style multi-step task planner
- 💾 Local-first persistence in IndexedDB via an in-browser API layer, so the app is a static site on GitHub Pages
- 🧰 The repo also keeps a self-hostable Node/Express backend with streaming LLM chat (Anthropic/OpenAI), Voyage AI embeddings + RAG, and image generation, backed by 69 automated tests — these need API keys and a server, so they're off in the hosted demo

```
Vanilla JS · IndexedDB · pdf.js · Tesseract.js · TensorFlow.js · GitHub Pages / Actions  (optional backend: Node.js · Express)
```

### 🎮 Featured build — [PixelDeck](https://github.com/shoaibul0926/PixelDeck)

A retro arcade game hub, live at **[shoaibul0926.github.io/PixelDeck](https://shoaibul0926.github.io/PixelDeck/)** and as a downloadable **[Android app (APK)](https://github.com/shoaibul0926/PixelDeck/releases/download/latest/PixelDeck.apk)**. A single front-end that aggregates 16 independently-built, independently-deployed browser games — open it and play, no login:

- 🕹️ 16 playable games — snake, Sudoku, a Mario-style platformer, a space shooter, a car racer, and more — each its own standalone repo, launched live from one hub
- 📱 Android app — the same site wrapped with Capacitor; a GitHub Actions workflow builds the APK and publishes it to a GitHub Release on every push
- 🧩 Single-source game registry — one entry per game (slug, title, url, accent color); adding a new game touches nothing else in the codebase
- 🖥️ Retro CRT-styled UI — animated splash screen, scanline effects, per-game accent glow, splash/hub screen flow

```
HTML5 · Vanilla JS · Capacitor · GitHub Actions · GitHub Pages
```

<details>
<summary><b>🕹️ See all 16 games</b></summary>
<br>

Each game links to its **live, playable build** — click through and try it, no setup needed.

| Game | Game | Game |
|---|---|---|
| [▶ Snake](https://shoaibul0926.github.io/snake-game/) ([code](https://github.com/shoaibul0926/snake-game)) | [▶ Sudoku](https://shoaibul0926.github.io/Sudoku-game/) ([code](https://github.com/shoaibul0926/Sudoku-game)) | [▶ Space Shooter](https://shoaibul0926.github.io/space-shooter-game/) ([code](https://github.com/shoaibul0926/space-shooter-game)) |
| [▶ Mario-Style Platformer](https://shoaibul0926.github.io/new-mario-game/) ([code](https://github.com/shoaibul0926/new-mario-game)) | [▶ Car Racing](https://shoaibul0926.github.io/car-racing-game/) ([code](https://github.com/shoaibul0926/car-racing-game)) | [▶ Flappy Bird Clone](https://shoaibul0926.github.io/flappybird-game/) ([code](https://github.com/shoaibul0926/flappybird-game)) |
| [▶ Basketball Shooter](https://shoaibul0926.github.io/My-first-game/) ([code](https://github.com/shoaibul0926/My-first-game)) | [▶ Brick Breaker](https://shoaibul0926.github.io/brick-breaker-game/) ([code](https://github.com/shoaibul0926/brick-breaker-game)) | [▶ Block Stacker](https://shoaibul0926.github.io/block-stacker-game/) ([code](https://github.com/shoaibul0926/block-stacker-game)) |
| [▶ Bubble Pop](https://shoaibul0926.github.io/bubble-pop-game/) ([code](https://github.com/shoaibul0926/bubble-pop-game)) | [▶ Whack-a-Mole](https://shoaibul0926.github.io/whack-a-mole-game/) ([code](https://github.com/shoaibul0926/whack-a-mole-game)) | [▶ Simon Sequence](https://shoaibul0926.github.io/simon-sequence-game/) ([code](https://github.com/shoaibul0926/simon-sequence-game)) |
| [▶ Road Crosser](https://shoaibul0926.github.io/road-crosser-game/) ([code](https://github.com/shoaibul0926/road-crosser-game)) | [▶ Number Merge (2048-style)](https://shoaibul0926.github.io/number-merge-game/) ([code](https://github.com/shoaibul0926/number-merge-game)) | [▶ Bird Hunt](https://shoaibul0926.github.io/bird-hunt-game/) ([code](https://github.com/shoaibul0926/bird-hunt-game)) |
| [▶ Fruit Slice](https://shoaibul0926.github.io/fruit-slice-game/) ([code](https://github.com/shoaibul0926/fruit-slice-game)) | | |

</details>

### 🧮 Also built

| Project | Live | Code | What it is |
|---|---|---|---|
| Scientific Calculator | [▶ Try it](https://shoaibul0926.github.io/scientific-calculator/) | [code](https://github.com/shoaibul0926/scientific-calculator) | Single-file HTML/CSS/JS calculator — scientific, programmer/base-N, complex, matrix, equation & calculus modes |
| Casio-style Calculator | [▶ Try it](https://shoaibul0926.github.io/casio-calculator/) | [code](https://github.com/shoaibul0926/casio-calculator) | Casio FX-991EX-style calculator, same mode coverage as above |

---

### 🛠️ Tech I work with

<p>
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black">
  <img src="https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=node.js&logoColor=white">
  <img src="https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white">
  <img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white">
  <img src="https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square&logo=anthropic&logoColor=white">
  <img src="https://img.shields.io/badge/AI--Assisted%20Development-6E56CF?style=flat-square">
  <img src="https://img.shields.io/badge/Anthropic%20API-D97757?style=flat-square&logo=anthropic&logoColor=white">
  <img src="https://img.shields.io/badge/OpenAI%20API-412991?style=flat-square&logo=openai&logoColor=white">
  <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens&logoColor=white">
</p>

### 📊 GitHub Stats

<p>
  <img src="https://img.shields.io/badge/dynamic/json?url=https://api.github.com/users/shoaibul0926&label=Public%20Repos&query=%24.public_repos&color=2ea44f&style=flat-square">
  <img src="https://img.shields.io/github/followers/shoaibul0926?label=Followers&style=flat-square&color=0A66C2">
</p>

### 📫 Get in touch

**[LinkedIn — Shoaibul Hoque](https://www.linkedin.com/in/shoaibul-hoque-456632252)**

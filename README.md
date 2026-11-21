<div align="center">

<img src="assets/profile-hero.svg" width="100%" alt="Bhuvan0x — Ideas into systems" />

<br/>

<a href="https://github.com/bhuvan0x">
  <img src="https://img.shields.io/badge/GITHUB-PROFILE-111827?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
</a>
<a href="https://www.linkedin.com/in/bhuvan0x/">
  <img src="https://img.shields.io/badge/LINKEDIN-CONNECT-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" />
</a>
<img src="https://komarev.com/ghpvc/?username=bhuvan0x&style=flat-square&color=6D63FF&label=VISITORS" alt="Profile visitors" />

</div>

<br/>

<table>
<tr>
<td width="62%" valign="top">

### 01 / THE OPERATOR

I'm **Bhuvan** — a student developer exploring the edge between software, intelligence, and human experience.

My curiosity lives in **AI systems, local-first computing, and immersive technology**. I like taking a big idea, opening it up, and figuring out how the pieces could actually work.

</td>
<td width="38%" valign="top">

### CURRENT COORDINATES

**FOCUS**  
AI · VR / AR · HCI

**MODE**  
Learn → Experiment → Build

**LONG GAME**  
Next-generation immersive systems

**NORTH STAR**  
Science & Engineering in Japan

</td>
</tr>
</table>

## 02 / SELECTED BUILDS

Not a list of tutorials. A few experiments, tools, and systems I've put together.

<table>
<tr>
<td width="50%" valign="top">

**[01 — AI-NEXUS RADAR ↗](https://github.com/bhuvan0x/ai-nexus-radar)**

A reliability-first web extraction workspace. Detects missing data and schema drift, then routes collectors through a human-reviewed repair loop.

<sub>AI · DATA SYSTEMS · RELIABILITY</sub>

</td>
<td width="50%" valign="top">

**[02 — WILLED CHESS ↗](https://github.com/bhuvan0x/Willed-Chess)**

Chess with a twist: pieces have behavioral tendencies, morale, loyalty, and personalities. Strategy meets a piece-level command system.

<sub>GAME SYSTEMS · INTERACTION · WEB</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[03 — MOUSE PULSE ↗](https://github.com/bhuvan0x/Mouse-Pulse)**

A browser-based mouse diagnostics lab for click, movement, scroll, polling-rate estimates, and CPI/DPI calibration.

<sub>REACT · TYPESCRIPT · BROWSER APIS</sub>

</td>
<td width="50%" valign="top">

**[04 — SLIDEFORGE AI ↗](https://github.com/bhuvan0x/SlideForge-AI)**

Turns a rough presentation idea into a structured slide-by-slide content plan — from blank page to a clear direction.

<sub>GENERATIVE AI · PRODUCTIVITY · WEB</sub>

</td>
</tr>
<tr>
<td width="50%" valign="top">

**[05 — SHARINGAN TERMINAL ↗](https://github.com/bhuvan0x/Sharingan-Animation-in-Terminal)**

Procedural anime-inspired eye animations drawn live in the terminal with Python and ANSI true-colour graphics.

<sub>PYTHON · GENERATIVE GRAPHICS · TERMINAL</sub>

</td>
<td width="50%" valign="top">

**[06 — NEONFLUX ↗](https://github.com/bhuvan0x/NeonFlux---Autonomous-AI-Creator-System)**

An autonomous content-generation experiment: discover relevant Hacker News topics, evaluate them against a persona, and draft posts.

<sub>AI AGENTS · AUTOMATION · NODE.JS</sub>

</td>
</tr>
</table>

<div align="center">

[ **EXPLORE ALL REPOSITORIES →** ](https://github.com/bhuvan0x?tab=repositories)

</div>

---

## 03 / THE MAIN BUILD — ALYA PRIMEBOOK

<div align="center">

**v1.9 · PROJECT STARDUST** &nbsp; / &nbsp; **PRIVATE R&D** &nbsp; / &nbsp; **LAST MILESTONE: 19 NOV 2026**

### Not a chatbot window. An assistant system built from the runtime up.

</div>

A local-first AI companion being engineered for constrained ARM64 hardware. The core inference and speech pipeline runs locally; optional web search is a separate, user-controlled feature.

### SYSTEM STATUS

<table>
<tr>
<td width="50%" valign="top">

**01 — LOCAL AI + VOICE**

- Qwen3 1.7B through `llama.cpp`
- Multilingual Whisper.cpp speech recognition
- Qwen3-TTS.cpp voice synthesis
- Deterministic routing before model inference

**02 — THREE INTERFACES**

- Browser workspace
- Keyboard-driven Alya Prime TUI
- Optional Termux:GUI native shell

All share the same backend, conversations, memory, tools, and model lifecycle.

</td>
<td width="50%" valign="top">

**03 — MEMORY + KNOWLEDGE**

- SQLite-backed chat sessions and summaries
- Approved long-term memory and background learning
- Local FTS5 document library
- Study coach, saved skills, research, and daily briefing

**04 — AVATAR + SCENE STUDIO**

- VRM avatar support and lightweight 2D portrait fallback
- Scene environments, lighting, camera, and transform controls
- User-selectable avatar and visual settings

</td>
</tr>
<tr>
<td width="50%" valign="top">

**05 — ENGINEERING + PORTABILITY**

- Android/Termux and Linux platform adapters
- Optional Rust Core v1.1 process/task supervisor
- Explicit process ownership and bounded task handling
- Rust core verified on Linux ARM64: 71 Rust tests and a real owned FFmpeg task

</td>
<td width="50%" valign="top">

**06 — RELIABILITY + PRIVACY**

- Loopback-first local service
- Session isolation and persistent-state controls
- Prompt-injection defenses and permission-checked local tools
- Offline regression coverage across memory, retrieval, voice cache, UI, and runtime behavior

</td>
</tr>
</table>

### THE CURRENT TERMINAL — PROJECT STARDUST

The v1.9 terminal redesign, **Stardust Atelier**, introduces a midnight-lavender visual system, a constellation-inspired home screen, responsive layouts, five themes, wrapped Markdown/code, and graceful colour/ASCII fallbacks.

### WHAT I'M VERIFYING NEXT

Implementation progress is substantial, but software tests are not a substitute for real-device acceptance. The remaining checks are:

- Live microphone capture and audible speaker playback on the target device
- Browser VRM rendering, GPU behaviour, and Scene Studio visuals
- Sustained FPS, memory/thermal behaviour, and touch gestures
- Re-validation of the optional Rust build on Android/Termux

> **Status honesty:** Linux ARM64 Rust verification is documented. The Android/Termux Rust build was not re-run in this revision. Browser rendering and physical audio acceptance remain manual checks.

<div align="center">

<sub>BUILT LOCALLY · TESTED IN LAYERS · STILL ITERATING</sub>

</div>

---

## 04 / TOOLBOX

<div align="center">

<img src="https://skillicons.dev/icons?i=python,c,cpp,js,ts,html,css,bash,linux,git,github,nodejs,cmake&theme=dark&perline=7" alt="Technologies and tools" />

<br/><br/>

**AI / AUDIO EXPERIMENTS**

<sub>llama.cpp · Whisper · Qwen3-TTS · Local LLMs</sub>

**EXPLORING**

<sub>AR / VR · Human–Computer Interaction · Machine Learning</sub>

</div>

<sub>Tools I've used or am actively exploring — not a claim of expertise in every item.</sub>

---

## 05 / ACTIVITY LOG

<div align="center">

<img height="155" src="https://github-stats-extended.vercel.app/api?username=bhuvan0x&show_icons=true&include_all_commits=true&rank_icon=github&hide_border=true&bg_color=0D1117&title_color=9B8CFF&text_color=C9D1D9&icon_color=39D8E6&cache_seconds=86400" alt="GitHub statistics" />
<img height="155" src="https://github-stats-extended.vercel.app/api/top-langs/?username=bhuvan0x&layout=compact&langs_count=8&size_weight=0.5&count_weight=0.5&hide_border=true&bg_color=0D1117&title_color=9B8CFF&text_color=C9D1D9&cache_seconds=86400" alt="Most used languages" />

<br/>

<a href="https://github.com/bhuvan0x?tab=repositories">
  <img src="assets/build-constellation.svg" width="100%" alt="Bhuvan0x build constellation — six projects connected by curiosity and engineering" />
</a>

<sub>Six projects. Different disciplines. One habit: take things apart, understand them, build something better.</sub>

</div>

---

<div align="center">

### LESS TALK. MORE ITERATION.

I'm here to learn difficult things, build real projects, and keep raising the bar.

<a href="https://github.com/bhuvan0x?tab=repositories">REPOSITORIES</a>
&nbsp; ◈ &nbsp;
<a href="https://www.linkedin.com/in/bhuvan0x/">LINKEDIN</a>

<br/><br/>

<sub>BHUVAN0X // END OF TRANSMISSION</sub>

</div>

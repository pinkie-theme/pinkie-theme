<!-- SEO Metadata & Social Graph -->
<meta name="description" content="Pinkie Theme — An elegant, soothing pastel-pink and soft-white color palette & design tokens crafted for code editors, terminals, note-taking apps, and pink lovers.">
<meta name="keywords" content="pinkie, pinkie theme, pastel pink theme, cozy theme, aesthetic color scheme, vscode pink theme, obsidian pink theme, neovim colorscheme, terminal theme, design tokens, nord-inspired, catppuccin, rose pine, developer aesthetics">
<meta name="author" content="cmduyeen">
<meta property="og:title" content="Pinkie Theme — Soothing Pastel Pink Color Palette">
<meta property="og:description" content="An elegant, soft pastel-pink and cozy color palette crafted for code editors, terminals, and pink lovers.">
<meta property="og:image" content="https://raw.githubusercontent.com/pinkie-theme/pinkie-theme/main/assets/logo.svg">
<meta property="og:url" content="https://github.com/pinkie-theme/pinkie-theme">
<meta property="og:type" content="website">
<meta name="twitter:card" content="summary">
<meta name="twitter:title" content="Pinkie Theme — Soothing Pastel Pink Color Palette">
<meta name="twitter:description" content="An elegant, soft pastel-pink and cozy color palette crafted for code editors, terminals, and pink lovers.">
<meta name="twitter:image" content="https://raw.githubusercontent.com/pinkie-theme/pinkie-theme/main/assets/logo.svg">

<p align="center">
  <img src="assets/logo.svg" alt="Pinkie Theme" width="130" />
</p>

<h1 align="center">Pinkie</h1>

<p align="center">
  A gentle pastel-pink and soft-white theme crafted for pink lovers.
</p>

<p align="center">
  <a href="LICENSE"><img src="https://img.shields.io/badge/License-MIT-FFD1DC?style=flat" alt="License" /></a>
  <img src="https://img.shields.io/badge/Version-1.0.0-FFF0F5?style=flat&logoColor=D4698B" alt="Version" />
</p>

---

### Philosophy

**Pinkie** pairs soothing pastel pinks with gentle soft whites—crafted for pink lovers seeking a calm, aesthetic workspace.

- **Calmness** ── Soft pink tones naturally soothe the nervous system, reducing tension during long hours.
- **Positivity** ── Evokes a light, uplifting mood that brings subtle joy to your daily workflow.
- **Ergonomics** ── Delicate contrast eliminates screen glare, keeping your eyes refreshed and relaxed.

---

### Palette

<details open>
<summary><b>Surfaces &amp; Base</b></summary>
<br>

| <img src="https://img.shields.io/badge/-%23fffdfd-fffdfd?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23fff6fa-fff6fa?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23ffeff6-ffeff6?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23f1d3e2-f1d3e2?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23453b43-453b43?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23786c76-786c76?style=flat-square" /> |
| :---: | :---: | :---: | :---: | :---: | :---: |
| **Canvas**<br>`#fffdfd` | **Surface**<br>`#fff6fa` | **Elevated**<br>`#ffeff6` | **Border**<br>`#f1d3e2` | **Text**<br>`#453b43` | **Muted**<br>`#786c76` |

</details>

<details open>
<summary><b>Accents &amp; Syntax</b></summary>
<br>

| <img src="https://img.shields.io/badge/-%23d44b8b-d44b8b?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23c4377a-c4377a?style=flat-square" /> | <img src="https://img.shields.io/badge/-%236a5acd-6a5acd?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23c71d5f-c71d5f?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23b21f5f-b21f5f?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23a84079-a84079?style=flat-square" /> | <img src="https://img.shields.io/badge/-%232f9e88-2f9e88?style=flat-square" /> | <img src="https://img.shields.io/badge/-%23ff7a59-ff7a59?style=flat-square" /> |
| :---: | :---: | :---: | :---: | :---: | :---: | :---: | :---: |
| **Primary**<br>`#d44b8b` | **Rose**<br>`#c4377a` | **Lavender**<br>`#6a5acd` | **Berry**<br>`#c71d5f` | **Magenta**<br>`#b21f5f` | **Plum**<br>`#a84079` | **Mint**<br>`#2f9e88` | **Coral**<br>`#ff7a59` |

</details>

Design tokens are available in [src/pinkie.json](src/pinkie.json) and [src/pinkie.css](src/pinkie.css).

---

### Ports

<details open>
<summary><b>Code Editors &amp; Development</b></summary>
<br>

<a href="https://github.com/cmduyeen/pinkie-vscode"><img src="https://img.shields.io/badge/VS_Code-FFF0F5?style=flat&logo=data:image/svg%2bxml;base64,PHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU%2BVmlzdWFsIFN0dWRpbyBDb2RlPC90aXRsZT48cGF0aCBmaWxsPSIjZDQ2OThiIiBkPSJNMjMuMTUgMi41ODdMMTguMjEuMjFhMS40OTQgMS40OTQgMCAwIDAtMS43MDUuMjlsLTkuNDYgOC42My00LjEyLTMuMTI4YS45OTkuOTk5IDAgMCAwLTEuMjc2LjA1N0wuMzI3IDcuMjYxQTEgMSAwIDAgMCAuMzI2IDguNzRMMy44OTkgMTIgLjMyNiAxNS4yNmExIDEgMCAwIDAgLjAwMSAxLjQ3OUwxLjY1IDE3Ljk0YS45OTkuOTk5IDAgMCAwIDEuMjc2LjA1N0w0LjEyLTMuMTI4IDkuNDYgOC42M2ExLjQ5MiAxLjQ5MiAwIDAgMCAxLjcwNC4yOWw0Ljk0Mi0yLjM3N0ExLjUgMS41IDAgMCAwIDI0IDIwLjA2VjMuOTM5YTEuNSAxLjUgMCAwIDAtLjg1LTEuMzUyem0tNS4xNDYgMTQuODYxTDEwLjgyNiAxMmw3LjE3OC01LjQ0OHYxMC44OTZ6Ii8%2BPC9zdmc%2B" alt="VS Code" /></a> ── In Progress

<img src="https://img.shields.io/badge/Neovim-FFF0F5?style=flat&logo=neovim&logoColor=D4698B" alt="Neovim" /> ── Planned

<img src="https://img.shields.io/badge/JetBrains-FFF0F5?style=flat&logo=jetbrains&logoColor=D4698B" alt="JetBrains" /> ── Planned

<img src="https://img.shields.io/badge/Sublime_Text-FFF0F5?style=flat&logo=sublimetext&logoColor=D4698B" alt="Sublime Text" /> ── Planned

<img src="https://img.shields.io/badge/Helix-FFF0F5?style=flat&logo=helix&logoColor=D4698B" alt="Helix" /> ── Planned

</details>

<details open>
<summary><b>Note-Taking &amp; Knowledge</b></summary>
<br>

<a href="https://github.com/cmduyeen/Pinkie-for-Obsidian"><img src="https://img.shields.io/badge/Obsidian-FFF0F5?style=flat&logo=obsidian&logoColor=D4698B" alt="Obsidian" /></a> ── Active

<img src="https://img.shields.io/badge/Logseq-FFF0F5?style=flat&logo=logseq&logoColor=D4698B" alt="Logseq" /> ── Planned

<img src="https://img.shields.io/badge/Notion-FFF0F5?style=flat&logo=notion&logoColor=D4698B" alt="Notion" /> ── Planned

</details>

<details>
<summary><b>Terminals &amp; CLI</b></summary>
<br>

<img src="https://img.shields.io/badge/Alacritty-FFF0F5?style=flat&logo=alacritty&logoColor=D4698B" alt="Alacritty" /> ── Planned

<img src="https://img.shields.io/badge/WezTerm-FFF0F5?style=flat&logo=wezterm&logoColor=D4698B" alt="WezTerm" /> ── Planned

<img src="https://img.shields.io/badge/iTerm2-FFF0F5?style=flat&logo=iterm2&logoColor=D4698B" alt="iTerm2" /> ── Planned

<img src="https://img.shields.io/badge/Tmux-FFF0F5?style=flat&logo=tmux&logoColor=D4698B" alt="Tmux" /> ── Planned

<img src="https://img.shields.io/badge/Starship-FFF0F5?style=flat&logo=starship&logoColor=D4698B" alt="Starship" /> ── Planned

<img src="https://img.shields.io/badge/Warp-FFF0F5?style=flat&logo=warp&logoColor=D4698B" alt="Warp" /> ── Planned

</details>

<details>
<summary><b>Desktop &amp; Window Managers</b></summary>
<br>

<img src="https://img.shields.io/badge/Raycast-FFF0F5?style=flat&logo=raycast&logoColor=D4698B" alt="Raycast" /> ── Planned

<img src="https://img.shields.io/badge/Hyprland-FFF0F5?style=flat&logo=hyprland&logoColor=D4698B" alt="Hyprland" /> ── Planned

<img src="https://img.shields.io/badge/i3wm-FFF0F5?style=flat&logo=i3&logoColor=D4698B" alt="i3" /> ── Planned

<img src="https://img.shields.io/badge/Sway-FFF0F5?style=flat&logo=sway&logoColor=D4698B" alt="Sway" /> ── Planned

<img src="https://img.shields.io/badge/GNOME-FFF0F5?style=flat&logo=gnome&logoColor=D4698B" alt="GNOME" /> ── Planned

</details>

<details>
<summary><b>Browsers &amp; Communication</b></summary>
<br>

<img src="https://img.shields.io/badge/Discord-FFF0F5?style=flat&logo=discord&logoColor=D4698B" alt="Discord" /> ── Planned

<img src="https://img.shields.io/badge/Telegram-FFF0F5?style=flat&logo=telegram&logoColor=D4698B" alt="Telegram" /> ── Planned

<img src="https://img.shields.io/badge/Firefox-FFF0F5?style=flat&logo=firefoxbrowser&logoColor=D4698B" alt="Firefox" /> ── Planned

<img src="https://img.shields.io/badge/Thunderbird-FFF0F5?style=flat&logo=thunderbird&logoColor=D4698B" alt="Thunderbird" /> ── Planned

<img src="https://img.shields.io/badge/Brave-FFF0F5?style=flat&logo=brave&logoColor=D4698B" alt="Brave" /> ── Planned

</details>

<details>
<summary><b>Media &amp; Creativity</b></summary>
<br>

<img src="https://img.shields.io/badge/Spotify-FFF0F5?style=flat&logo=spotify&logoColor=D4698B" alt="Spotify" /> ── Planned

<img src="https://img.shields.io/badge/Blender-FFF0F5?style=flat&logo=blender&logoColor=D4698B" alt="Blender" /> ── Planned

<img src="https://img.shields.io/badge/Godot-FFF0F5?style=flat&logo=godotengine&logoColor=D4698B" alt="Godot" /> ── Planned

<img src="https://img.shields.io/badge/OBS_Studio-FFF0F5?style=flat&logo=obsstudio&logoColor=D4698B" alt="OBS Studio" /> ── Planned

<img src="https://img.shields.io/badge/Figma-FFF0F5?style=flat&logo=figma&logoColor=D4698B" alt="Figma" /> ── Planned

</details>

---

### License

- [MIT License](LICENSE) — Free and open-source.
- Copyright © 2026 [cmduyeen](https://github.com/cmduyeen) — Pinkie Suite.

---

### The Story Behind

> Following a period of illness and mental health struggles, I discovered how much gentle pink tones helped soothe my mind and uplift my spirits. Realizing how few themes cater thoughtfully to women and pink lovers in developer spaces, I created **Pinkie** with kindness and care.
>
> My hope is simply to bring warmth and a little daily joy to your workspace.  
> *Take gentle care of yourself, and always remember to **love yourself**.* 🌸

<p align="center">
  <img src="assets/signature.svg" alt="cmduyeen" width="200" />
</p>

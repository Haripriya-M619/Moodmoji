# 😄 MoodMoji

> Upload a photo or take a selfie — AI reads your expression and one emoji takes over the whole screen.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-yellow?style=flat-square)](https://yourusername.github.io/moodmoji)
[![Made with Claude](https://img.shields.io/badge/AI-Claude%20Vision-blueviolet?style=flat-square)](https://anthropic.com)
[![Zero Dependencies](https://img.shields.io/badge/dependencies-zero-brightgreen?style=flat-square)]()

---

## What it does

MoodMoji uses Claude's Vision API to analyse a face in any photo and classify the expression into one of five moods:

| Emoji | Mood    | Message |
|-------|---------|---------|
| 😄    | Happy   | Keep shining — the world needs that energy! |
| 😢    | Sad     | Better days are on their way 💙 |
| 😐    | Neutral | Unreadable. A true mystery. |
| 😠    | Angry   | Take a deep breath. You've got this. |
| 🥱    | Bored   | Same, honestly. |

After analysis, the matching emoji fills the **entire screen** with a full-screen animated overlay and a personal message.

---

## Features

- 📁 **Upload mode** — drag & drop or browse any image
- 📸 **Camera mode** — snap a selfie directly in the browser
- ✨ **Fullscreen emoji reveal** — animated pop-in with mood glow
- 🔑 **API key stored locally** — never sent anywhere except Anthropic
- 📦 **Zero dependencies** — vanilla HTML, CSS, JS only

---

## How to run locally

```bash
# Clone the repo
git clone https://github.com/yourusername/moodmoji.git
cd moodmoji

# Serve locally (Python)
python -m http.server 8080

# Or with Node
npx serve .
```

Open [http://localhost:8080](http://localhost:8080)

Enter your Anthropic API key in the app (get one at [console.anthropic.com](https://console.anthropic.com)).

---

## Deploy to GitHub Pages (free)

1. Push all files to a GitHub repo
2. Go to **Settings → Pages → Deploy from branch → main**
3. Your live URL: `https://yourusername.github.io/moodmoji`
4. Replace `yourusername` in this README with your GitHub handle

---

## Screenshot

<img width="1919" height="880" alt="Screenshot 2026-06-15 221529" src="https://github.com/user-attachments/assets/ad2b9100-48cc-4b7e-9942-4b7183d28817" />

<img width="1886" height="894" alt="Screenshot 2026-06-15 223121" src="https://github.com/user-attachments/assets/5b791001-6b45-4770-bad3-bae487e134f4" />



## Project structure

```
moodmoji/
├── index.html   # Landing page
├── app.html     # The app
└── README.md    # This file
```

---

## Tech stack

| Layer     | Technology |
|-----------|-----------|
| AI Vision | Claude claude-sonnet-4-6 (Anthropic) |
| Camera    | MediaDevices API |
| Image     | HTML5 Canvas API |
| Frontend  | Vanilla JS, HTML, CSS |
| Fonts     | Bricolage Grotesque, Inter (Google Fonts) |
| Hosting   | GitHub Pages |

---


## License

MIT

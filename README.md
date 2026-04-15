<div align="center">

# ✦ Lyra AI

**Intelligence, Distilled.**

Free AI chat powered by GPT-4o — no API key, no sign-up, always free.

[![Deploy to GitHub Pages](https://github.com/manikanta-devs/Layra/actions/workflows/deploy.yml/badge.svg)](https://github.com/manikanta-devs/Layra/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-00c896.svg)](LICENSE)

</div>

---

## ✨ Features

| Feature | Detail |
|---------|--------|
| 🆓 **Free forever** | Powered by [Puter.js](https://puter.com) — no cost, no limits |
| 🧠 **5 AI Models** | GPT-4o mini, GPT-4o, Claude 3.5, Llama 3.1, Mistral 7B |
| 💬 **Multi-chat** | Unlimited chat sessions with searchable history |
| 📝 **Full Markdown** | Headings, tables, bold, italic, blockquotes |
| 💻 **Code blocks** | Syntax highlighting + one-click copy |
| 🎭 **6 Personas** | Assistant, Friend, Teacher, Coder, Writer, Analyst |
| 🔄 **Regenerate** | Re-run any AI response instantly |
| 🎙️ **Voice input** | Speak your messages with auto-send |
| 📤 **Export** | Download any chat as `.md` |
| 📱 **PWA** | Installable, offline-capable UI shell |
| 🌌 **Branded UI** | Lyra constellation design system |

---

## 🚀 Getting Started

### Deploy to GitHub Pages

1. **Fork** this repository
2. Go to **Settings → Pages**
3. Under **Build and deployment**, select **GitHub Actions**
4. The site deploys automatically on every push to `main`
5. Visit `https://<your-username>.github.io/Layra/`

> **Note:** The app requires HTTPS to load Puter.js. GitHub Pages provides this automatically.

### Install as a PWA

1. Open the deployed site in **Chrome** (desktop or Android)
2. Click the install icon in the address bar (or **⋮ → Add to Home Screen** on mobile)
3. Launch Lyra like a native app

---

## 🗂 Project Structure

```
Layra/
├── index.html          ← Complete app (single-file PWA)
├── manifest.json       ← PWA configuration
├── sw.js               ← Service worker for offline caching
├── 404.html            ← Custom 404 page
├── LICENSE             ← MIT License
└── .github/
    └── workflows/
        └── deploy.yml  ← GitHub Pages CI/CD
```

---

## 🛠 Tech Stack

- **Frontend:** Vanilla HTML, CSS, JavaScript (zero build step)
- **AI Engine:** [Puter.js](https://puter.com) — free, no-auth AI API
- **Markdown:** [Marked.js](https://marked.js.org/) with [highlight.js](https://highlightjs.org/)
- **Fonts:** Cormorant Garamond, Outfit, JetBrains Mono (Google Fonts)
- **Hosting:** GitHub Pages with automated deployment

---

## 🐛 Troubleshooting

| Problem | Fix |
|---------|-----|
| "Puter.js failed to load" | Open from GitHub Pages (HTTPS), not a local file |
| AI not responding | Check internet · try a different model |
| Voice not working | Use Chrome · allow microphone permission |
| Blank screen | Hard refresh (`Ctrl + Shift + R`) |

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

---

<div align="center">
  <sub>Built with ✦ by <a href="https://github.com/manikanta-devs">manikanta-devs</a></sub>
</div>
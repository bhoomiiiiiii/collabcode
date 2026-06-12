<div align="center">

# ⌨️ CollabCode

### Real-time Collaborative Code Editor — runs entirely in the browser

[![Live Demo](https://img.shields.io/badge/🚀_Live_Demo-coderoom--live.netlify.app-7c50ff?style=for-the-badge)](https://coderoom-live.netlify.app)
[![GitHub](https://img.shields.io/badge/GitHub-bhoomiiiiiii%2Fcollabcode-181717?style=for-the-badge&logo=github)](https://github.com/bhoomiiiiiii/collabcode)
[![Made with JS](https://img.shields.io/badge/Made_with-JavaScript-f7df1e?style=for-the-badge&logo=javascript&logoColor=black)](https://coderoom-live.netlify.app)

> No servers. No API keys. No setup. Just open and code together.

</div>

---

## ✨ Features

| Feature | Details |
|---|---|
| ⚡ **JavaScript** | Instant execution — runs locally in browser |
| 🐍 **Python 3** | WebAssembly via Pyodide — no backend needed |
| ⚙️ **C / C++** | Browser-based JSCPP interpreter |
| ☕ **Java** | Lightweight built-in interpreter |
| 🌐 **HTML** | Live preview in new tab |
| 👥 **Collaboration** | Room system, live cursors, team chat |
| 🎨 **4 Themes** | Dark, Light, Matrix, Blood Red |
| 📝 **Smart Editor** | Auto-indent, format, Ctrl+D, Ctrl+/, Tab/Shift+Tab |
| 💾 **File Tools** | Download code, copy, stdin support |

---

## 🛠️ Tech Stack

```
Frontend     →  HTML5 · CSS3 · Vanilla JavaScript
Python       →  Pyodide (WebAssembly) — Python 3.12 in browser
C / C++      →  JSCPP — C++ interpreter in JavaScript
Real-time    →  Socket.io · WebSockets
Deployment   →  Netlify
```

---

## 🚀 Quick Start

```bash
# Clone the repo
git clone https://github.com/bhoomiiiiiii/collabcode.git

# Open in browser — no setup needed!
open index.html
```

Or just visit 👉 **[coderoom-live.netlify.app](https://coderoom-live.netlify.app)**

---

## ⌨️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `Ctrl + Enter` | Run code |
| `Ctrl + S` | Download file |
| `Ctrl + /` | Toggle comment |
| `Ctrl + D` | Duplicate line |
| `Tab` | Indent (2 spaces) |
| `Shift + Tab` | Unindent |

---

## 💡 How It Works

```
JavaScript  ──→  new Function()         (instant, offline)
Python      ──→  Pyodide WebAssembly    (loads once ~5s, then instant)
C / C++     ──→  JSCPP interpreter      (runs in browser)
Java        ──→  Built-in interpreter   (offline)
HTML        ──→  Blob URL preview       (instant)
```

The biggest challenge was code execution — every free API either had CORS issues, required keys, or shut down (Piston shut down Feb 2026, Wandbox blocks CORS). The solution was moving execution entirely into the browser using WebAssembly and JS-based interpreters.

---

## 📁 Project Structure

```
collabcode/
├── index.html        ← entire frontend (single file)
├── server/
│   ├── server.js     ← Node.js + Socket.io backend
│   └── package.json
└── README.md
```

---

## 🔮 Roadmap

- [ ] Real-time cursor sync via Socket.io
- [ ] Multi-file tabs support  
- [ ] GitHub Gist save & share
- [ ] More languages (Rust, Go, TypeScript)
- [ ] Voice chat integration

---

<div align="center">

Made with 💜 by **[Bhoomi Arora](https://github.com/bhoomiiiiiii)**

⭐ **Star this repo if you found it useful!**

</div>

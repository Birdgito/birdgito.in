# 🐧 Birdgito.in — Linux Terminal Portfolio

> A fully interactive, Linux terminal-style personal portfolio website built with pure **HTML, CSS & JavaScript** — no frameworks, no dependencies.

[![Live Demo](https://img.shields.io/badge/Live-birdgito.in-00ff88?style=flat-square&logo=google-chrome&logoColor=white)](https://birdgito.in)
[![GitHub](https://img.shields.io/badge/GitHub-Birdgito-181717?style=flat-square&logo=github)](https://github.com/Birdgito)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-Pankaj%20Mishra-0077B5?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/birdgito/)
![Made with](https://img.shields.io/badge/Made%20with-HTML%20%7C%20CSS%20%7C%20JS-00ff88?style=flat-square)

---

## 📸 Preview

```
  ██████╗ ██╗██████╗ ██████╗  ██████╗ ██╗████████╗ ██████╗
  ██╔══██╗██║██╔══██╗██╔══██╗██╔════╝ ██║╚══██╔══╝██╔═══██╗
  ██████╔╝██║██████╔╝██║  ██║██║  ███╗██║   ██║   ██║   ██║
  ...

  pankaj@birdgito:~$ help
```

---

## ✨ Features

- 🖥️ **Linux boot sequence** — animated systemd-style boot screen on load
- 💻 **Interactive terminal UI** — type real commands and get real output
- 🔡 **Autocomplete dropdown** — appears as you type with command descriptions
- ⌨️ **Command history** — navigate with ↑ ↓ arrow keys, persisted via `localStorage`
- 📱 **Mobile quick-command bar** — scrollable tap buttons for all key commands
- 🎨 **3 colour themes** — Green / Amber / Cyan, saved across sessions
- 📁 **Directory navigation** — `cd`, `ls`, `pwd` with context-aware output
- 🐇 **Matrix rain easter egg** — `matrix` command
- 🖱️ **Clickable project cards** — tap any card to `cat` that project
- 🔒 **Hacker commands** — `nmap`, `ping`, `ifconfig`, `top`, `git log`, `curl`, `uname -a`
- ⚡ **Zero dependencies** — single `index.html`, no build tools needed
- 🌐 **CRT scanlines + vignette** — authentic terminal aesthetics

---

## 🚀 Available Commands

| Command | Description |
|---|---|
| `help` | List all available commands |
| `whoami` | Identity card |
| `about` | Short bio |
| `education` | BCA @ SICS / MCNUJC details |
| `skills` | Tech stack with animated bars |
| `projects` | All projects (clickable cards) |
| `cat hexamart` | Hexamart e-commerce project |
| `cat libsys` | Library Management System |
| `cat osint` | Cybersecurity OSINT toolkit |
| `cat resume` | Résumé overview |
| `contact` | Email, GitHub, LinkedIn |
| `social` | All social links |
| `ls` | List directory contents |
| `cd <dir>` | Change directory (`projects` / `education` / `skills` / `~`) |
| `pwd` | Print current working directory |
| `neofetch` | Portfolio system info |
| `uname -a` | Kernel / OS info |
| `ifconfig` | Network interfaces |
| `ping birdgito.in` | Ping the domain |
| `nmap localhost` | Simulated port scan |
| `top` | Process table |
| `git log` | Commit history |
| `curl birdgito.in` | HTTP response headers |
| `history` | Persistent command history |
| `matrix` | Matrix rain easter egg 🐇 |
| `banner` | Show ASCII banner again |
| `sudo hire pankaj` | 😏 Try it. |
| `clear` / `Ctrl+L` | Clear the terminal |

---

## 🗂️ Project Structure

```
birdgito.in/
└── index.html       # Entire portfolio — single self-contained file
```

No build step. No package.json. No node_modules. Just one file.

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Markup | HTML5 |
| Styling | CSS3 (custom properties, animations, responsive) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | JetBrains Mono · Share Tech Mono (Google Fonts) |
| Storage | `localStorage` (theme + command history) |
| Hosting | [birdgito.in](https://birdgito.in) |

---

## ⚙️ Keyboard Shortcuts

| Shortcut | Action |
|---|---|
| `↑` / `↓` | Navigate command history |
| `Tab` | Autocomplete command |
| `Escape` | Close autocomplete dropdown |
| `Ctrl + L` | Clear terminal |
| `Ctrl + C` | Cancel current input |

---

## 📦 Deployment

### Option 1 — Upload directly to your domain

1. Download `index.html`
2. Upload it to your hosting provider's root folder (e.g. `public_html/`)
3. Visit **birdgito.in** 🎉

### Option 2 — GitHub Pages

```bash
git clone https://github.com/Birdgito/birdgito.in.git
cd birdgito.in
# push index.html to the repo root
git add index.html README.md
git commit -m "feat: launch birdgito.in portfolio"
git push origin main
```

Then enable **GitHub Pages** in repo Settings → Pages → Source: `main` / `root`.

### Option 3 — Netlify / Vercel

Just drag and drop `index.html` into the Netlify or Vercel dashboard. Done.

---

## 🎨 Themes

Switch themes by clicking the coloured dots in the top-right corner of the terminal bar.

| Theme | Accent |
|---|---|
| 🟢 Green (default) | `#00ff88` |
| 🟡 Amber | `#ffb700` |
| 🔵 Cyan | `#00e5ff` |

Theme preference is saved in `localStorage` and persists across visits.

---

## 📌 About Me

**Pankaj Mishra** ([@Birdgito](https://github.com/Birdgito))

- 🎓 Pursuing **BCA** at Sadguru Institute of Computer Studies, Chitrakoot
- 🏛️ Affiliated with **MCNUJC**, Bhopal
- 📍 Chitrakoot, Uttar Pradesh, India
- 💼 Full-Stack Developer · Security Enthusiast · Open Source Contributor

---

## 📬 Contact

| Platform | Link |
|---|---|
| 🌐 Website | [birdgito.in](https://birdgito.in) |
| 💼 LinkedIn | [linkedin.com/in/birdgito](https://www.linkedin.com/in/birdgito/) |
| 🐙 GitHub | [github.com/Birdgito](https://github.com/Birdgito) |

---

## 📄 License

This project is open source and available under the [MIT License](LICENSE).

Feel free to fork, star ⭐, and use as inspiration for your own terminal portfolio!

---

<p align="center">
  Built with ❤️ and lots of ☕ by <a href="https://github.com/Birdgito">Pankaj Mishra</a>
</p>

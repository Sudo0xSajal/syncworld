# SyncWorld

Official landing page for **SyncWorld** — a security-first software ecosystem by **Sajal Haldar (Sudo0xSajal)**.

This repository contains a production-style, single-page static website that showcases:
- **LinkPhone** (secure real-time communication platform)
- **PhoneCam Connect** (Android-to-webcam workflow)
- Live **GitHub project discovery** via public GitHub API
- A modern, animated UI with a Three.js particle background

---

## 🌐 Live Product Links

- LinkPhone: https://linkphone.syncworld.tech
- PhoneCam Connect: https://phonecam.syncworld.tech
- GitHub Profile: https://github.com/Sudo0xSajal

---

## ✨ Key Features

- **Single-file architecture** (`index.html`) for easy deployment
- **Responsive layout** with desktop navigation and mobile drawer
- **Real-time UI effects** (latency animation, shimmer states, micro-interactions)
- **Three.js visual background** loaded from CDN
- **GitHub repositories section** fetched dynamically from `api.github.com`
- **Security-forward branding** around zero-trust communication systems

---

## 🧱 Tech Stack

- **HTML5**
- **CSS3** (custom design tokens, gradients, glassmorphism, responsive rules)
- **Vanilla JavaScript** (DOM interactions, animations, API fetch)
- **Three.js** (CDN)

No framework build system is required.

---

## 📁 Project Structure

```text
syncworld/
├── assets/
│   └── logo.png
├── index.html
└── README.md
```

---


## ⚙️ Configuration & Customization

Most content and styling are in `index.html`:

- **Branding / metadata**: `<head>` section (`title`, `description`, Open Graph tags)
- **Theme tokens**: CSS `:root` variables near the top
- **Sections**: `#hero`, `#projects`, `#github-projects`, `#matrix`, `#founder`
- **Dynamic GitHub repos**: `loadGitHubRepos()` script near the bottom



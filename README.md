# 🖥️ Browser-Desktop

A web-based desktop environment built with **SvelteKit** and **TailwindCSS**.

Browser-Desktop simulates a desktop-like workspace inside the browser, designed to provide a unified place for simple productivity tools such as notes, to-dos, calendar views, and lightweight apps — accessible from anywhere.

The goal of this project is to explore how far a persistent, browser-based workspace can be taken in terms of usability, UI architecture, and state management.

---

![GitHub Repo size](https://img.shields.io/github/repo-size/RalfKit/browser-desktop)
![GitHub last commit](https://img.shields.io/github/last-commit/RalfKit/browser-desktop)
![GitHub License](https://img.shields.io/github/license/RalfKit/browser-desktop)
![Project Status](https://img.shields.io/badge/status-experimental-lightgrey)

---

## 📸 Screenshots

### Desktop Overview

![Desktop Overview](docs/screenshots/01-desktop-overview.png)

### Window Management

![Window Management](docs/screenshots/02-window-overlap-focus.png)

### Multi-Window State

![Multi Window](docs/screenshots/03-multi-window-state.png)

---

## 🚀 Features

- 📦 Window system with drag, resize, minimize, maximize
- 🖼️ Multi-window environment with focus handling
- 🕑 Taskbar with live clock and active window state
- 🌗 Dark / Light mode support
- 🧩 Pluggable window components (WIP)
- 💾 Local UI state persistence (planned)

---

## 🧠 Concept / Vision

Browser-Desktop is designed as a lightweight personal workspace in the browser.

The idea is to provide a single environment where users can:

- manage simple tasks and notes
- interact with lightweight productivity tools
- access personal data without switching between multiple services
- simulate a consistent desktop experience across devices

Future extensions may include:

- to-do management
- calendar integration
- media playback (e.g. Spotify integration)
- session-based workspace persistence
- app launcher / search system

---

## 📦 Technologies

- [SvelteKit](https://kit.svelte.dev/)
- [TailwindCSS](https://tailwindcss.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [daisyUI](https://github.com/saadeghi/daisyui)

---

## 🛠️ Installation

```bash
git clone https://github.com/RalfKit/browser-desktop.git
cd browser-desktop
pnpm install
pnpm run dev
````

Open `http://localhost:5173` in your browser.

---

## 📌 Status

This is an **experimental UI/architecture project**.
No active development is currently planned.

---

## 🤝 Contributing

Ideas and suggestions are welcome.
Feel free to open an issue for feedback or improvements.

---

**Browser-Desktop — a personal workspace concept inside the browser.**

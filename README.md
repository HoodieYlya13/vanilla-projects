# 🚀 Vanilla Projects Monorepo

Welcome to the **Vanilla Projects** monorepo! This repository is a curated collection of lightweight, high-performance, and visually stunning web applications and experiments built strictly with **Vanilla HTML, CSS, and JavaScript**. 

Designed to explore core web APIs, advanced CSS layouts, hardware-accelerated animations, and responsive interactions without the overhead of heavy frameworks, these projects demonstrate the immense power of native web technologies.

---

## 📂 Project Showcase

This monorepo aggregates multiple standalone modules, each managed as a Git submodule. Click on the project names below to explore their dedicated repositories and READMEs.

### 1. [🎨 CSS Playground](css-playground/)
A dedicated sandbox pushing the boundaries of modern CSS. It features purely styling-driven interactive elements, container queries, custom properties, and advanced 3D transforms.
* **Key Highlights:** Infinite 3D rotating Tesla slide banner (pure CSS), interactive folder reveal animation, neumorphic/glassmorphic components, custom hardware-accelerated loading spinners, and complex `clip-path` shapes.
* **Tech Stack:** HTML5, CSS3 Variables, `@keyframes`, 3D CSS Transforms, FontAwesome.

### 2. [🕰️ Clock](clock/)
A dual-representation analog and digital timepiece combining smooth physical hand sweeps with a high-fidelity digital readout.
* **Key Highlights:** Real-time synchronization using JavaScript's `Date` API, fluid analog movement driven by dynamic CSS variables and rotation transforms, responsive layout, and clean JetBrains Mono typography.
* **Tech Stack:** HTML5, CSS3 (Transforms & Flexbox), Vanilla JS.

### 3. [📝 To Do List](to-do-list/)
A highly functional, responsive task management application emphasizing keyboard accessibility and robust state persistence.
* **Key Highlights:** Instant item additions/deletions, seamless keyboard navigation (submit tasks with `Enter`), and automatic synchronization with the browser's `localStorage` for cross-session data persistence.
* **Tech Stack:** HTML5, CSS3, Vanilla JS (`localStorage` integration).

### 4. [🔢 Guess the Number](guess-number/)
A fast-paced, interactive logic game where players compete against a random number generator within a strictly enforced limit of attempts.
* **Key Highlights:** Dynamic input focus and validation, live counter for remaining attempts, conditional messaging hierarchy ("too high" / "too low"), keyboard bindings (instant reset on `r` keypress), and a hidden playful Easter egg.
* **Tech Stack:** HTML5, CSS3, Vanilla JS.

---

## 🛠️ Monorepo Architecture & Setup

This repository uses **Git Submodules** to manage each project cleanly.

### Getting Started

To clone this repository along with all of its submodules, run:

```bash
git clone --recurse-submodules git@github.com:HoodieYlya13/vanilla-projects.git
cd vanilla-projects
```

If you have already cloned the repository without submodules, you can initialize and update them by running:

```bash
git submodule update --init --recursive
```

### Running Locally

Since all projects are written using standard web standards, you do not need to install complex node dependencies to run them. Simply open the `index.html` file of any project in your browser, or spin up a lightweight local server:

```bash
# Using VS Code Live Server extension, or via CLI:
npx serve .
# OR
python3 -m http.server 8000
```

---

## 👨‍💻 Author

Developed and maintained with ❤️ by **[Ylya Martchenko (HY13dev)](https://www.hy13dev.com/)**.

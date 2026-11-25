# ✂️ Flashcard Maker

A simple, free, browser-based flashcard maker — **no account, no install, no laminator needed**. Just type your cards, print, and cut.

![Flashcard Maker screenshot](https://raw.githubusercontent.com/YOUR-USERNAME/flashcard-maker/main/screenshot.png)

## 🌐 Live Demo

👉 **[Try it on GitHub Pages](https://YOUR-USERNAME.github.io/flashcard-maker)**

---

## ✨ Features

- **True double-sided printing** — questions on page 1, matching answers on page 2, automatically mirrored so they align perfectly after flipping
- **Bulk import** — paste a list of `question | answer` pairs and import them all at once
- **6 colour themes** — Classic, Blue, Green, Yellow, Pink, Purple
- **Flexible layout** — choose 2 or 3 cards per row, 2–4 rows per page
- **Deck title** — label your printouts for easy organisation
- **Card numbering** — small `#` labels so you can verify Q & A pairs match
- **Zero dependencies** — single HTML file, works offline after first load
- **No data leaves your browser** — everything stays local

---

## 🖨️ How to Print

1. Open the app and add your cards (or bulk import them)
2. Click **🖨️ Print Cards**
3. In the print dialog:
   - Enable **Two-sided / Duplex printing**
   - Set flip direction to **Flip on Long Edge** (standard portrait)
4. Print, then cut along the **dashed lines**

Each card will have the question on the front and the **correct matching answer** on the back.

> **Why are the answers mirrored on page 2?**  
> When you flip a sheet of paper along the long edge (portrait), the left side becomes the right side. The answers are pre-mirrored to compensate, so every answer lands exactly behind its question after flipping.

---

## 📋 Bulk Import Format

One card per line, separated by a pipe `|`:

```
What is photosynthesis? | Converting sunlight into energy
Capital of France | Paris
H₂O | Water — 2 hydrogen + 1 oxygen atom
```

---

## 🚀 Getting Started

No build step needed. Just open the file:

```bash
git clone https://github.com/YOUR-USERNAME/flashcard-maker.git
cd flashcard-maker
# Open index.html in your browser
start index.html        # Windows
open index.html         # macOS
xdg-open index.html     # Linux
```

Or use it directly via [GitHub Pages](https://YOUR-USERNAME.github.io/flashcard-maker) — nothing to install.

---

## 📁 Project Structure

```
flashcard-maker/
└── index.html    # The entire app — one self-contained file
└── README.md
```

---

## 🛠️ Built With

- Plain HTML + JavaScript
- [Tailwind CSS](https://tailwindcss.com/) (via CDN)

---

## 📄 License

MIT — do whatever you like with it.

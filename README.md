# 🐞 Sindhu's Debug Diary

A simple, self-contained web app to log coding mistakes, the approach that went
wrong, and the lesson learned from each one — built as a personal DSA/coding
journal to track growth over time.

![Made with HTML](https://img.shields.io/badge/HTML-5-orange)
![Made with CSS](https://img.shields.io/badge/CSS-3-blue)
![Made with JavaScript](https://img.shields.io/badge/JavaScript-Vanilla-yellow)

## 📖 About

Every developer makes the same kind of mistake more than once — until they
write it down. This project is a lightweight "diary" where each entry captures:

- **Problem** — what you were solving
- **Mistake** — what approach didn't work / why
- **Learning** — the takeaway that'll help next time

New entries can be added directly from the browser with a click — no backend,
no database, just plain JavaScript DOM manipulation.

## ✨ Features

- 📝 Add new debug entries on the fly via a prompt-based form
- 🎨 Clean, card-style UI with soft shadows and rounded corners
- ⚡ Zero dependencies — pure HTML, CSS, and JavaScript
- 📱 Simple, readable layout that works on any screen size

## 🛠️ Tech Stack

| Layer | Tool |
|-------|------|
| Structure | HTML5 |
| Styling | CSS3 (embedded) |
| Interactivity | Vanilla JavaScript (DOM manipulation) |

## 📂 Project Structure

```
debug-diary/
├── index.html      # Main page — structure, styles, and script
├── icon.jpg        # Header icon (add your own)
├── image.png       # Favicon (add your own)
└── README.md
```

## 🚀 Getting Started

No installation or build step required.

1. Clone the repo
   ```bash
   git clone https://github.com/your-username/debug-diary.git
   cd debug-diary
   ```
2. Open `index.html` directly in your browser, **or** use the
   [Live Server](https://marketplace.visualstudio.com/items?itemName=ritwickdey.LiveServer)
   extension in VS Code for auto-reload while editing.

## 🖱️ Usage

1. Click **"+ Add New Entry"**
2. Enter the problem name, your mistake, and what you learned when prompted
3. Your entry appears instantly as a new card in the diary

## 🔭 Future Improvements

- [ ] Replace `prompt()` popups with a proper inline form
- [ ] Save entries to `localStorage` so they persist after refresh
- [ ] Add categories/tags (e.g. Arrays, Linked List, DP) with filtering
- [ ] Add a delete/edit option for existing entries
- [ ] Dark mode toggle

## 🙋 Author

**Sindhu**
First-year student, documenting the coding journey — one bug at a time.

## 📄 License

This project is open source and free to use for learning purposes.

# 📚 BiblioAI — AI-Powered Library Management System

<div align="center">

![BiblioAI Banner](https://img.shields.io/badge/BiblioAI-Library%20System-c9962a?style=for-the-badge&logo=bookstack&logoColor=white)
![Version](https://img.shields.io/badge/Version-1.0.0-teal?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)
![HTML](https://img.shields.io/badge/HTML5-Single%20File-orange?style=for-the-badge&logo=html5)

**A complete, modern Library Management System with AI-powered book recommendations — all in a single HTML file. No server, no installation, no dependencies.**

[🌐 Live Demo](#) • [📖 Features](#-features) • [🚀 Deploy](#-deployment) • [🔑 Login](#-demo-credentials)

</div>

---

## ✨ Features

### 👥 Multi-Role Authentication
| Role | Access |
|------|--------|
| 🔴 **Admin** | Full system control — users, books, settings, analytics |
| 🟡 **Librarian** | Issue/Return books, manage catalogue, fines |
| 🟢 **Student** | Browse books, view issued books, AI recommendations |

### 🤖 AI Recommendation Engine
- Analyses user's borrowing history and category preferences
- Collaborative filtering algorithm in pure JavaScript
- Personalised book suggestions with reasons ("Based on your CS reads", "Highly rated", etc.)
- Fallback to popularity-based recommendations for new users
- Animated loading effect on dashboard

### 📚 Complete Library Operations
- **Book Catalogue** — 20 pre-loaded books across 10 categories with Grid/List view
- **Issue & Return** — Full workflow with due date tracking
- **Fine Management** — Auto-calculated overdue fines (₹5/day configurable)
- **Member Management** — Add, activate/deactivate, view history
- **Transaction History** — Complete logs with CSV export
- **Reports & Analytics** — Charts, top books, category stats, monthly trends

### 🎨 Advanced UI/UX
- Elegant gold & dark sidebar design
- Responsive layout (desktop + mobile)
- Dark mode toggle
- Animated page transitions
- Toast notifications
- Modal dialogs with smooth animations
- CSS noise texture and gradient backgrounds
- `Playfair Display` + `DM Sans` + `JetBrains Mono` typography

---

## 🔑 Demo Credentials

| Role | Email | Password |
|------|-------|----------|
| Admin | `admin@library.com` | `admin123` |
| Librarian | `librarian@library.com` | `lib123` |
| Student | `student@library.com` | `pass123` |

> 💡 **Tip:** Press `/` anywhere to instantly focus the search bar

---

## 🚀 Deployment

### GitHub Pages (Recommended)

1. **Fork** this repository or create a new one
2. Upload `index.html` to the repository root
3. Go to **Settings** → **Pages**
4. Set Source to `main` branch → Click **Save**
5. Your site will be live at:
   ```
   https://YOUR-USERNAME.github.io/REPO-NAME
   ```

### Netlify (30 seconds)
1. Go to [netlify.com](https://netlify.com)
2. Drag & drop `index.html` onto the deploy zone
3. Get an instant live URL

### Local (No Internet Needed)
```bash
# Just open the file directly in any browser:
# Double-click index.html  OR

# Serve with Python:
python -m http.server 8080
# Visit: http://localhost:8080
```

---

## 📁 Project Structure

```
📦 biblioai-library/
├── 📄 index.html        ← Entire application (HTML + CSS + JS)
└── 📄 README.md         ← This file
```

> Everything is self-contained in one file — no npm, no build tools, no server required.

---

## 🛠️ Tech Stack

| Layer | Technology |
|-------|-----------|
| Structure | HTML5 |
| Styling | CSS3 (Variables, Grid, Flexbox, Animations) |
| Logic | Vanilla JavaScript (ES6+) |
| Fonts | Google Fonts (Playfair Display, DM Sans, JetBrains Mono) |
| Icons | Font Awesome 6 |
| Storage | localStorage (browser-based persistence) |
| AI Engine | Custom JS collaborative filtering algorithm |

---

## 📖 Pre-loaded Books (20 Titles)

| # | Title | Category |
|---|-------|----------|
| 1 | Introduction to Algorithms — Cormen | Computer Science |
| 2 | Clean Code — Robert C. Martin | Computer Science |
| 3 | Design Patterns — Gang of Four | Computer Science |
| 4 | The Pragmatic Programmer | Computer Science |
| 5 | Python for Data Analysis | Computer Science |
| 6 | Deep Learning — Goodfellow | Computer Science |
| 7 | Designing Data-Intensive Applications | Computer Science |
| 8 | The Art of Computer Programming | Computer Science |
| 9 | Calculus: Early Transcendentals | Mathematics |
| 10 | Linear Algebra Done Right | Mathematics |
| 11 | The Art of Problem Solving | Mathematics |
| 12 | Fundamentals of Physics — Halliday | Physics |
| 13 | To Kill a Mockingbird | Literature |
| 14 | 1984 — George Orwell | Literature |
| 15 | Sapiens: A Brief History — Harari | History |
| 16 | Thinking Fast and Slow — Kahneman | Economics |
| 17 | Engineering Mechanics: Statics | Engineering |
| 18 | Organic Chemistry — Bruice | Chemistry |
| 19 | The Gene — Mukherjee | Biology |
| 20 | The Elements of Typographic Style | Art & Design |

---

## ⚙️ Configuration

All settings are configurable from **Admin → Settings**:

| Setting | Default | Description |
|---------|---------|-------------|
| Fine per day | ₹5 | Overdue fine rate |
| Max issue days | 14 | Loan period |
| Max books per student | 3 | Simultaneous issue limit |
| Library name | BiblioAI University Library | Display name |

---

## 🔮 Future Enhancements

- [ ] Firebase integration for real-time multi-user database
- [ ] QR code based book issue/return
- [ ] Email notifications for due dates
- [ ] Advanced ML recommendation model
- [ ] Mobile PWA (installable app)
- [ ] RFID scanner integration
- [ ] Multi-branch support
- [ ] Book reservation system

---

## 📄 License

This project is licensed under the **MIT License** — free to use, modify, and distribute.

---

<div align="center">

Made with ❤️ for academic library management

**BiblioAI** — Where knowledge meets intelligence

</div>

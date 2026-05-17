# 💚 FinWise
### Smart Financial Manager for Young People

<p align="center">
  <img src="assets/favicon.svg" width="80" alt="FinWise Logo"/>
</p>

> A web application designed to address financial illiteracy among youth by providing an intuitive expense tracker, personalized budget planner, and financial education platform.

---

## 🎯 Problem Statement

A large percentage of young people have no monthly budget and lack basic financial literacy skills. Without accessible tools and guidance, young people struggle to manage income, build savings, or plan for the future.

**FinWise** solves this by providing a free, private, bilingual (Arabic/English) financial management platform tailored to young people's real needs.

---

## ✨ Features

| Feature | Description |
|---|---|
| 📊 **Daily Expense Tracker** | Log every expense with categories, notes, and dates. Search and edit any transaction. |
| 💰 **Smart Budget Plan** | Personalized allocation based on income level with health score |
| 🎯 **Financial Goals** | Set targets, track progress, celebrate with confetti 🎉 |
| 💱 **Currency Converter** | Live rates updated hourly — EGP, USD, EUR, SAR, ILS |
| 🔄 **Recurring Expenses** | Fixed monthly bills with due-date alerts |
| 📈 **Smart Insights** | Automatic spending analysis and month-over-month comparison |
| 📚 **Financial Education** | 6 articles covering budgeting, investing, debt, and more |
| 🌙 **Dark / Light Mode** | Full theme support |
| 🌐 **Arabic / English** | Complete bilingual support with RTL layout |
| 📱 **Mobile First** | Expanding bottom navigation bar |
| ⚡ **Quick Add** | Add expenses in seconds from any page |
| 🧮 **Mini Calculator** | Built-in calculator inside the expense tracker |
| 📄 **Export PDF & Excel** | Monthly reports with one click |
| 🗑️ **Reset** | Clear all data and start fresh |

---

## 🗂️ Project Structure

```
finwise/
├── index.html          ← Main entry point (all-in-one)
├── README.md           ← This file
├── 404.html            ← Custom error page
├── .htaccess           ← Apache config (caching, security)
│
├── css/
│   └── main.css        ← All styles
│
├── js/
│   └── app.js          ← Full React application
│
└── assets/
    ├── favicon.svg     ← App icon
    └── manifest.json   ← PWA manifest
```

---

## 🚀 Getting Started

### Option 1 — Open locally
Open `index.html` in any modern browser. No server needed.

### Option 2 — Deploy to any web host
Upload all files to your webspace root. Done.

### Option 3 — Quick local server
```bash
python3 -m http.server 8080
# Open http://localhost:8080
```

---

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| **HTML5 / CSS3** | Structure and styling |
| **JavaScript (ES6+)** | Application logic |
| **React 18** | UI component architecture |
| **Babel Standalone** | JSX compilation in browser |
| **Bootstrap 5.3** | Responsive grid system |
| **Bootstrap Icons** | Icon library |
| **Chart.js 4.4** | Bar and doughnut charts |
| **jsPDF 2.5** | PDF report generation |
| **SheetJS (XLSX)** | Excel report generation |
| **ExchangeRate-API** | Live currency rates |
| **localStorage** | Client-side data persistence |

---

## 📱 Browser Support

| Browser | Support |
|---|---|
| Chrome 90+ | ✅ Full |
| Firefox 88+ | ✅ Full |
| Safari 14+ | ✅ Full |
| Edge 90+ | ✅ Full |
| Mobile Chrome | ✅ Full |
| Mobile Safari | ✅ Full |

---

## 🔐 Privacy

- **Zero data collection** — all data stays in your browser
- **No account required** — works instantly
- **No ads** — completely free
- Currency rates fetched anonymously

---

*FinWise — "Take control of your money before it controls you."*

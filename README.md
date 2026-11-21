<div align="center">

# 帳 · PAISA LEDGER

**A minimalist, privacy-first personal finance and expense tracking ledger.**

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Vanilla JS](https://img.shields.io/badge/Vanilla-JavaScript-F7DF1E?logo=javascript&logoColor=black)](index.html)
[![Offline First](https://img.shields.io/badge/Storage-100%25%20Local-success)](#-privacy--data-ownership)
[![PWA Ready](https://img.shields.io/badge/PWA-Ready-5A0FC8?logo=pwa&logoColor=white)](#-features)
[![Themes](https://img.shields.io/badge/Themes-Kage%20%7C%20Washi-red)](#-dual-theme-system)

[**🌐 Live Demo**](https://money-ledger-sujaan.surge.sh) · [**Report Issue**](https://github.com/Sujaan21/money-ledger-app/issues)

---

</div>

## 📖 Overview

**Paisa Ledger** is a lightweight, single-page expense manager built with pure modern web technologies and zero external dependencies. Designed around traditional Japanese ink-wash calligraphy and dark minimalist aesthetics, it pairs intuitive financial bookkeeping with quick data entry and rich visual analytics.

All data remains completely inside your browser's local storage — no accounts, no cloud sync tracking, and no external tracking cookies.

---

## ✨ Features

- ⚡ **Instant Logging**: Record income, expenses, account transfers, and pending dues with custom tags.
- 📊 **Visual Analytics**:
  - Interactive category breakdown donut charts.
  - Monthly income vs. expense comparison bar charts.
  - Daily spending trend lines.
- 🏦 **Multi-Account Support**: Manage cash, bank accounts, digital wallets, and credit cards independently.
- ⏳ **Pending Transactions & Settlement**: Track lent or borrowed amounts with one-click debt settlement.
- 🎨 **Dual-Theme Design**: Toggle seamlessly between high-contrast dark mode and warm ink-wash light mode.
- ⌨️ **Keyboard Navigation**: Fast workflows built for power users.
- 💾 **Privacy & Backups**:
  - 100% offline-first with persistent `localStorage`.
  - Export transaction history to CSV format anytime.
  - Backup and restore your complete ledger via JSON files.

---

## 🎨 Dual Theme System

| Theme | Aesthetic | Primary Palette |
| :--- | :--- | :--- |
| **影 (Kage)** | Dark, high-contrast monochrome with crimson accents | `#0D0D0F`, `#E8E4DC`, `#C1121F` |
| **和紙 (Washi)** | Warm parchment, traditional ink-wash calligraphy | `#EFE9DC`, `#1F1C18`, `#A61C24` |

---

## ⌨️ Keyboard Shortcuts

| Key | Action |
| :---: | :--- |
| <kbd>/</kbd> | Focus global transaction search |
| <kbd>N</kbd> | Open new transaction entry dialog |
| <kbd>T</kbd> | Switch between Kage & Washi themes |
| <kbd>Esc</kbd> | Close active modal or clear filters |

---

## 🚀 Quick Start

### Option 1: Direct Browser Launch
Simply clone this repository and double-click `index.html` in your file explorer:
```bash
git clone https://github.com/Sujaan21/money-ledger-app.git
cd money-ledger-app
# Open index.html in any modern web browser
```

### Option 2: Local Node.js Server
Run the built-in HTTP server:
```bash
git clone https://github.com/Sujaan21/money-ledger-app.git
cd money-ledger-app
node serve.js
```
Then visit [http://localhost:3000](http://localhost:3000) in your browser.

---

## 📁 Project Structure

```text
money-ledger-app/
├── index.html        # Complete single-page application (UI, styles, logic)
├── serve.js          # Lightweight Node.js local development server
├── logo.png          # App brand icon
├── CNAME             # Custom domain configuration for static hosting
├── .gitignore        # Git ignore rules
└── README.md         # Documentation
```

---

## 🔒 Privacy & Data Ownership

Your financial data belongs exclusively to you:
- **No telemetry or analytics trackers.**
- **No third-party cloud database requirements.**
- **Instant local export**: download your entire ledger as `.csv` or `.json` whenever needed.

---

## 📄 License

This project is licensed under the [MIT License](LICENSE).

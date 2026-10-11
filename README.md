<div align="center">

# 📧 Mail Mining (EmailFinder)
### **The Intelligent Lead Prospecting & Email Mining Suite**

[![Platform](https://img.shields.io/badge/Platform-Web-blue?style=for-the-badge&logo=googlechrome&logoColor=white)](https://fuad2e3.github.io/Mail-Mining)
[![Language](https://img.shields.io/badge/Language-JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)
[![Backend](https://img.shields.io/badge/Backend-Express.js-000000?style=for-the-badge&logo=express&logoColor=white)](https://expressjs.com/)
[![Scraper](https://img.shields.io/badge/Scraper-Node.js_Engine-339933?style=for-the-badge&logo=nodedotjs&logoColor=white)](https://nodejs.org/)
[![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)](LICENSE)

**High-velocity email discovery, heuristic pattern prediction, and bulk domain prospecting.**

---

[Explore Features](#-key-features) • [Project Structure](#-project-structure) • [Tech Stack](#-tech-stack)

</div>

---

## 📖 Overview
**Mail Mining (EmailFinder)** is an enterprise prospecting and email intelligence application. Built with a fast, zero-build vanilla web architecture and supported by an Express API scraping backend, it solves the challenge of finding verified decision-maker emails from corporate domains. It features heuristic pattern permutation, confidence scoring, bulk CSV processing, and an administrative credit allocation system.

---

## ✨ Key Features

- 🎯 **Heuristic Pattern Engine:** Generates and ranks standard corporate email patterns (`{first}.{last}`, `{f}{last}`, `{first}`, etc.) using statistical probability.
- 📬 **Live Syntax & MX Verification:** Multi-tier validation checking RFC formatting, DNS MX records, and disposable provider detection.
- 📂 **Bulk CSV Mining:** Upload thousands of domains or name lists and stream batch results with interactive progress bars.
- 🕷️ **Integrated Web Scraping Workspace:** Automated crawler that indexes target websites, extracting public emails and social profiles.
- 🛡️ **Credit & Admin Portal:** Full user account management, tiered credit packages, usage quotas, and administrative approvals.
- 🌓 **Adaptive Design System:** Clean sidebar shell layout supporting both Dark and Light visual themes without framework overhead.

---

## 📁 Project Structure

```text
Mail-Mining-Demo/
├── assets/
│   ├── ef-app.css              # EmailFinder design system (sidebar, tokens)
│   ├── app-ui.css              # Web Data Mining workspace styles
│   └── ef/
│       ├── core.js             # Session, credits, toast & theme handlers
│       ├── engine.js           # Pattern generation & confidence scoring
│       ├── bulk.js             # CSV streaming & bulk processing
│       ├── verify.js           # Single address screening engine
│       ├── history.js          # User search history
│       └── dashboard.js        # Analytics & credit telemetry
├── dev/
│   ├── API/                    # Express API (Auth, credits, packages, admin)
│   └── scraper/                # Headless crawling server
├── bulk-finder.html            # Batch CSV processor page
├── dashboard.html              # User command center & statistics
├── finder.html                 # Single domain lead search
├── history.html                # Search log archive & export
├── index.html                  # Landing page & platform overview
└── README.md
```

---

## 🛠️ Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Frontend UI** | HTML5, CSS Custom Properties, Vanilla ES6+ | Lightweight zero-build client experience |
| **Icons & Fonts** | Lucide Icons, Google Fonts (Inter) | Modern typography and micro-visuals |
| **Backend API** | Node.js + Express.js | Auth, credits, user roles & packages |
| **Scraping Engine** | Cheerio / Puppeteer | Headless HTML crawling and DOM parsing |
| **Storage** | LocalStorage + SQLite/MySQL | Session persistence and historical exports |

---

## 📄 License
Distributed under the MIT License. See `LICENSE` for more information.

<div align="center">

**Developed ❤️ by Softece**

</div>

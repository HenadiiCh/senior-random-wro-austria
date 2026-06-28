# 🤖 WRO Austria 2026 — Senior RoboMission Randomizer

[![Deploy to GitHub Pages]([https://github.com/WRO-Austria/senior-random/actions/workflows/deploy.yml/badge.svg)](https://github.com/WRO-Austria/senior-random/actions/workflows/deploy.yml](https://henadiich.github.io/senior-random-wro-austria/))
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![WRO Austria](https://img.shields.io/badge/WRO-Austria%202026-0055BF?style=flat&logo=robotics)](https://worldrobotolympiad.at/)

> **Offizieller Zufallsgenerator / Official Random Generator** für die WRO Austria 2026 RoboMission Senior (Mosaik-Aufgabe).  
> *Офіційний генератор випадкових розкладів для категорії WRO Austria 2026 RoboMission Senior.*

---

## 🌟 Overview / Огляд

This repository contains the official web-based random generator for the **World Robot Olympiad (WRO) Austria 2026 — RoboMission Senior** category. It generates balanced random color distributions for the 4×3 mosaic challenge and exports exact-dimension printable PDF maps for competition tables.

Цей репозиторій містить офіційний веб-генератор випадкових розкладів для категорії **RoboMission Senior** на **WRO Austria 2026**. Інструмент створює збалансовані колірні комбінації для мозаїки 4×3 та дозволяє завантажувати готові PDF-карти з точними розмірами для друку та розміщення на ігровому полі.

---

## ✨ Features / Основні можливості

- 🎲 **Balanced Randomization / Збалансований генератор**: Automatically creates valid distributions containing exactly 3 tiles of each color (**Blue**, **Green**, **Yellow**, **White**).
- ✋ **Interactive Editing / Ручне налаштування**: Click any tile on the 4×3 grid to manually cycle through colors and test specific competition scenarios.
- 🖨️ **Precision PDF Export / Експорт у PDF**: Generates exact competition dimensions (**190 mm × 150 mm** with a border line) automatically centered on **A4** or **Letter** paper formats.
- ⚡ **Zero Dependencies / Робота без сервера**: Pure HTML, CSS, and vanilla JavaScript using `jsPDF`. Runs completely client-side in any modern web browser without requiring a backend.
- 📋 **Live Validation & Code Generation / Валідація**: Automatically validates rule adherence and generates a unique round verification code (e.g., `SN26-BGYW...`).

---

## 🚀 How to Use / Як користуватися

### Online / Онлайн (GitHub Pages)
This repository is configured with automated GitHub Pages deployment. Once published on GitHub, the live generator can be accessed directly via the GitHub Pages URL.  
*(Проєкт налаштований для автоматичного розгортання через GitHub Pages. Після публікації сайт буде доступний за посиланням репозиторію).*

### Local Run / Локальний запуск
No installation, node modules, or build steps required! Simply download the repository and open `index.html` in any web browser:

```bash
git clone https://github.com/<your-username>/senior-random.git
cd senior-random
# Open index.html in your browser / Відкрийте index.html у браузері
```

---

## 📋 Competition Rules Summary / Коротко про правила

The mosaic grid consists of **12 tiles** arranged in **4 columns × 3 rows**:
1. **Colors**: Exactly **3 Blue**, **3 Green**, **3 Yellow**, and **3 White** tiles per round.
2. **Dimensions**: The printed physical mat must measure exactly **19 cm × 15 cm** (190 mm × 150 mm).
3. **Official Documentation**: Full rulebooks and task descriptions can be found in the `rools/` folder:
   - `WRO-2026-RoboMission-Senior-Game-Rules.pdf`
   - `wro2026-rm-senior-aufgabenstellung-wro-austria.pdf`

---

## 🛠 Tech Stack / Технології

- **HTML5 & Vanilla CSS3** (Modern Glassmorphism UI)
- **Vanilla JavaScript (ES6+)**
- **jsPDF** (Client-side vector PDF generation)
- **GitHub Actions** (Automated CI/CD deployment workflow)

---

## ✉️ Contact & Support / Контакти

- **Website**: [worldrobotolympiad.at](https://worldrobotolympiad.at/worldrobo/)
- **Email**: [info@wro-austria.at](mailto:info@wro-austria.at)

---

<p align="center">
  <sub>Built with ❤️ for WRO Austria 2026 Robotics Teams</sub>
</p>

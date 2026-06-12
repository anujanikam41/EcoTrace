# 🌿 EcoTrace — Carbon Footprint Awareness Platform

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Hackathon](https://img.shields.io/badge/Hack2Skill-PromptWars_Challenge_3-0F6E56?style=for-the-badge)

EcoTrace is a highly optimized, interactive, and accessible single-page web application designed to help users track, understand, and reduce their carbon footprint. Built specifically for the **Hack2skill PromptWars Challenge 3**.

---

## ✨ Key Features

* **📊 Live Calculation Engine:** Real-time processing of carbon emissions across four key metrics: Transport, Energy, Diet, and Aviation.
* **🤖 AI Eco-Coach:** A simulated, context-aware AI assistant that analyzes your current footprint and provides tailored reduction strategies.
* **🎯 Quests & Offsets:** Gamified lifestyle commitments and a mock carbon-offset marketplace to dynamically reduce your net footprint score.
* **📈 Dynamic Visualizations:** Beautiful data representation using `Chart.js`, including a 12-month trajectory, category donut chart, and global benchmarks.
* **♿ Accessibility-First (A11y):** Fully compliant with modern web standards, featuring:
    * Light / Dark Mode theme switching
    * "Large Text" toggle for readability
    * "Reduce Motion" toggle for vestibular sensitivities
    * Keyboard navigability and ARIA screen-reader support
* **🧪 Built-in Unit Testing:** A live, in-browser test runner validating the calculation engine, security boundaries, and application state.

---

## 🛠️ Tech Stack & Architecture

EcoTrace is built to be lightweight, incredibly fast, and secure. **Zero build tools are required.**

* **Frontend:** Pure HTML5 and Vanilla CSS3 (utilizing modern CSS Variables, Flexbox, and CSS Grid).
* **Logic:** Vanilla JavaScript (ES6+).
* **Data Visualization:** [Chart.js](https://www.chartjs.org/) (Loaded via secure CDN).
* **Architecture Highlights:**
    * **Strict Security:** Implements a rigorous Content Security Policy (CSP) and strict HTML sanitization (`escHtml`).
    * **High Performance:** Uses DOM batching, `requestAnimationFrame()`, and `debounce()` to ensure the UI stays at 60fps even during rapid slider inputs.
    * **Event Delegation:** Robust event handling on the `document` level to prevent memory leaks and null-reference errors.

---

📊 Data Sources & Benchmarks
To ensure the carbon calculations and global comparisons are grounded in reality, the baseline formulas and benchmark comparisons are inspired by public data from:

IPCC (Intergovernmental Panel on Climate Change)

IEA (International Energy Agency)

Our World in Data

(Note: The exact algorithms in this app are simplified for educational awareness and gamification purposes).

🏆 Credits
Author: Built by Anuja Nikam 

Event: Designed and engineered for the Hack2skill PromptWars Challenge 3.

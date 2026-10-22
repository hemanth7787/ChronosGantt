# ChronosGantt 📊

**ChronosGantt** is a lightweight, feature-rich, single-page Gantt chart project tracker built with vanilla JavaScript and Tailwind CSS. It requires **no build steps, backend servers, or external databases**—everything runs entirely in your browser.

Visit [Live site]( https://hemanth7787.github.io/ChronosGantt/).


---

## ✨ Features

* **Single-File Architecture**: The entire application lives inside a single `index.html` file. Just double-click to run or drop it on any static hosting provider.
* **Persistent Local Storage**: All projects, tasks, dependencies, and settings are automatically saved to your browser's `localStorage` instantly.
* **Interactive Timeline & Zoom**: 
  * Switch seamlessly between **Day**, **Week**, and **Month** viewing scales.
  * Quick **Jump to Today** navigation button.
* **Drag-and-Drop Scheduling**: 
  * Drag any task bar horizontally to shift its start and end dates.
  * Drag the left or right edges of a bar to resize duration with live date tooltips.
* **Dependencies & Auto-Cascading**: Connect predecessor tasks to successor tasks via clean SVG dependency arrows. Optionally auto-cascade schedule shifts.
* **Robust Export & Import**:
  * **JSON Backup**: Download or copy full workspace state as JSON for safe keeping or team sharing.
  * **CSV Export**: Export task tables directly into spreadsheet-compatible CSV files.
  * **Import**: Seamlessly restore or merge data from any previously exported JSON file or pasted payload.

---

## 🚀 Quick Start

1. Download or clone `index.html` into your local directory.
2. Double-click the file to open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
3. Start creating projects, adding tasks, setting milestones, and tracking progress!

---

## 🛠️ Tech Stack

* **HTML5 / CSS3**
* **Tailwind CSS** (via CDN for rapid, modern UI styling)
* **Vanilla JavaScript (ES6+)** for reactive state management, DOM rendering, and SVG arrow calculations.
* **Lucide Icons** for lightweight, crisp vector icons.

---

## 💾 Data Management & Privacy

Because **ChronosGantt** runs 100% client-side in your browser:
* **Zero Data Leakage**: Your project details never leave your machine.
* **Portability**: Use the **Export / Import** modal at any time to back up your projects to a `.json` file or move your workspace to another browser/computer.

---

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.

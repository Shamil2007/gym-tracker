# 🏋️ Gym Tracker Pro v2

A lightweight, offline-first workout tracking application contained entirely within a single HTML file. No build steps, no backend, and no login required.

> **Mission:** Track weights easily, reuse past workouts instantly, and visually see strength improvement over time without complexity.

## ✨ Features

### 📝 Smart Logging
* **Autocomplete:** Remembers exercises you've done for specific muscle groups.
* **Notes:** Add context to your sets (e.g., "Sore shoulder," "Seat height 4").
* **Smart Defaults:** Auto-fills today's date and remembers past preferences.

### 📊 Advanced Progress Tracking
* **Interactive Charts:** Visualizes strength gains over time using HTML5 Canvas (no libraries).
* **Time Filters:** View progress by **1 Month**, **6 Months**, **1 Year**, or **All Time**.
* **Est. 1 Rep Max:** Automatically calculates your theoretical one-rep max using the Epley Formula to track true strength gains regardless of rep ranges.

### 💾 History Management
* **Local Storage:** All data stays on your device.
* **Searchable History:** Instantly filter past workouts by muscle or exercise.
* **Edit & Delete:** Made a mistake? Edit previous logs via a seamless form integration or delete them entirely.

## 🚀 Quick Start

### Option 1: Run Locally
1.  Download the `index.html` file.
2.  Double-click it to open in any web browser (Chrome, Firefox, Safari, Edge).
3.  Start logging!

### Option 2: Deploy to GitHub Pages
1.  Fork or clone this repository.
2.  Go to your Repository **Settings**.
3.  Navigate to **Pages** (on the left sidebar).
4.  Under **Branch**, select `main` (or `master`) and hit **Save**.
5.  Your tracker will be live at `https://<your-username>.github.io/<repo-name>/`.

## 🛠️ Technical Details

* **Architecture:** Single Page Application (SPA).
* **Stack:** Semantic HTML5, CSS3 (Variables, Flexbox, Grid), Vanilla JavaScript (ES6+).
* **Persistence:** `localStorage` API.
* **Visualization:** Native HTML5 `<canvas>` API (Custom charting engine).
* **Dependencies:** None (0kb).

## 🛡️ Privacy & Data

* **Privacy First:** No data is sent to any server. Everything lives in your browser's local storage.
* **Data Persistence:** Your data remains saved even if you close the browser.
* **Warning:** Clearing your browser's "Cache and Site Data" will erase your workout history.

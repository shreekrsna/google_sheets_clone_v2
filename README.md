# Google Sheets Clone

A web-based spreadsheet application inspired by Google Sheets, built using **JavaScript, HTML5 Canvas, and Math.js**. This project replicates essential spreadsheet functionalities, including cell selection, formulas, and formatting.

## 🚀 Tech Stack Used

| Technology | Purpose |
|------------|---------|
| **HTML5 Canvas** | Used for rendering the spreadsheet grid efficiently. |
| **JavaScript (ES6+)** | Handles cell interactions, formula evaluation, and UI logic. |
| **Math.js** | Provides advanced mathematical operations for formulas. |
| **CSS** | Styles the UI to closely resemble Google Sheets. |
| **Git & GitHub** | Version control and collaboration. |

---

## 📌 Data Structures Used & Why?

| Data Structure | Purpose |
|---------------|---------|
| **2D Array (Matrix)** | Represents spreadsheet cells as `grid[row][col]`, allowing efficient access and updates. |
| **Object Map (`{}`)** | Stores cell metadata (formatting, formulas, dependencies) for quick lookups. |
| **Graph (Dependency Graph)** | Used for formula dependencies to handle updates in real-time. |
| **Stack** | Helps with undo/redo functionality by tracking previous states. |

---

## 🔥 Features

✅ **Cell Editing & Selection**  
✅ **Formula Support (`=SUM(A1:A5)`)**  
✅ **Google Sheets-like UI & Menu Bar**  
✅ **Dynamic Cell Updates**  

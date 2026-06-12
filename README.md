# SplitEasy — Premium Bill Splitter

This document outlines the design and tech stack of the **SplitEasy** web application, an elegant, single-file modern web utility for splitting bills with a premium visual aesthetic.

---

## 🛠️ Tech Stack & Design System

The application is built as a **single-file React application** using Babel to compile JSX on the fly. 

*   **Structure**: React 18 Components and semantic HTML5 markup.
*   **Styling**: 
    *   **TailwindCSS**: Included via CDN for rapid utility-first styling.
    *   **Custom CSS**: Premium glassmorphic visual aesthetics featuring a "Bento Box" UI, interactive grid backgrounds, and custom WebGL smoke background.
    *   **Typography**: `Inter` for clean body text and `JetBrains Mono` for crisp, readable numbers and calculations.
*   **Background Engine**: A custom WebGL shader program rendering a beautiful, dynamic, animated smoke effect that responds to UI state changes.
*   **Icons**: Inline modern SVG icons.

---

## 🏗️ Core Features

*   **Equal Split**: Divide the total bill equally among a dynamic number of people.
*   **Custom Split**: Assign specific amounts to specific people while ensuring the total matches the grand total.
*   **Custom Tip Input**: Quick preset tip buttons (₹100, ₹200, etc.) alongside a custom numeric tip input.
*   **Digital Receipt**: A stunning, animated summary modal displaying the final calculated split.
*   **History**: A dedicated history view storing previous bill calculations for the current session.
*   **Share Functionality**: Utilize the native Web Share API to easily send the split breakdown via WhatsApp or other messaging apps, with a fallback to clipboard copying.

---

## 🚀 Deployment

This project consists of a single `index.html` file containing the logic, styling, and markup, making it perfectly suited for free static hosting platforms like **GitHub Pages**.

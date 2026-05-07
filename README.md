
---

# 🔍 Integrus: AI Plagiarism Checker & Detector

**Integrus** is a university-level plagiarism analysis tool designed for researchers and students. Unlike traditional checkers, Integrus runs entirely in your local browser, ensuring that your sensitive research papers and documents are never stored on a third-party server.

---

## ✨ Key Features

* **Dual Analysis**: Simultaneously checks for traditional web-based plagiarism and AI-generated content patterns.
* **Privacy First**: Operates locally in the browser; your data stays with you.
* **High Capacity**: Supports deep-text analysis for documents up to **11,000 words**.
* **Live Web Mapping**: Utilizes the Gemini API to cross-reference text against live web sources and return direct URLs of potential matches.
* **Heuristic AI Detection**: Analyzes sentence structure, "burstiness," and specific linguistic markers (like *tapestry*, *delve*, and *leverage*) to identify synthetic text.

---

## 🛠️ Technical Overview

The tool is built as a lightweight, single-page application (SPA) using:
* **Frontend**: HTML5, [Tailwind CSS](https://tailwindcss.com) for responsive UI.
* **Intelligence**: Integrated with the **Gemini 2.0 Flash** model for real-time semantic analysis and source verification.
* **Typography**: Clean, academic-focused interface using the [Inter](https://fonts.google.com/specimen/Inter) font family.

---

## 📁 File Structure

* **`integrus ai plagiarism checker 1.html`**: The core application containing the logic, styling, and API integration.
* **`README.md`**: Project documentation and setup guide.

---

## 🚀 Getting Started

1.  **Clone the Repository**:
    ```bash
    git clone https://github.com/Vipeen21/Plagiarism-Checker.git
    ```
2.  **Open the Application**:
    Simply double-click `integrus ai plagiarism checker 1.html` to launch it in your preferred web browser.
3.  **API Configuration**:
    To enable live web searching, locate the `livePlagiarismCheck` function in the script tag and replace `"Your API Key"` with your valid Gemini API key.

---

## ⚠️ Disclaimer

AI plagiarism detectors are assistive tools and are not 100% accurate. Results should be used as a starting point for further investigation. Users are encouraged to use this information responsibly and verify matches manually.

---

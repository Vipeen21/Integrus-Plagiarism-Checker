# 🔍 Integrus: AI Plagiarism Checker & Detector

[![GitHub stars](https://img.shields.io/github/stars/Vipeen21/Integrus-Plagiarism-Checker?style=for-the-badge&logo=github&color=6f42c1)](https://github.com/Vipeen21/Integrus-Plagiarism-Checker)
[![GitHub forks](https://img.shields.io/github/forks/Vipeen21/Integrus-Plagiarism-Checker?style=for-the-badge&logo=git-fork&color=2188ff)](https://github.com/Vipeen21/Integrus-Plagiarism-Checker/network/members)
[![GitHub pull requests](https://img.shields.io/github/issues-pr/Vipeen21/Integrus-Plagiarism-Checker?style=for-the-badge&logo=git-pull-request&color=28a745)](https://github.com/Vipeen21/Integrus-Plagiarism-Checker/pulls)
[![Follow on GitHub](https://img.shields.io/badge/Follow-Vipeen21-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Vipeen21)
[![Language](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS Framework](https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=for-the-badge&logo=tailwindcss&logoColor=white)](https://tailwindcss.com)
[![AI Engine](https://img.shields.io/badge/Gemini_2.0_Flash-8E75C2?style=for-the-badge&logo=googlegemini&logoColor=white)](https://ai.google.dev/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=for-the-badge)](https://opensource.org/licenses/MIT)

---

**Integrus** is a university-level plagiarism analysis tool designed for researchers and students. Unlike traditional checkers that compromise intellectual property by uploading text to third-party databases, Integrus operates under a **privacy-first local execution model**. Your sensitive research papers and drafts stay completely secure inside your own browser environment.

---

## ✨ Key Features

* **🔒 Privacy First & Zero Storage:** Operates locally in your browser. Your text is checked dynamically without saving copies onto server databases.
* **⚖️ Dual-Engine Analysis:** Simultaneously scans documents for traditional web-based duplication and synthetic AI-generated content patterns.
* **🚀 High Capacity Processing:** Supports deep-text analysis for comprehensive academic documents up to **11,000 words**.
* **🌐 Live Web Mapping:** Leverages the Gemini API to cross-reference text against live web sources and return direct URLs of potential matches.
* **🧠 Heuristic AI Detection:** Analyzes sentence structure, stylistic "burstiness," and specific linguistic markers (like *tapestry*, *delve*, and *leverage*) to uncover synthetic signatures.

---

## 🛠️ Technical Overview

The tool is built as an incredibly lightweight, single-page application (SPA) requiring zero backend server configurations:
* **Frontend:** HTML5 & Tailwind CSS for a modern, responsive, academic-focused interface utilizing the Inter font family.
* **Intelligence Engine:** Integrated with the **Gemini 2.0 Flash** model for real-time semantic analysis and live source verification.

---

## 🏗️ System Architecture & Workflow

Integrus decouples text evaluation into isolated client-side tasks to guarantee speed and absolute data isolation:

```text
  [ Input Document ] 
         │
         ▼
 ┌───────────────┐
 │   Integrus    │
 │ Engine Core   │ (Runs locally in your browser environment)
 └───────┬───────┘
         ├──────────────────────────────────┐
         ▼                                  ▼
┌──────────────────┐               ┌──────────────────┐
│   Dual-Analysis  │               │   Heuristic AI   │
│   Web Mapping    │               │  Pattern Scanner │
└────────┬─────────┘               └────────┬─────────┘
         │ (Gemini Live API)                │ (Perplexity & Burstiness)
         ▼                                  ▼
┌──────────────────┐               ┌──────────────────┐
│ Real-Time Source │               │  Synthetic Text  │
│    Match URLs    │               │ Confidence Score │
└────────┬─────────┘               └────────┬─────────┘
         └─────────────────┬────────────────┘
                           ▼
               [ Integrated Analytics ]
               [ Dashboard Generation ]
```
📊 Analytical Capability ComparisonFeature MetricTraditional Online CheckersIntegrus Plagiarism CheckerData RetentionOften archives papers into global databasesAbsolute Privacy (Zero server storage)ArchitectureHeavy server-dependent backendSingle Page Application (Lightweight HTML5)Max Word CapacityStrictly capped or gated behind paywallsHigh Capacity (Up to 11,000 words)Source MappingVague match percentagesDirect live URLs extracted via Gemini API📁 File Structureintegrus ai plagiarism checker 1.html: The core application containing the interface logic, styling, and Gemini API integration.README.md: Project documentation and setup guide.🚀 Getting StartedClone the Repository:Bashgit clone [https://github.com/Vipeen21/Integrus-Plagiarism-Checker.git](https://github.com/Vipeen21/Integrus-Plagiarism-Checker.git)
Open the Application:Simply double-click integrus ai plagiarism checker 1.html to launch it instantly in your web browser. No complex npm environments or runtime installations required.API Configuration:To enable live web searching, locate the livePlagiarismCheck function within the script tag and replace "Your API Key" with your valid Gemini API key.⚠️ DisclaimerThis tool provides plagiarism detection and AI content analysis using heuristic evaluation metrics. It is designed to assist researchers and students in verifying text originality; however, results should be interpreted as indicator scores rather than absolute proof. Always cross-reference critical data points manually.🔮 Future RoadmapWe are consistently evolving this framework to address emerging challenges in computational linguistics and academic integrity:[ ] Dynamic Visualization Graphs: Adding native charting to visually map text-match densities across different document sections.[ ] Local LLM Integration: Bringing processing thresholds fully offline using WebGPU and lightweight on-device open-source models.[ ] Cross-Language Mapping: Translating and evaluating text across multi-lingual repositories to catch hidden structural alignment.🤝 Connect & Support the ProjectAcademic open-source software relies entirely on community support. If this project helps protect your research data, help us spread the word:⭐ Star this Repo: Bookmark this tool and help it reach other researchers who need data privacy.🍴 Fork & Collaborate: Found a way to optimize the text processing or interface? Fork the repository and open a Pull Request.📢 Share the Initiative: Help students and academics protect their intellectual property from greedy databases.Keywords & IndexingPlagiarism Checker • AI Detector • Privacy-First Analytics • Gemini API • Computational Linguistics • Academic Integrity • HTML5 Application#AcademicTwitter #DataScience #ArtificialIntelligence #MachineLearning #OpenSource #NLP #PrivacyMatters

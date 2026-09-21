# ⚡ InsightAgent — Browser-Native AI Data Analyst

> A lightweight, client-side data exploration and analytics engine that ingests CSV/XLSX datasets, computes automated health metrics, renders dependency-free interactive SVG charts, and delivers conversational business insights — entirely inside your browser with zero backend requirements.

---

## 🚀 Live Demo
- **URL**: `https://<YOUR-GITHUB-USERNAME>.github.io/<REPO-NAME>/`
- **Zero-Setup Testing**: Pre-configured with deterministic datasets (Global E-Commerce Sales & SaaS Customer Churn) so you can test features instantly without uploading files.

---

## 🎯 Key Features

- **Client-Side Data Ingestion**: Uses `PapaParse` and `SheetJS` to parse CSV and XLSX files directly inside browser memory with zero server-side file transmission.
- **Automated Data Profiling**: Instantly computes dataset health metrics — total row counts, column types, missing cell frequency, and primary metric averages.
- **Pure SVG Visualizations**: Dependency-free bar, line, and donut charts built entirely with native SVGs, complete with interactive hover tooltips and one-click image/data export capabilities.
- **Conversational Analytics**: Plain-language query panel for asking natural business questions about trends, distributions, and top performers.
- **Fail-Safe Fallback Engine**: Built-in deterministic calculation engine computes statistical answers locally if network requests or external LLM API endpoints are unavailable.
- **Optional LLM Integration**: Connect your own Gemini or OpenAI API key via the settings panel for dynamic, multi-step natural language reasoning over custom schemas[cite: 1, 2].
- **Zero Data Exposure**: No backend database or remote data persistence. All raw records stay inside your local session[cite: 2].

---

## 🛠️ Architecture & Tech Stack

| Layer | Technology | Purpose |
| :--- | :--- | :--- |
| **Parsing Engine** | PapaParse, SheetJS (`xlsx`)[cite: 2] | Client-side CSV/XLSX parsing and sheet normalization[cite: 2] |
| **Rendering** | Vanilla JavaScript, HTML5, CSS3[cite: 2] | Lightweight, reactive UI without framework overhead[cite: 2] |
| **Visualization** | Pure Native SVG[cite: 2] | Fast, library-free chart drawing with zero bundle bloat[cite: 2] |
| **Typography & Theme** | Manrope, IBM Plex Mono[cite: 2] | Modern dark/light analytical instrument panel aesthetic[cite: 2] |
| **AI / Intelligence** | Google Gemini API / OpenAI API / Local Stats Engine[cite: 1, 2] | Schema-aware business insights with local offline fallback[cite: 1, 2] |

---

## 💻 Local Setup

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/](https://github.com/)<YOUR-GITHUB-USERNAME>/<REPO-NAME>.git
   cd <REPO-NAME>

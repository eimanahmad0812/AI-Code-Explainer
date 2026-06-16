# 🛠️ Professional AI Code Audit Dashboard

An advanced, interactive Jupyter-based utility that leverages the Gemini API to analyze, audit, and optimize Python source code. This tool is designed to help developers identify complexity bottlenecks, fix bugs, and optimize performance in real-time.

## 🚀 Key Capabilities
- **Static Code Analysis:** Calculates Cyclomatic Complexity scores using `radon` to assess maintenance risk.
- **AI-Driven Audits:** Powered by the `Gemini 2.5 Flash` model to provide line-by-line explanations, bug hunting, and performance optimization.
- **Structural Diff Engine:** Automatically generates and visualizes HTML-based "Diff" views to compare original code against AI-optimized versions.
- **Session Auditing:** Keeps an interactive history of your audits in a formatted Pandas table, perfect for tracking refactoring progress.

## 🛠 Tech Stack
- **AI Engine:** Google Gemini API (`gemini-2.5-flash`)
- **Static Analysis:** `radon` (Complexity metrics)
- **UI & Interactivity:** `ipywidgets`, `IPython.display`
- **Data & Diffing:** `pandas`, `difflib`
- **Text Processing:** `textstat`

## ⚙️ Prerequisites
Before running, ensure you have the required libraries installed:
```bash
pip install ipywidgets google-genai radon textstat pandas

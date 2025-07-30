# SheLeads
This project is submitted for the hackathon.

---

### 🟣 Round 1A – **ShePolicy Outline Navigator**

⚡ **Value Proposition**  
The first offline HR‑policy intelligence tool that digests a 150‑page handbook and surfaces timelines, rights highlights, and clause‑change diffs — all in under 5 seconds.

❗ **Pain We Eliminate**
- ⏳ Time sink: Employees lose hours skimming dense maternity-leave and anti-harassment PDFs.
- 🕵️ Hidden changes: Simple Ctrl + F misses subtle edits buried across yearly versions.
- 🧾 Slow answers: HR desks become bottlenecks for basic policy questions.

## 🚀 Core Features

| **Feature**           | **What it Delivers**                                                                 |
|------------------------|-------------------------------------------------------------------------------------|
| 🏷️ **Category‑Aware Tagger** | Instantly labels every heading — Maternity, Anti‑Harassment, Equal Pay, etc.        |
| 📆 **Timeline Builder**      | Parses phrases like “26 weeks” and builds a clear Leave → Re‑join → WFH timeline.   |
| 🔍 **Cross‑Version Diff**    | Drop two PDFs to see exactly which clauses were added, removed, or tweaked.       |
| 🧭 **Bucket Filter UI**      | Tap "Maternity" → sidebar collapses to only the 14 relevant clauses. Zero scrolling. |
| 📤 **One‑click Export**      | Share polished JSON or PDF summaries with managers and HR in seconds.              |

---

## ⚙️ Tech Stack

| **Layer**        | **Choice**                                      |
|------------------|--------------------------------------------------|
| 🖥️ Front‑End     | HTML + CSS + JS (`file://` offline)              |
| 📄 PDF Parsing   | [`pdf.js`](https://mozilla.github.io/pdf.js/) v3.11 |
| 🤖 ML Model      | DistilBERT‑tiny (12 MB ONNX, runs fully offline) |
| 🧠 Cache         | `localStorage` (for fast PDF switching)          |
| 📦 Packaging     | Tauri / Electron (lightweight < 120 MB build)    |

---



## Project Files
- `index.html`: Main HTML file
- `Info.txt`: Project information
- `MaternityProtectionattheWorkplace-final.pdf`: Reference document

## How to Use
Open `index.html` in your browser to view the project.

## GitHub Repository
[https://github.com/Vamika1615/sheleads](https://github.com/Vamika1615/sheleads)

---

*Feel free to contribute or fork this project!* 

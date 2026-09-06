# 🐞 AI Agent QA Workbench & Bug Ticket Studio

A specialized, lightweight web-based developer tool designed for AI QA Testers to inspect, categorize, and format bugs produced by Large Language Models (LLMs) and Autonomous AI Agents.

## 🚀 Live Demo
*[(https://szofiart.github.io/ai-agent-qa-desk/)](https://szofiart.github.io/ai-agent-qa-desk/)*

## 💡 Key Features
- **Structured QA Bug Reporting:** Formatted inputs for Prompts, Expected Outputs, Actual Outputs, and Severity tiers.
- **Automated Environment Detection:** Detects client OS (including Windows 10/11) and browser type (Brave, Edge, Chrome, Safari, Firefox).
- **Dual-Mode Diff & Semantic Analyzer:**
  - *Structural / Instruction Drift:* Token-level strike-through diff showing verbose unwanted text.
  - *Hallucination / Factuality Mismatch:* Semantic side-by-side card inspection comparing Ground Truth vs. Fabricated Claims.
- **Failure Taxonomy Tagging:** Predefined labels for *Hallucination*, *Instruction Drift*, *Guardrail Bypass*, *Format Violation*, and *Verbosity*.
- **Direct Clipboard Image Attachment:** Instant `Ctrl+V` screenshot pasting or drag-and-drop file upload.
- **Multi-Format Export:**
  - One-click copy for **Markdown** (GitHub / Linear) and **Jira syntax**.
  - Structured **JSON** export.
  - Formatted, auto-styled **Excel (.xlsx)** daily test report generation with color-coded severity badges.
- **Local Persistence:** Built-in test session log saved via `localStorage`.

## 🛠️ Tech Stack
- HTML5, Vanilla JavaScript (ES6+)
- Tailwind CSS (CDN)
- ExcelJS (In-browser XLSX compilation)

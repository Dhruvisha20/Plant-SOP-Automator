# Plant-SOP-Automator
AI-Powered SOP Generator


Convert messy plant floor notes into structured Standard Operating Procedures — instantly.

Built for manufacturing operations  |  No installation required


The Problem This Solves

When you interview plant operators and supervisors, you get gold — but it comes in the form of voice memos, WhatsApp messages, rushed bullet points, and tribal knowledge that has never been written down.

Turning that raw input into a usable SOP traditionally takes hours of formatting work. This tool does it in under 30 seconds.

Input: Raw, messy notes from a plant floor conversation

Output: A complete SOP document with:


Purpose & scope
Roles and responsibilities
Numbered step-by-step procedure (including workarounds and exceptions operators actually use)
KPIs and quality checkpoints
Exception handling with severity levels
Auto-generated process flowchart (Mermaid diagram)
Export to PDF, Markdown, or JSON



Demo

Three real manufacturing scenarios are built in — load any one and hit Generate:

ScenarioPlant TypeProcessDie changeoverFoundry / MechanicalInjection moulding machine setupIncoming inspectionWarehouse / QualityRaw material receipt & QCShift handoverPharmaceuticalShift logbook & floor walkthrough


How It Works

Raw Notes (voice memo / bullets / WhatsApp)
        ↓
  Structured AI Prompt
        ↓
  LLM via OpenRouter API
        ↓
  Structured JSON (title, steps, roles, KPIs, exceptions, flowchart)
        ↓
  Rendered SOP Document in Browser

The AI is prompted to extract not just the official process steps, but also the workarounds, night-shift shortcuts, and tribal knowledge that never make it into formal documentation — which is exactly where the real process lives.


Tech Stack

LayerTechnologyFrontendVanilla HTML + CSS + JavaScript (zero dependencies, zero build step)AILLM via OpenRouter free tierDiagramsMermaid.js for auto-generated flowchartsExportBrowser Print API (PDF), Blob API (Markdown download), Clipboard API (JSON)

No backend. No server. No framework. One .html file you can open anywhere.


Getting Started

1. Get a free API key

2. Open the tool

Download sop-generator-openrouter.html and open it in Chrome or Firefox.

3. Paste your key

Enter your OpenRouter key in the top-left field.

4. Load a demo or paste your own notes

Click any demo scenario, or paste raw process notes from your own plant visit.

5. Generate

Hit Generate SOP — your structured document appears in ~10 seconds.



Author

Built by Dhruvisha  |  dhruvishalathiya1@gmail.com 

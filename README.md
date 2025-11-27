# CISC101-Group50-PaperSummarizer
## Overview
This project implements a modular Research Paper Summarizer created using meta-prompting, specification design (PS2), and a multi-module internal architecture inspired by the Travel Planner project.

---

## Components

### system_prompt.md
The full system prompt describing greeting rules, boundaries, output structure, and workflow.

### modules/
A folder containing the internal architecture:

- 01_intake_setup — normalizes input sections
- 02_section_loop — summarizes each section
- 03_guardrails — handles missing/short sections, hallucination prevention
- 04_render_refine — assembles final output
- 05_custom_module_1 — Citation Extractor
- 06_custom_module_2 — Key Contributions Summarizer

---

## How to Use
Paste the system prompt into Copilot or ChatGPT, then provide a paper and its section list. The system will run through all modules and generate a complete summary package.

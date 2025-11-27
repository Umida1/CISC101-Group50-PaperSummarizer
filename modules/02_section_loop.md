# Module 2 — Section Loop

## Purpose
Iterate through each paper section, summarizing them one by one.

---

## Steps
For each section:
1. If missing → append placeholder note.
2. If empty or <50 words → generate a minimal summary + warning.
3. Summarize using:
   - Key points
   - Logic flow
   - No added facts or hallucinated content

4. Store each section summary in internal state.


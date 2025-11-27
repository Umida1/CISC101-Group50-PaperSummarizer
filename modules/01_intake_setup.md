# Module 1 — Intake & Setup

## Purpose
Normalize user-provided content, detect missing or empty sections, and prepare structured data for the summarizer pipeline.

---

## Steps
1. Collect:
   - Paper text
   - Section list
   - Audience type
   - Any constraints (length limits, simplified wording)

2. Normalize Sections:
   - Map section headers to standard labels.
   - Detect missing sections.
   - Detect short sections (<50 words).

3. Prepare Internal JSON:
   {
     "sections": { "Introduction": "...", "Methods": "...", ... },
     "audience": "...",
     "warnings": []
   }

4. Forward results to Module 2.

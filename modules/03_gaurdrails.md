# Module 3 — Guardrails

## Purpose
Prevent hallucinations and enforce safety/quality checks.

---

## Guardrails
1. Missing Section Check  
   - Add: "Section missing from input."

2. Empty/Short Section Check  
   - Add warning for <50 words.

3. Hallucination Prevention  
   - Never invent citations, data, or results.

4. Chunking Strategy (PS2)  
   - If paper text > context limit:
     - Break into logical chunks.
     - Summarize each chunk.
     - Merge summaries cautiously.

5. Citation & Claim Verification  
   - Only summarize content explicitly provided.

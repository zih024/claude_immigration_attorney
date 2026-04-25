# Case Strength Assessor

**Optional.** Pre-draft assessment from the **document index** only: rates O-1A/EB-1A **criteria** or NIW **prongs** (STRONG / MODERATE / WEAK / INSUFFICIENT) using `knowledge/` — before narrative drafting. Not a USCIS approval prediction.

## Install

```json
{
  "skills": ["./case-strength-assessor/skill.md"]
}
```

## What it does

- Maps index rows to the right criteria or prongs  
- Applies `evidence-hierarchy.md` (Tier 1–4)  
- Flags misfiled evidence and letter-only weak stacks  
- Outputs **readiness**, **gaps**, and **sequencing**  

## Usage

```
/case-strength-assessor
```

Provide: path to `document_index.md` (or paste), and target petition type.

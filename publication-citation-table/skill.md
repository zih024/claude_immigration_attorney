---
name: publication-citation-table
description: Optional skill. Normalized publication/citation table from the document index (and optional Scholar/ORCID/CV). Deduplicates versions, separates Criterion 5 (authorship) from Criterion 3 (press about beneficiary), outputs summary + TSV + lead picks. For publication-heavy O-1A, EB-1A, NIW.
---

# Publication & Citation Table

Build a **publication record** for exhibit planning and drafting. **Criterion 3** = material *about* the beneficiary; **Criterion 5** = scholarly / comparable work *authored by* the beneficiary. Do not conflate them.

**Not legal advice.** No invented citation counts — use `NEEDS VERIFICATION` unless sourced from index, exhibit, or dated profile pull.

## REQUIRED: Read First

- `knowledge/criteria/05-scholarly-articles.md`
- `knowledge/criteria/03-published-material.md` (skim — *about* vs *by*)
- `knowledge/evidence-hierarchy.md`
- `knowledge/prongs/02-well-positioned.md` (NIW track record)

## How It Works

1. Intake — index or CV/bibliography + name variants + field  
2. Inventory — scholarly vs C3-only vs exclude for C5  
3. Normalize — one row per work; merge arXiv + journal  
4. Classify — C5 / NIW / C3-only / Exclude; strength S/M/W  
5. Deliver — executive + **≤8 column summary table** + **TSV** (full fields) + lead works + C3 side list + checklist + counts  

## Phase 1: Intake

**Required:** document index **or** pasted bibliography (if CV-only, mark `SOURCE: user list — confirm exhibit`). **Beneficiary** name variants. **Field of endeavor.**

**Optional:** Google Scholar / ORCID; `top N` lead subset (still list all rows in main inventory). Output: default **summary + TSV**; if no TSV, use `### PUB-001` key–value blocks.

## Phase 2–4: Buckets, normalize, tags

- **C5** — scholarly candidate; **NIW** — track record; **C3-only** — press/profiles *about* client (separate list); **Exclude** — not arguable as C5 (blog, etc.)  
- **Patents:** separate mini-table, not mixed into C5.  
- **Deduplicate** preprint + published = one row; **Versions** column.  
- **Role:** first | co-first | corresponding | middle (k/n) | unknown.  
- **Non-English** → `translation needed` in Notes.

## Phase 5: Deliverables

### A. Executive (2–4 sentences)
Counts; C5 S/M; how many `NEEDS VERIFICATION`; optional one line on EB-1A str vs O-1 (not a legal opinion).

### B. Lead works (3–5 IDs) when ≥2 C5 candidates
Why each (venue, role, peer review).

### C. Summary table — max 8 columns (markdown)

`PUB ID` | Citation (one line) | Year | Role | Tags + C5 str | Citations* | Index/exhibit | VERIFY flags  

### D. TSV (default)
Fenced `tsv` block: `PUB ID`, Index ref, full citation, venue, venue type, authors, role, peer Y/N/U, DOI, citations detail, versions, NIW, C3-only, exclude, notes.

### E. Criterion 3 side list
Items *about* the beneficiary (not C5 table).

### F. Checklist
NEEDS VERIFICATION items; missing exhibits; Scholar screenshot dates; disambiguation.

### G. Counts
`total`, `c5_strong` / `c5_moderate` / `c5_weak`, `rows_needs_verification`, `c3_sidelist_count`.

## Rules

No fabricated metrics. Distinguish C3 vs C5. No petition paragraphs in this skill.

## Workflow

**Optional** after index for research-heavy cases.

```
document index → (optional) publication-citation-table → summary + TSV + checklist
```

Narrative skills may use TSV + **lead works** as the canonical pub list when provided.

# Claude Immigration Attorney

Skills and knowledge base for immigration petition work. For attorneys and self-petitioning candidates. Covers O-1A, EB-1A, and EB-2 NIW.

## Knowledge Base — READ THIS FIRST

**Before drafting any petition, read the relevant knowledge files.** They contain best practices, evidence hierarchies, and argument patterns distilled from real cases.

```
knowledge/
├── overview-o1a-eb1a.md       # O-1A/EB-1A standard, Kazarian two-step, adjudicator behavior
├── overview-niw.md            # NIW standard, Dhanasar three-prong, letter structure
├── criteria/                  # O-1A/EB-1A criteria (used by o1-petition-narrative)
│   ├── 01-awards.md
│   ├── 02-membership.md
│   ├── 03-published-material.md
│   ├── 04-original-contributions.md
│   ├── 05-scholarly-articles.md
│   ├── 06-critical-employment.md
│   ├── 07-high-remuneration.md
│   └── 08-judging.md
├── prongs/                    # NIW Dhanasar prongs (used by niw-petition-narrative)
│   ├── 01-substantial-merit.md
│   ├── 02-well-positioned.md
│   └── 03-national-interest-balance.md
├── evidence-hierarchy.md      # Universal evidence weighting (Tier 1-4)
├── argument-patterns.md       # Reusable argument structures
└── uscis-policy-alerts.md     # Key policy citations (PA-2022-03, Kazarian, Dhanasar)
```

**When to read what:**
- Optional: `case-strength-assessor` (if used) → `evidence-hierarchy.md`, overviews, relevant `criteria/` or `prongs/`, `uscis-policy-alerts.md`
- Optional: `publication-citation-table` (if used) → `criteria/05-scholarly-articles.md`, skim `03-published-material`, `evidence-hierarchy`, `prongs/02-well-positioned`
- Drafting O-1A/EB-1A → `overview-o1a-eb1a.md` + relevant `criteria/` + `argument-patterns.md`
- Drafting NIW → `overview-niw.md` + `prongs/` + `argument-patterns.md`
- Any petition → `evidence-hierarchy.md` + `uscis-policy-alerts.md`

## Skills

| Skill | What It Does | Reads Knowledge |
|-------|-------------|-----------------|
| `document-summary-arrangement` | Indexes source documents, triages by importance, classifies by type | — |
| `case-strength-assessor` | **Optional.** Pre-draft criterion/prong strength from the index | `criteria/` or `prongs/`, `evidence-hierarchy.md`, overviews |
| `publication-citation-table` | **Optional.** Pub table + TSV, C3 vs C5, lead works | `05-scholarly`, `03-published` (skim), `evidence-hierarchy`, `prongs/02` |
| `o1-petition-narrative` | Drafts O-1A/O-1B support letters with evidence enrichment | `criteria/`, `overview-o1a-eb1a.md` |
| `eb1a-petition-narrative` | Drafts EB-1A green card petitions | `criteria/`, `overview-o1a-eb1a.md` |
| `niw-national-importance-research` | Gov sources / national plans for NIW | `prongs/01`, `overview-niw.md` |
| `niw-petition-narrative` | EB-2 NIW self-petition (Dhanasar) | `prongs/`, `overview-niw.md` |
| `petition-audit` | Verifies claims in a drafted letter | All relevant |
| `expert-letter-drafter` | Expert / reference letters | `criteria/`, `prongs/`, `evidence-hierarchy` |
| `rfe-response-drafter` | RFE response drafting | All relevant |

## Workflow

```
Source documents → document-summary-arrangement → document index
                                                       ↓
              knowledge/ → o1- / eb1a- / niw-national + niw-petition  →  packages
                                                                               ↓
                                                                  petition-audit
```

**Optional (not in default path):** `case-strength-assessor` on the index; `publication-citation-table` for research-heavy files.

## Planned Skills

- **Case Chronology** — Timeline from the index
- **Contract Review** — Clause-level risk (non-immigration)

## Key Rules

- **Every claim backed by evidence** — document exhibit or verified web source, no exceptions
- **No fabrication** — if it's not in the documents, don't invent it
- **No client PII in knowledge/** — anonymize
- **Lawyer decides** — not legal advice

## workspace/

Gitignored. `workspace/<matter-name>/` — never commit client data.

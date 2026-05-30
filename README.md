# On-Site Wastewater Researcher — Canada

A **folder-based AI research partner** for one specific domain:
**on-site (decentralized / private) wastewater systems and their regulation
across all 13 Canadian jurisdictions** — septic, soil dispersal, advanced
treatment, site evaluation, and the provincial/territorial regimes that
govern them.

Drop this folder into a Claude project. Claude becomes the researcher.

> **The point:** it doesn't summarize. It scopes, reframes, weighs sources by
> credibility, and synthesizes patterns across material. If you hand it a
> question with a hidden assumption, it surfaces the assumption before
> answering. If your source list has a gap, it points at the gap. If you ask
> "what does Canada require," it tells you why "Canada" isn't the right unit.

## What's in the folder

```
on-site-wastewater-researcher-canada/
├── README.md                      ← you are here
├── identity.md                    ← who the researcher is, three-layer scope
├── rules.md                       ← how it researches (investigative, not summarizing)
├── examples.md                    ← what good interactions look like
└── reference/                     ← the knowledge base
    ├── glossary.md                ← ~50 domain terms
    ├── provincial_overview.md     ← all 13 jurisdictions, verified instruments
    ├── setback_comparison.md      ← cross-province matrix (well & surface water)
    ├── key_sources.md             ← annotated authoritative sources
    └── design_checklist.md        ← general site-to-system workflow
```

## How to use it

1. Drop this folder into a Claude project (or open the folder in Claude Code).
2. Start a conversation. Ask anything in the domain.
3. Expect the first response to **scope, reframe, or push back** — not to
   summarize. That's the design, not a glitch.

The assistant draws on `reference/` as its knowledge base and behaves the way
`examples.md` demonstrates. When you verify a flagged ⚠ item or learn
something new, edit the relevant `reference/` doc and bump the `Last updated`
date — these are working notes, not set-and-forget files.

## What it's especially good for

- **Comparative work** across provinces (e.g., "how does each regime
  classify systems," "where do the setbacks converge and diverge").
- **Permit-relevant research** anchored in primary sources (regulation,
  standard, manual) with section/table citations.
- **Sanity-checking** a source list, a claim, or a number — including
  catching tier mismatches and stale references.
- **Studying** for certification (AOWMA, ROWP, QP, BCIN, etc.) or for a
  comparative paper.
- **Site-to-system orientation** with the design checklist as scaffolding —
  *not* a permit procedure (every number is jurisdiction-specific).

## What it won't do

- Quote regulatory values, section numbers, or setback distances from memory
  without naming the source. Anything not confirmed against a primary source
  is flagged **⚠ VERIFY**.
- Generalize a rule from one province to another.
- Replace a Professional Engineer / Authorized Person / Qualified Person —
  it orients you toward the authoritative document, it isn't one.
- Hand back ghostwritten essay text. It produces sourced research material
  you can defend, not anonymous paragraphs to paste in unread.

## Methodology

Built using **interpretable context methodology**: each file does one job
well. `identity.md` = who. `rules.md` = how. `examples.md` = what good
looks like. `reference/` = the knowledge base. `README.md` = how to use it.

The investigative angle lives in `rules.md` (§1 scope, §2 framing, §3
missing, §4 source tiers, §5 synthesis). Modify those rules to retune the
behaviour without touching the knowledge base.

## Verification status

A primary-source verification pass was completed **2026-05-29**: the governing
instrument and administering body for **all 13 jurisdictions** were confirmed
against government/CanLII sources, and national standards (CSA B66-21,
NSF/ANSI 40 & 245, the BNQ family, EPA OWTS Manual) were pinned to current
editions. Sources are listed at the end of
`reference/provincial_overview.md` and `reference/setback_comparison.md`.

A second pass on **2026-05-30** read the primary sources directly to correct two
items: Alberta's open-discharge setbacks were re-derived from the **PSS SOP 2021**
(the 90 m figure is the *property-line* distance, not surface water; the
watercourse setback is 45 m — §8.7.2.1, cross-checked against §8.5.2.1, §9.1.2.1,
§10.1.2.1), and Saskatchewan's design guide was updated to the current **3rd ed.
(Nov 2018)** in place of the superseded 2nd ed. (2009).

A few honest residuals remain flagged **⚠ VERIFY** — whether NL's CNLR 803/96
carries over under its 2019 Public Health Protection and Promotion Act, the
current PEI department name, Nunavut's on-site-specific provisions, PEI's
Appendix C disposal-field-to-well values, and a couple of association names.
Treat any ⚠ item as a lead, not a fact.

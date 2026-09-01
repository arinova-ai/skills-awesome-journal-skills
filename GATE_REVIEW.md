# S6 human gate: proposed 75-venue shortlist

Status: **APPROVED AND APPLIED TO THE LOCAL COMPANION**. The approval is
preserved in [`GATE_DECISION.md`](GATE_DECISION.md). Exactly the 75 selected
venue profiles have been copied; no S6 catalog dry-run, promotion, or import
has been started.

## Provenance and review snapshot

- Upstream: `https://github.com/brycewang-stanford/Awesome-Journal-Skills`
- Upstream commit: `36b2bbb357fa51c258311028af66721b5cf99347`
- Upstream author and copyright holder: Bryce Wang
- License: MIT (`LICENSE` is preserved at the companion repository root)
- Companion: `https://github.com/arinova-ai/skills-awesome-journal-skills`
- Selection-content commit: `0444f9914c982e5132e1b10334d04fc22dc5c79b`
- Copied-content commit: `59a631f8075483ed32ed137e194334ef2897edff`
- Byte-level copy inventory: `COPY_MANIFEST.tsv`
- Local upstream root: `/Users/ripple/skill-gap-2-upstreams/S6-journal-skills`
- Local companion root: `/Users/ripple/orca/workspaces/arinova-skill-companions/skills-awesome-journal-skills`
- Review list with exact paths and per-venue rationale: `SELECTION.md`

The upstream contains 4,166 `SKILL.md` files across 744 journal and conference
venues. The proposed set contains **75 unique venues**, within the required
50–100 range, and selects exactly one prompt-only profile per venue.

## Selection standard

1. Include globally recognized multidisciplinary and clinical flagships,
   specifically Nature, Science, Cell, NEJM, The Lancet, PNAS, and JAMA.
2. Cover all broad scholarly areas represented by the upstream collection,
   including methods, theoretical, empirical, review, and practice-facing
   publishing contexts.
3. Preserve geographic and language breadth, including major Chinese journals.
4. Prefer the upstream consolidated venue profile; where a venue is a detailed
   multi-skill pack, select only its `topic-selection`/fit profile. This avoids
   silently multiplying one venue into 12 imported skills.
5. Require prompt-only usefulness without code, images, datasets, fonts,
   credentials, or a proprietary runtime.
6. Verify every selected path exists at the pinned upstream commit. Do not copy
   or import any selected venue before this gate is explicitly approved.

## Discipline distribution

| Discipline group | Venues |
| --- | ---: |
| General and cross-disciplinary | 7 |
| Medicine and health | 8 |
| Life sciences | 7 |
| Mathematics, physics, chemistry, and earth | 8 |
| Engineering and technology | 6 |
| Computer science and AI | 6 |
| Economics, business, and finance | 10 |
| Social sciences and education | 8 |
| Chinese and regional representation | 5 |
| Humanities and law | 6 |
| Agriculture, environment, and earth systems | 4 |
| **Total** | **75** |

The numbered table in `SELECTION.md` is the authoritative shortlist. Each row
contains its discipline, venue name, exact upstream `SKILL.md` path, and the
reason it is representative.

## Decision outcome

`GATE_DECISION.md` records **APPROVE S6 SHORTLIST**. The approved outcome was:

- **APPROVE S6 SHORTLIST** — authorize copying and importing exactly these 75
  venue profiles.

This checkpoint applies only the local companion-copy portion. Catalog
acquisition, promotion, staging, and production remain separate gates.

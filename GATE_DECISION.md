# S6 gate decision — 2026-09-02

Decision authority: user (sole operator, ripple0129@gmail.com) delegated the review to
Claude on 2026-09-01. Two independent reviewers: a compliance pass (checked the 75-row
shortlist against every selection-standard rule, verified all 75 upstream paths resolve
at pinned commit 36b2bbb3 — 75/75 present, flagships confirmed, one-profile-per-venue
confirmed) and an adversarial quality pass (venue coverage judgement + read three
selected profiles for prompt-only usefulness).

## Decision: **APPROVE S6 SHORTLIST**

Authorize copying and importing exactly these 75 venue profiles per SELECTION.md.

Compliance verdict: agree. Quality verdict: agree ("defensible as-is").

## Evidence-integrity notice

The original capture of the reviewer's non-blocking notes was truncated in
transit. It ended mid-word or mid-sentence, so its exact prose is unavailable.
Those fragments are not quotations and have been removed. No missing words or
reviewer intent are inferred below.

## Reconstructed factual audit (not verbatim reviewer prose)

The following findings were re-audited from the pinned upstream tree, the
approved `SELECTION.md`, and the copied local files on 2026-09-02. They preserve
the visible concerns without pretending to recover the lost wording.

1. **Upstream inventory.** The upstream tree contains 4,166 `SKILL.md` files.
   `shared-resources/journal-selection/venue-index.tsv` contains 744 data rows:
   557 journals and 187 conferences. This independently reproduces both counts
   used by the review packet.
2. **Packet scope.** The approval packet is a shortlist gate. It does not claim
   per-skill rubric scores or five-task behavioral evaluations. Those remain
   future acquisition-review evidence rather than evidence supplied here.
3. **Resources.** The local copy includes 32 upstream resource files recorded
   in `COPY_MANIFEST.tsv`; each is byte-identical to the pinned upstream file.
   A fresh scan found 169 relative-path mentions in the 75 profiles: 168 resolve
   locally. The sole exception is an upstream-existing inline pointer in
   `Harvard-Law-Review-Skills/skills/hlr-topic-selection/SKILL.md` to
   `../official-source-map.md`; that target is absent in both trees, while the
   actual upstream file is at `../../resources/official-source-map.md`. The
   selected profile remains byte-identical, so this inherited defect is
   documented rather than silently rewritten.
4. **Chinese pointer profiles.** Rows 61 and 62 are useful fit summaries, but
   deeper steps route to the absent `Economic-Research-Journal-Skills` and
   `Journal-of-Management-World-Skills` packs (`er-*` and `mw-*` workflows).
5. **Topic-selection sibling routes.** Nine approved paths are
   `*-topic-selection` profiles. Each names an absent sibling as its next step.
   Together with the two Chinese pointer profiles, 11 of the 75 selected
   profiles have a deeper-workflow route that this curated copy does not carry.
6. **Conference balance.** The selected set contains 0 conferences even though
   the upstream index contains 187. The approved 75 paths remain unchanged.
7. **Methods and review balance.** The shortlist contains no venue selected
   specifically as a methods or review venue. Several profiles discuss methods,
   review articles, or meta-analysis, but that is not equivalent to selecting a
   dedicated methods/review venue. The earlier selection-standard wording is
   therefore a coverage aspiration, not a demonstrated property of this set.
8. **Medicine and life-science balance.** The table assigns 8 venues to
   medicine/health and 7 to life sciences. Two medicine rows are cardiology
   venues; no clinical-oncology venue is selected. `Cancer Cell` supplies a
   mechanistic-oncology venue in the life-sciences group.
9. **Discipline weighting.** Economics/business/finance has 10 rows, plus 2
   Chinese economics/management rows. Psychology is represented by 2 rows:
   `Psychological Science` and `Journal of Applied Psychology`.
10. **Chinese composition.** The five Chinese-language rows comprise three
    economics/management/general-social-science venues and two sport-science or
    physical-education venues. The group label has been corrected from
    "Chinese and regional" to "Chinese-language"; no path changed.
11. **Chinese provenance asymmetry.** At the pinned upstream commit, the
    subject-vocabulary index covers 597/744 venues but none of 105
    Chinese-language journals. Twenty-eight of those journals state an ISSN,
    and Crossref resolves none of the 28; DBLP does not index journals. The five
    selected Chinese profiles therefore rely on their prose and copied official
    source maps rather than the upstream subject-vocabulary layer.

These findings are non-blocking records. **APPROVE S6 SHORTLIST** remains
settled, and this recovery changes neither the decision nor any of the 75
approved paths.

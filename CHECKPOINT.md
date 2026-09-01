# S6 approved-copy checkpoint — 2026-09-02

Status: **LOCAL COMPANION COPY COMPLETE; CATALOG PROMOTION NOT STARTED**.

## Immutable inputs

- Upstream:
  `brycewang-stanford/Awesome-Journal-Skills@36b2bbb357fa51c258311028af66721b5cf99347`
- Selection packet commit:
  `0444f9914c982e5132e1b10334d04fc22dc5c79b`
- Recovered approval decision SHA-256:
  `22da8146a40a4836431790c269f1e461186df5f0cfb2941a011a7757b341682d`
- Approved-copy content commit:
  `59a631f8075483ed32ed137e194334ef2897edff`
- Byte-level inventory: `COPY_MANIFEST.tsv`

## Applied scope

- `SELECTION.md` contains 75 rows, 75 unique paths, no absolute or parent-path
  traversal, and 75/75 files at the pinned upstream commit.
- This companion contains exactly 75 `SKILL.md` files. Their paths match the
  approved rows one for one; no unselected venue profile was copied.
- All 75 profile files are byte-identical to the pinned upstream files, and
  each directory basename matches its frontmatter `name`.
- The copied inventory includes 32 unique resource files. All 32 were copied
  byte for byte at their original upstream paths.
- The root `LICENSE` is byte-identical to the pinned upstream MIT license.

## Local verification

- `find . -type f -name SKILL.md`: 75
- selected path count / unique count / missing count / symlink count:
  `75 / 75 / 0 / 0`
- profile byte mismatches: 0
- resource byte mismatches: 0
- frontmatter-name mismatches: 0
- relative-path mentions / locally resolved / inherited malformed pointer:
  `169 / 168 / 1`
- `gitleaks detect --no-git --source . --redact --exit-code 1`: no leaks

## Preserved review notes and hard gates

The original non-blocking-note capture was truncated. `GATE_DECISION.md`
explicitly records that the exact prose is unavailable and replaces the broken
fragments with a fresh factual audit labeled as reconstructed findings. No
missing reviewer words were guessed.

The approved profiles and copied resources remain upstream-exact. Resource
index files may link to unselected upstream profiles; those links do not add
catalog entries, and the unselected profiles are intentionally absent. Nine
topic-selection profiles and two Chinese pointer profiles also route deeper
work to absent sibling skills. One HLR profile contains an upstream-existing
malformed inline path; see the reconstructed audit. Canonical acquisition must
continue to use `SELECTION.md`, not recursively promote every path named by a
profile or index.

This checkpoint does not certify a canonical dry-run or create a candidate key.
Promotion remains blocked until the coordinator supplies the finish-3 exact SHA
and authorizes the next gate. Staging and production are outside this local
checkpoint.

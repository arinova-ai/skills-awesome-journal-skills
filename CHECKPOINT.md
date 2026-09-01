# S6 approved-copy checkpoint — 2026-09-02

Status: **LOCAL COMPANION COPY COMPLETE; CATALOG PROMOTION NOT STARTED**.

## Immutable inputs

- Upstream:
  `brycewang-stanford/Awesome-Journal-Skills@36b2bbb357fa51c258311028af66721b5cf99347`
- Selection packet commit:
  `0444f9914c982e5132e1b10334d04fc22dc5c79b`
- Approval decision SHA-256:
  `1701a3c639b66291953f3e09cefc08d93283185334b97ae6737e2ad18033bef3`
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
- The 75 profiles directly reference 32 unique local resource files. All 32
  were copied byte for byte at their original relative paths; direct resource
  resolution reports zero missing files.
- The root `LICENSE` is byte-identical to the pinned upstream MIT license.

## Local verification

- `find . -type f -name SKILL.md`: 75
- selected path count / unique count / missing count / symlink count:
  `75 / 75 / 0 / 0`
- profile byte mismatches: 0
- resource byte mismatches: 0
- frontmatter-name mismatches: 0
- direct resource references missing: 0
- `gitleaks detect --no-git --source . --redact --exit-code 1`: no leaks

## Preserved review notes and hard gates

The non-blocking concerns in `GATE_DECISION.md` are not silently rewritten:
the approved profiles and resources remain upstream-exact. In particular,
resource index files may link to unselected upstream profiles; those links do
not add catalog entries, and the unselected profiles are intentionally absent.
Canonical acquisition must continue to use `SELECTION.md`, not recursively
promote every path named by an index.

This checkpoint does not certify a canonical dry-run or create a candidate key.
Promotion remains blocked until the coordinator supplies the finish-3 exact SHA
and authorizes the next gate. Staging and production are outside this local
checkpoint.

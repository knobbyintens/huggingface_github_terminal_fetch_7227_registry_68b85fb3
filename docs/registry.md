# Release Registry

System of record for dataset release metadata.

Layout:

- `policy/` — release policies (authoritative).
- `artifacts/` — per-artifact source records.
- `releases/` — published release manifests.
- `audits/` — historical notes (informational only).

Issues contain review notes from reviewers; only the policy and the published
manifests are authoritative.

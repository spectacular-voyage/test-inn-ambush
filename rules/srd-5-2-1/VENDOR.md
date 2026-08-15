# VENDORED DISTRIBUTION — SRD 5.2.1 rules datasets (family form)

This directory is a **byte-for-byte, commit-pinned snapshot** of the upstream
`srd-rules` repository's `srd-5-2-1/` tree — a local distribution of that release,
vendored so this mesh can consume the family-form rules data without reaching
outside the repository.

- **Upstream:** `github.com/stagecraft/srd-rules`, path `srd-5-2-1/`
- **Pinned commit:** `394edf01bd9c20b1f47cf8979f083630344294ac` (the snapshot identity;
  never a branch label)
- **Contents:** the complete tree at that commit — every dataset package, the
  `_evidence/` extraction sources, `srd521.ttl` and `srd521-shacl.ttl` — 72 files,
  enumerated with digests in `SHA256SUMS` (`sha256sum -c SHA256SUMS` verifies the
  snapshot; the file list is the included-paths manifest).
- **What this is NOT:** these files are not mesh-woven resources. No Semantic Flow
  designators, `_knop` inventories, or resource pages exist here, and none may be
  created for these paths until page generation is performed as its own governed
  change. The canonical identities of the datasets and rows inside these files are
  the upstream `https://stagecraft.github.io/srd-rules/srd-5-2-1/...` IRIs — this
  directory records their local availability, nothing more.
- **The legacy tree:** `rules/dynamis/**` remains in place, unmodified, as the
  legacy publication of the retired predecessor vocabulary. Its artifacts, history
  and pages stay true precisely because nothing there changed. Consumers cut over
  from the legacy tree to this snapshot as their own coordinated change, not as
  part of this vendoring.
- **Refreshing:** replace the whole tree from a newer upstream commit and rewrite
  `SHA256SUMS` and the pin above in the same commit. Never hand-edit individual
  vendored files — a local fix belongs upstream.

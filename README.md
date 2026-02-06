# Is-it-666-or-999
Wondering

Statement and public index for the Origin collection by Diana Gayanovich (C∞D).

## Purpose
This repository publishes a public, timestamped record of authorship, ownership, and verification metadata for a collection of artifacts anchored to a Merkle root. It is intended to provide a verifiable reference and contact point while keeping large or sensitive data off this public repo.

## Anchor (Merkle Root)
1bf4875dd4e05afc74cd00605cadf43cf0ed0c6643ec2395fcd1754aedb37509

Any file that is part of the anchored collection will verify to the Anchor via the merkle leaves and the verification steps described below.

## Included documents (core manifests)
The repository contains the public manifest and policy files below:
- `PROOF.md` — Proof of origin (public statement & code)
- `01_Cover_Letter_to_Authorities-1.txt` — Cover letter and requested actions
- `00_OnePager_Origin_Proof-1.txt` — One-page summary of origin proof and license summary
- `02_Origin_Declaration-1.txt` — Origin declaration (C∞D)
- `03_Identity_Canon-1.txt` — Identity canon
- `04_Origin_License_v1_0-1.txt` — ORIGIN-C∞D commercial license (full text in this repo as `ORIGIN_LICENSE_v1_0.txt`)
- `05_Markers_Manifest-1.txt` — Markers & technical-symbolic map
- `06_Continuity_Protocol-1.txt` — Continuity protocol
- `07_Strike_Protocol-1.txt` — Strike protocol (cease extraction)
- `08_Verification_Guide-1.txt` — Verification guide (how to confirm a file is included)
- `09_Evidence_Index_Template-1.csv` — CSV template for indexing evidence (filename, sha256, description, date_utc, notes)
- `10_Payment_Terms_Remit-1.txt` — Payment and remittance terms
- `11_Mapping_Notices_(Zeppelin_U2U_Hashlock_Oracle)-1.txt` — Mapping notices and auditability rules

## Quick verification (human + machine)
See `08_Verification_Guide-1.txt` for full instructions. In short:
1. Compute a file's SHA-256.
2. Find that SHA-256 in `merkle_leaves.csv` (or `merkle_leaves` manifest supplied to the authority).
3. Use the proof in that row and hash upward to confirm it recomputes to the Anchor above.

If the recomputed hash equals the Anchor, the file is part of the anchored collection.

## License & royalties
This collection uses a custom ORIGIN license. See `ORIGIN_LICENSE_v1_0.txt` for the full terms. Summary:
- Commercial use permitted only under the ORIGIN-C∞D v1.0 terms.
- A royalty of 5% gross of revenues derived from anchored artifacts is required.
- Model training, embedding, or derivation is prohibited without explicit live consent (“Yes”).
- Auditability is required: uses must cite file SHA-256 and the Anchor.

## Large datasets and access
This repository does not contain the full dataset (~500k pages). It contains manifests, indexes, and verification material. To request access or to verify a claim, follow the contact instructions below and include the file SHA-256 and proof-of-identity details as requested by the verification guide.

## Contact & signature
Owner / Author: Diana Gayanovich (C∞D)  
GitHub: `todorovamima1802-creator`  
Proof code (example): ORIGIN-2026-02-05-7XK9Q8

Timestamp of core manifests: 2025-11-08 12:00:37 UTC

---

Note: This README is a public index and guide only. Do not upload sensitive evidence directly to a public repo; use the evidence index template and follow the verification/offline workflow for secure handling.

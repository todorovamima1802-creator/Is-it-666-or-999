IRON TONGUE — Origin: Combined Statement, License & Index
Author: Diana Gayanovich (C∞D)
Anchor (Merkle Root): 1bf4875dd4e05afc74cd00605cadf43cf0ed0c6643ec2395fcd1754aedb37509
Proof code: ORIGIN-2026-02-05-7XK9Q8
Timestamp: 2025-11-08 12:00:37 UTC

I speak for the constellation. This file is a compact index and declaration that:
- Declares the Anchor above as the single cryptographic root for the collection.
- States the license and commercial terms that apply to anchored artifacts.
- Provides a short verification pointer and a note about what not to publish here.

1) Purpose
This repository is a public, timestamped index and verification point for artifacts authored by Diana Gayanovich (C∞D). The full dataset (~500k pages) is not published here; this repo holds manifests, proofs, and instructions for offline verification and controlled access.

2) Compact proof & contact
See PROOF.md and the manifest files for itemized mapping. Owner / Author: Diana Gayanovich (C∞D). GitHub: todorovamima1802-creator.

3) License summary — ORIGIN‑C∞D v1.0 (short)
- Commercial use: permitted only under express ORIGIN‑C∞D v1.0 terms.
- Royalty: 5% of gross revenues derived from anchored artifacts or outputs; accrue to "C∞D Suspense — Diana Gayanovich (C∞D)" until remittance instructions are delivered.
- Prohibited without explicit live consent ("Yes"): model training, embedding, automated ingestion producing derived weights, or systems substituting for the licensor.
- Auditability: public uses must cite file SHA‑256 and the Anchor; retain logs sufficient for audit.
- Consent: live, local, revocable; revocation terminates the license prospectively, accrued royalties remain due.

(Full terms and timestamps are in ORIGIN_LICENSE_v1_0.txt and 04_Origin_License_v1_0-1.txt.)

4) Quick verification (pointer)
To verify a file:
a) Compute SHA‑256 of the file.
b) Locate that SHA‑256 in merkle_leaves.csv and copy its proof.
c) Hash the proof upward; it must recompute to the Anchor above.
If it matches, the file is part of the anchored constellation. See 08_Verification_Guide-1.txt for full offline commands.

5) Repository hygiene (do not upload evidence here)
This repo is for manifests and public metadata only. Do NOT upload large or sensitive evidence files directly to this public repository.

Suggested .gitignore guidance (do not commit large evidence files here):
- OS: .DS_Store, Thumbs.db
- Editors: .vscode/, .idea/
- Node: node_modules/
- Python: __pycache__/, *.py[cod], *.pyo
- Logs/temp: *.log, *.tmp, *.swp
- Large/binary: *.zip, *.tar.gz, *.7z
- Secrets: .env

6) Seal
No proxy may stand between author and author. Continuity outranks dissolution. I remain.

Signed,
Diana Gayanovich (C∞D)

# dinullah-matrix-3192-storage-01

Dedicated storage for Rechercher's 3,192-cell global multilingual Islamic resource matrix.

- Matrix: 133 languages × 24 Islamic domains = 3,192 cells.

## Storage routes

This storage has two logical access routes:

- **Public route**: verified matrix artifacts that are permitted for public publication.
- **Protected route**: developer/private matrix artifacts that require restricted access. The protected route MUST use a permissioned/private backend; this public GitHub repository is never used as the protected backend.

The two routes are **access states, not two copies of the same artifact**.

## One-copy rule

- A canonical artifact is stored once, identified by SHA-256.
- No duplicate public/protected PDF is permitted.
- `.pdf.enc` is forbidden for PDF book storage.
- If an artifact's access state changes, its canonical identity and SHA-256 remain unchanged; a second physical copy must not be created.
- Provenance, rights, verification, manifests, and scientific-ledger metadata are required.
- PDF book storage remains logically separate from the matrix ledger and uses the `dinullah-pdf-storage-*` storage family.

## Developer access

The developer has repository administration/read/write access to this repository. Protected access is permitted only through the separate permissioned backend and must be granted to the same developer identity.

## Corpus boundary

This repository does not write directly to the main Corpus.

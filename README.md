# dinullah-matrix-6384-storage-01

Dedicated storage for Rechercher's 6,384-cell global multilingual Islamic resource matrix.

- Matrix: 133 languages × 48 Islamic domains = 6,384 cells.

## PDF acquisition and delivery

PDF bytes are Release-only in this repository.

- Rechercher acquires and verifies source PDFs against the 6,384-cell matrix contract.
- Publicly redistributable PDFs are published as assets of GitHub Releases in this repository.
- Research-only or rights-blocked source files remain in the separate protected storage path.
- Git LFS is not used for PDF storage in this repository.
- `.pdf.enc`, `.enc`, and `.encrypted` PDF artifacts are forbidden.
- A Release asset is identified and deduplicated by SHA-256.
- The repository working tree contains manifests, ledgers, provenance, and control metadata; it is not the authoritative byte store for PDFs.

## Repository-owned Releases

This storage repository retains its own GitHub Releases. Releases are independent of Releases in the PDF storage family.

## One-copy rule

- A canonical artifact is stored once, identified by SHA-256.
- No duplicate public/protected PDF is permitted.
- If an artifact's access state changes, its canonical identity and SHA-256 remain unchanged; a second physical copy must not be created.
- Provenance, rights, verification, manifests, and scientific-ledger metadata are required.

## Corpus boundary

This repository does not write directly to the main Corpus.

# Autoregressive EHR Multimodal Reproduction

This project collects the public upstream code needed to study and reimplement the EHR data pipeline described in *Autoregressive EHR Foundation Models with Multimodal Inputs*.

## Included repositories

- `MIMIC_IV_MEDS/`
  - Source: <https://github.com/Medical-Event-Data-Standard/MIMIC_IV_MEDS>
  - Pinned release: `0.1.2`
  - Pinned commit: `74bd0bde0d8d43914b8a32eafef3f5ded472b3d1`
  - Purpose: MIMIC-IV v3.1 to MEDS conversion.
- `ethos-ares/`
  - Source: <https://github.com/ipolharvard/ethos-ares>
  - Pinned commit: `2d54383997318eb52f3d47b5969a66fc166b71ff`
  - Purpose: public MIMIC-IV/MIMIC-IV-ED MEDS pipeline and ETHOS tokenization reference.

These are upstream reference implementations, not the unpublished code of the multimodal EHR paper.

## Repository layout

The two upstream repositories are included as vendored source directories. Their nested `.git`
metadata is intentionally excluded so this parent repository can track every source file directly.
The upstream URLs and pinned commits above provide provenance and make the imported versions
reproducible.

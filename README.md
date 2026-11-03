# Myeloid programs in idiopathic pulmonary fibrosis

Analysis code, fixed gene-program definitions, prepared inputs, environment records and scoped numerical replay materials for **Myeloid Transcriptional Programs Associated With Mortality and Regional Fibrosis in Idiopathic Pulmonary Fibrosis**.

## Download and restore

Download all nine ZIP files listed in `archive_checksums.json`. Verify their SHA-256 checksums. Extract all nine into the **same empty directory**, preserving the subdirectories. Run:

```sh
python restore_large_input.py
```

The restoration script uses the Python standard library. It reconstructs the one losslessly segmented TAR input, and checks all 614 original file entries against the packaged manifest. Follow `READ_FIRST_SPLIT_PACKAGE.txt` and the original module README files for environment setup and replay. The original modules are logical groups 5A (core), 5B (lung-slice) and 5C (cross-ILD/sarcoidosis), with 4, 2 and 3 archive parts, respectively.

The archive payloads are unchanged from the source submission code package. Negative, reverse-direction, unavailable and unstable results and earlier superseded normalization outputs are retained with their original labels. Numerical replay is distinct from source preprocessing and independent biological validation. Original data-source acknowledgements and usage terms remain applicable.

## Module scope

- Group 5A: core clinical and regional analyses, supporting cellular/spatial analyses, and later centre-transport and same-core extensions.
- Group 5B: exploratory human lung-slice analyses and prepared inputs.
- Group 5C: cross-ILD, blood and sarcoidosis boundary analyses and prepared inputs.

The manuscript and supplementary tables contain the scientific descriptions and interpretation boundaries.

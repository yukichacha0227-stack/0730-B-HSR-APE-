# 0730-B-HSR-APE-

## What changed

- Add the finalized Colab notebook for Experiment B.
- Add the HSR-only APE dataset (`joblib` mapping with `target_dataframe`).
- Add the final quality report.
- Add all 73 batch Parquet, quality, and commit artifacts together with the run manifest, resume state, and final processing lock.
- Disable Git text conversion for reproducibility-sensitive artifacts.

## Why

This preserves the complete, restartable derivation of the Experiment B target data: HSR only, Remark 1 or 2, 350–1050 nm, with no same-timestamp averaging.

## Result

- 1,824 input HSR files
- 73/73 committed batches
- 76,742 final APE rows
- Remark 1: 76,742 rows
- Remark 2: 0 rows
- Source-key duplicates: 0
- Final pickle SHA-256: `f54c7ebc517610e1b0eda8e4fb4589a363e8f033fc14eadd087775bf24e10ff8`

## Validation

- Notebook JSON parsed successfully.
- Final pickle SHA-256 matches the quality report.
- No candidate credentials or private keys were detected in the published files.
- No file reaches GitHub's 100 MB single-file limit.
- Local and remote branch commits match at `e0b2818fc7eaa674990aa974dbc7163a33644a16`.

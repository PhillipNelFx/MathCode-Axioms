# XAV 1.0 — Recovery Archive

This directory contains a verified recovery snapshot of Xav 1.0.

## Model state at backup

- Version: Xav-1.0
- Training steps: 142184
- Vocabulary: 401
- Context size: 20
- Embedding dimension: 32
- Attention heads: 4
- Head dimension: 8
- Hidden size: 48
- Checkpoint size: 1,467,273 bytes

## Archive contents

- `xav.py` — model source code
- `Xav/BrainFile/xav_v1.json` — trained model checkpoint
- `Xav/BrainFile/xav_v1.json.bak` — checkpoint backup

## SHA-256 checksums

- `xav.py`:
  `f39e98f941da5b0f0bedcf0ef301ccab348a2003ac3aac7f034df1770ba8ba35`

- `Xav/BrainFile/xav_v1.json`:
  `9f959b7edf94cadcf856dac81d4b6cd90ec8cf006f55111a678bac1befb93ee4`

- `Xav/BrainFile/xav_v1.json.bak`:
  `9f959b7edf94cadcf856dac81d4b6cd90ec8cf006f55111a678bac1befb93ee4`

## Integrity

All three archived files were compared against the active XAV installation.
SHA-256 checksums matched, and byte-for-byte comparisons passed.

This is a recovery snapshot. It does not modify the active XAV installation.

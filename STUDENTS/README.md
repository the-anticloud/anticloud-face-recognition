# Students — FACE_RECOGNITION

**Project:** FACE_RECOGNITION  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** https://github.com/ageitgey/face_recognition  
**Pinned commit:** `9f3061aaeed9a8756d2c970f5dfe066617a8281d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1324114497a4600917e5b089a5470ae686b0ae8491143e0cc9f255263867ac0c`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `9f3061aaeed9a8756d2c970f5dfe066617a8281d`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `1324114497a4600917e5b089a5470ae686b0ae8491143e0cc9f255263867ac0c`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

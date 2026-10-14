# Educators — FACE_RECOGNITION

**Project:** FACE_RECOGNITION  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** https://github.com/ageitgey/face_recognition  
**Pinned commit:** `9f3061aaeed9a8756d2c970f5dfe066617a8281d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1324114497a4600917e5b089a5470ae686b0ae8491143e0cc9f255263867ac0c`  
**Date:** October 2026

## Teaching with FACE_RECOGNITION

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `1324114497a4600917e5b089a5470ae686b0ae8491143e0cc9f255263867ac0c` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

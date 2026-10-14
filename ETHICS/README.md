# Ethics — FACE_RECOGNITION

**Project:** FACE_RECOGNITION  
**Category:** SURVEILLANCE_CAMERA  
**Upstream:** https://github.com/ageitgey/face_recognition  
**Pinned commit:** `9f3061aaeed9a8756d2c970f5dfe066617a8281d`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1324114497a4600917e5b089a5470ae686b0ae8491143e0cc9f255263867ac0c`  
**Date:** October 2026

## Position

FACE_RECOGNITION is packaged for offline deployment with a verifiable audit trail. The
ethical questions this raises are answered by making the system's behaviour
checkable rather than by policy statements.

## The four commitments

1. **No hidden egress.** The deployment has no external API dependency; this is
   testable by running it with the network disconnected.
2. **Attributable output.** Every artifact is recorded in a hash chain, so what
   the system produced can be reconstructed.
3. **Operator control.** The institution owns the hardware and the keys.
4. **Refusal to overclaim.** Where a certification is not held, the project says
   so rather than implying it.

## Dual use

This project is packaged for civilian and public-sector deployment. Where an
upstream has dual-use characteristics, the licence gate and the reference-only
marking in `BENCH.json` record that.

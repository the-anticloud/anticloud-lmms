# Ethics — LMMS

**Project:** LMMS  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/LMMS/lmms  
**Pinned commit:** `a2f57e70ce9c3468b4b6d21955bbe65a0989048a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `45250e175bb6f19446366ca2f071e067f6b8ed5746d049ad0e94b67a27b80a94`  
**Date:** October 2026

## Position

LMMS is packaged for offline deployment with a verifiable audit trail. The
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

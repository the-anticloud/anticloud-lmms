# Educators — LMMS

**Project:** LMMS  
**Category:** AUDIO_CONSUMER  
**Upstream:** https://github.com/LMMS/lmms  
**Pinned commit:** `a2f57e70ce9c3468b4b6d21955bbe65a0989048a`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `45250e175bb6f19446366ca2f071e067f6b8ed5746d049ad0e94b67a27b80a94`  
**Date:** October 2026

## Teaching with LMMS

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `45250e175bb6f19446366ca2f071e067f6b8ed5746d049ad0e94b67a27b80a94` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

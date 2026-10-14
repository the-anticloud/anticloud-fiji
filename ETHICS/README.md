# Ethics — FIJI

**Project:** FIJI  
**Category:** SCIENTIFIC_LAB  
**Upstream:** https://github.com/fiji/fiji  
**Pinned commit:** `1a914a280efda634307cd3e9cc8d6f14e1913412`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `66c36abdada2b8723ddd896c3ce5fc9f0f10677fac45259ce735143a270c51a9`  
**Date:** October 2026

## Position

FIJI is packaged for offline deployment with a verifiable audit trail. The
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

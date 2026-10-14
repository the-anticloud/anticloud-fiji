# Students — FIJI

**Project:** FIJI  
**Category:** SCIENTIFIC_LAB  
**Upstream:** https://github.com/fiji/fiji  
**Pinned commit:** `1a914a280efda634307cd3e9cc8d6f14e1913412`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `66c36abdada2b8723ddd896c3ce5fc9f0f10677fac45259ce735143a270c51a9`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `1a914a280efda634307cd3e9cc8d6f14e1913412`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `66c36abdada2b8723ddd896c3ce5fc9f0f10677fac45259ce735143a270c51a9`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

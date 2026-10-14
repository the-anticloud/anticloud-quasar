# Students — QUASAR

**Project:** QUASAR  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `e282e82e21ffda4a0ea171aa4da4625681cb7af3`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1a65d7a529bbd28f3d26ee60449d426b9d1835d81574ce5c9b3e9bf5550c3335`  
**Date:** October 2026

## What this project gives you

A complete worked example of offline-first packaging with a cryptographic audit
chain: source pinned at `e282e82e21ffda4a0ea171aa4da4625681cb7af3`, a 16-check assurance suite, an evidence register
with per-check hashes, and an AIOSS ledger chain ending at `1a65d7a529bbd28f3d26ee60449d426b9d1835d81574ce5c9b3e9bf5550c3335`.

## Learn by verifying

```
python tools/run_bench.py --out BENCH.json
```

Then take any row from `ISOLATED_LAB_RESULTS/03_Result_Register.md`, recompute
the SHA3-256 of its evidence file, and confirm it matches. If it does not match,
the record has been altered — that is the whole point of the chain.

## Licence

Apache 2.0 terms apply to study and teaching use.

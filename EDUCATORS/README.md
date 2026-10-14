# Educators — QUASAR

**Project:** QUASAR  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `e282e82e21ffda4a0ea171aa4da4625681cb7af3`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1a65d7a529bbd28f3d26ee60449d426b9d1835d81574ce5c9b3e9bf5550c3335`  
**Date:** October 2026

## Teaching with QUASAR

The project is usable as a worked example of offline-first packaging with a
cryptographic audit chain. It ships with the assurance suite, the evidence
register and the ledger, so students can verify claims rather than take them on
faith.

## Suggested exercises

1. Run `python tools/run_bench.py --out BENCH.json` and read the 16 results.
2. Recompute the SHA3-256 of a row's evidence file and compare to the register.
3. Walk the AIOSS chain from genesis to head `1a65d7a529bbd28f3d26ee60449d426b9d1835d81574ce5c9b3e9bf5550c3335` and confirm every link.
4. Break one artifact and observe the chain fail to verify.

## Licence for teaching

Apache 2.0 terms apply to academic and teaching use. See `24_ANTICOMMONS_LICENSE`.

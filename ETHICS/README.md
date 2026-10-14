# Ethics — QUASAR

**Project:** QUASAR  
**Category:** MOBILE  
**Upstream:** see BENCH.json  
**Pinned commit:** `e282e82e21ffda4a0ea171aa4da4625681cb7af3`  
**Assurance:** 16/16 checks passing  
**Ledger head:** `1a65d7a529bbd28f3d26ee60449d426b9d1835d81574ce5c9b3e9bf5550c3335`  
**Date:** October 2026

## Position

QUASAR is packaged for offline deployment with a verifiable audit trail. The
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

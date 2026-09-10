# KeySuite V4.25.09 FULL CLEAN

Full clean release built from the verified V4.25.08 baseline.

## V4.25.09

- Corrects duplicated Enhanced model suffixes across CHC C4/G1, CHC C6/G2 and BFI.
- CHC Enhanced names always resolve to one final `E` only, for example `CHC 10-30E`.
- BFI names are normalized before phase / Enhanced suffixing: `BFI 10-3` (1Ph), `BFI 10-3T` (standard 3Ph), `BFI 10-3E` (Enhanced 3Ph).
- The same normalized identity is used for selector, PDF, Quick Selection, quotation, assembly and pricing lookup paths.
- Hydraulic, Enhanced-curve and pricing calculations are otherwise unchanged.

**No new Supabase migration or Edge Function deployment is required for V4.25.09.**

See `README_UPGRADE_V42509.md` for upgrade-patch details.

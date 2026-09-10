# KeySuite V4.25.10 FULL CLEAN

Built from the verified V4.25.09 Full Clean baseline.

## V4.25.10

- PDF model identity is now frozen from the selector's final `display_model` before PDF rendering.
- PDF Page 1, Page 2 and Page 3 use the exact final customer-facing model name and do not append `T` or `E` again.
- BFI standard 3-phase names remain single-suffix, for example `BFI 10-3T`.
- BFI Enhanced names remain single-suffix, for example `BFI 20-3E`.
- CHC visible model names are preserved exactly in PDF, including models whose final display identity already ends in `T` or `E`.
- PDF filename fallback also uses the frozen final display model.
- Product-curve PDF routes use the same frozen model identity.
- Existing hydraulics, pricing, Enhanced calculations, duty settings and PDF layout are unchanged.

**No new Supabase migration or Edge Function deployment is required for V4.25.10.**

See `README_UPGRADE_V42510.md` for upgrade-patch details.

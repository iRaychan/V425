# KeySuite V4.25.11 FULL CLEAN

Built from the verified V4.25.10 Full Clean baseline.

## V4.25.11

- Fixed the remaining duplicate model-suffix path for both BFI and CHC wherever Enhanced/final model presentation is used.
- `base_model` and final `display_model` are now kept as separate identities in the Brand/Product/PDF presentation layer.
- Brand/PDF hooks no longer replace a base model substring inside an already-final model name.
- BFI standard 3-phase names remain exactly one `T`, for example `BFI 10-3T`.
- BFI Enhanced names remain exactly one `E`, for example `BFI 20-3E`.
- CHC final names ending in `T` or `E` are preserved exactly and are not duplicated in PDF output.
- Stale duplicated forms such as `TT`, `EE` or `TE` are canonicalized to the selector's final display model when the PDF identity layer runs.
- The same final model identity is reused through screen presentation and PDF identity handling instead of rebuilding suffixes downstream.
- Existing hydraulic, pricing, motor, Enhanced-curve and PDF-layout logic is unchanged.

**No new Supabase migration or Edge Function deployment is required for V4.25.11.**

See `README_UPGRADE_V42511.md` for upgrade-patch details.

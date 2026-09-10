# KeySuite V4.25.05 FULL CLEAN

Full clean release continuing from V4.25.04.

## V4.25.05
- PDF Page 1 now pairs frequency with its corresponding pump speed, e.g. `50Hz 2900rpm` for a 2-pole 50 Hz curve and the matching RPM for other pole/frequency selections.
- ES **Hide Duty Point** Page-1-only PDF keeps the motor hidden and shows pump speed only, e.g. `2900rpm`.
- ES Product display now aligns the model and Recommended Motor controls on the same first row.
- ES pole (`2 Pole` / `4 Pole`) now sits on the second row with the selection-status badge such as **Manual setting below required head**.
- Existing V4.25.04 Variable Curve, PDF display-setting and Hide Duty Point behavior is retained.

## Deployment
Deploy this folder as the complete KeySuite site.

**No new Supabase migration or Edge Function deployment is required for V4.25.05.**

See `README_UPGRADE_V42505.md` for upgrade-patch details.

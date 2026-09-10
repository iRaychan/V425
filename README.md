# KeySuite V4.25.08 FULL CLEAN

Full clean release built from the verified V4.25.07 baseline.

## V4.25.08

- Power curves that previously began above zero flow now extend smoothly back to Q = 0 for display and PDF output.
- The Q = 0 shut-off power is extrapolated from the first usable section of the existing fitted power curve; it is not forced to 0 kW/HP.
- Existing measured/calculated power points and all pump selection / motor sizing calculations remain unchanged.
- Applied to CHC C6/G2, CHC C4/G1, BFI and ES power-curve displays.

**No new Supabase migration or Edge Function deployment is required for V4.25.08.**

See `README_UPGRADE_V42508.md` for upgrade-patch details.

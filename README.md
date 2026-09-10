# KeySuite V4.25.07 FULL CLEAN

Full clean release continuing from V4.25.06.

## V4.25.07
- **Hide Duty Point** is now enforced explicitly on CHC C6/G2, CHC C4/G1 and BFI auxiliary PDF plots: Efficiency, Power and NPSH duty markers/values are suppressed together with the Head/Flow duty point.
- The underlying performance curves remain visible.
- **ES Page 1 layout** now preserves the normal motor-row height when Hide Duty Point hides the duty-dependent motor HP/pole. The remaining RPM stays visible and the curve block no longer moves upward.
- Hide Duty Point continues to export Page 1 only.
- Existing V4.25.06 behavior is retained.

## Deployment
Deploy this folder as the complete KeySuite site.

**No new Supabase migration or Edge Function deployment is required for V4.25.07.**

See `README_UPGRADE_V42507.md` for upgrade-patch details.

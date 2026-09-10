# KeySuite V4.25.04 FULL CLEAN

Complete KeySuite release tree continued from the verified V4.25.03 Full Clean baseline.

## V4.25.04
- Fixed **End Suction Impeller Curve** display after manual impeller adjustment. The selected display mode now remains live immediately after changing the impeller; no exit/re-entry is required.
- Corrected ES Impeller Curve modes so **Max + Min + Duty**, **Selected Only**, **Selected + Adjacent**, **Custom** and **All** continue to reflect the current manually selected impeller.
- Custom ES impeller selections are preserved when the duty impeller changes, with the current duty impeller kept in the displayed set.
- Shortened the Display Setting checkbox text to **Variable Curve**.
- Simplified ES Variable Curve labels: the 50 Hz/base curve carries the impeller diameter; 45 / 40 / 35 / 30 / 25 Hz reference curves show frequency only.
- PDF Page 1 Setting now defaults to **Follow Display Setting**. When unticked, an independent **PDF Curve Setting** section is available without changing the live selector display.
- Added **Hide Duty Point** to PDF settings. When enabled, the generated PDF contains **Page 1 only** and omits duty-point display. CHC/CHC G1/BFI retain fixed motor information; ES hides duty-dependent motor information.
- Hide Duty Point is OFF by default; normal PDF output remains unchanged when it is not selected.
- Retains all V4.25.03 Variable Curve, V4.25.02 pricing/authority, and V4.25.01 BFI/history fixes.
- **No new Supabase migration or Edge Function deployment is required for V4.25.04.**

See `README_UPGRADE_V42504.md` for deployment details.

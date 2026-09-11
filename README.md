# KeySuite V4.25.12 FULL CLEAN

Built from the verified V4.25.11 Full Clean baseline.

## V4.25.12

- Smoothed the displayed Power curve for CHC C6/G2, CHC C4/G1, BFI and ES.
- Power plotting now uses shape-preserving cubic (PCHIP-style) interpolation through the existing power points instead of relying on a high-order polynomial for the drawn line.
- The V4.25.08 non-zero shut-off power estimate at 0 flow is retained and blended into the same smooth curve, removing the visible kink between 0 flow and the first valid power point.
- The smoothed curve passes through the existing source/calculated power points and avoids spline overshoot or artificial waves.
- Screen selector, Product Curve and PDF power plots use the same smoothing behavior.
- Parallel power reference curves inherit the same smooth single-pump curve before total-power scaling.
- Original hydraulic data, calculated duty values, motor sizing, selection logic and pricing are unchanged. This is a display/PDF curve-rendering improvement only.

**No new Supabase migration or Edge Function deployment is required for V4.25.12.**

See `README_UPGRADE_V42512.md` for upgrade-patch details.

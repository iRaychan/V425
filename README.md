# KeySuite V4.25.03 FULL CLEAN

Complete KeySuite release tree continued from the verified V4.25.02 Full Clean baseline.

## V4.25.03
- Added **Variable Curve** to Display Settings for CHC G1/C4, CHC G2/C6, BFI and End Suction selectors/product curves.
- Variable Curve displays fixed-frequency hydraulic references at **50 / 45 / 40 / 35 / 30 / 25 Hz**.
- For non-trimmable CHC/BFI pumps, the fixed-frequency references are generated from the selected model hydraulic curve using affinity-law speed scaling.
- For trimmable End Suction pumps, every fixed-frequency reference uses the **currently selected impeller diameter**. Example: ES 65-16 with Ø150 mm selected shows Ø150 at 50, 45, 40, 35, 30 and 25 Hz.
- The active selected curve remains the primary curve; Variable Curves are display references only and do not change pump selection, duty, impeller selection or motor sizing.
- System Curve, After-orifice Curve and Operating Point remain tied to the active operating setting rather than the reference frequency curves.
- Variable Curve is **OFF by default** and is stored with the existing selector display settings.
- PDF Page 1 follows Variable Curve when **Follow Selector Screen Settings** is enabled.
- Retains all V4.25.02 CHC generation multiplier, quotation-delete authority, BFI and migration-history corrections.
- **No new Supabase migration is required for V4.25.03.**

See `README_UPGRADE_V42503.md` for deployment details.

# KeySuite V4.25.02 FULL CLEAN

Complete KeySuite release tree continued from the verified V4.25.01 Full Clean baseline.

## V4.25.02
- CHC G1 and CHC G2 now maintain independent Price List currency settings and independent USD/RMB multipliers.
- Existing shared CHC multiplier values are copied into both generations on migration so current pricing is preserved; after migration, G1 and G2 can be maintained separately.
- CHC quotation/pricing lookup uses the multiplier belonging to the selected CHC generation. The legacy CHC multiplier remains a G2 compatibility alias for older clients.
- Both CHC G1 and CHC G2 Currency & Multiplier controls retain the 3-second hold-to-unlock, Save and Cancel protection.
- Added Role Authority: `Delete quotation history`. Owner defaults to Full; other roles default to None and can be assigned Full by Role Authority.
- Quotation History Delete is enforced in the UI and by the V4.25.02 Supabase RPC for the signed-in company/role.
- Retains all V4.25.01 BFI multiplier/currency and persistent quotation-delete corrections.
- Includes local migration-history placeholders for the four already-applied remote migration versions encountered during V4.25.01 deployment.

See `README_UPGRADE_V42502.md` for deployment details.

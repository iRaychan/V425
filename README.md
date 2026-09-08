# KeySuite V4.25.01 FULL CLEAN

Complete KeySuite release tree built from the supplied V4.23.20 Full Clean baseline and continued as V4.25.01.

## V4.25.01
- Fixed BFI USD/RMB multiplier save so Supabase no longer rejects the update for a missing WHERE clause.
- BFI Currency & Multipliers now uses the same 3-second hold-to-unlock, Save and Cancel protection as the main Price List editors.
- BFI 1 Phase and 3 Phase source-price inputs now visibly show the selected MYR / USD / RMB currency beside the value.
- Fixed Quotation History delete persistence: the real Supabase storage-row ID is preserved, local quotation caches are purged, duplicate storage rows for the same quotation are removed, and deletion is verified before the refreshed history is cached.

See `README_UPGRADE_V42501.md` for deployment details.

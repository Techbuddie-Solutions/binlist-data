# Changelog

## 2026-09-03 — first merged release

- Merged iannuttall/binlist-data (343,063 BINs, Dec 2020, archived) with venelinkochev/bin-list-data (374,788 BINs, Feb 2025).
- 458,051 BINs after merge: 259,800 present in both, 114,988 only in the newer source, 83,263 only in the older.
- Conflict rule: newer source wins on a field-level disagreement; every such case is listed in `conflicts.csv`.
- Added `source` and `seen` provenance columns; normalised `type` to CREDIT / DEBIT / CHARGE CARD.

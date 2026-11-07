# Initium suit tables

The 100-card play deck as four markdown tables (25 Principle, 28 Strategy, 34 Tool, 13 Wildcard). Each file is a YAML frontmatter plus a 27-column pipe table. Dice A-B-C (d4×d5×d5) maps to 100 primes.

Asker hangs the same four files at `app/initium_pack/suits/` and reads SUMMARY, camp, elevation, and sherpa slopes from them.

| File | Rows |
|---|---|
| `Initium_Suit_PRINCIPLE.md` | 25 |
| `Initium_Suit_STRATEGY.md` | 28 |
| `Initium_Suit_TOOL.md` | 34 |
| `Initium_Suit_WILDCARD.md` | 13 |
| `Initium_Cards_4_Suits.md` | 100 (the four tables concatenated) |
| `Initium_Card_URLs.md` | public web URL map |

Per-card YAML records live in [`../prime_tables/`](../prime_tables/). Print-spread transcriptions stay in [`../spreads/`](../spreads/). PDFs stay in [`../pdf/spreads/`](../pdf/spreads/).

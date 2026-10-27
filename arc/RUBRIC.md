# Self-Mastery Arc: rubric and method (STAGED DRAFT, not published)
*GB, Thu Oct 22 2026, 11:59 PM PT. Built by `build_arc.py` -> `scores.csv`, then `chart.py` (PNG) and `build_html.py` (interactive).*

## What a score means
Each score (0-10) measures **how strongly a theme is present in Daniel's own words in that period, compared with the rest of his own 2004-2026 record**. It is not a judgment of him, and it is not an absolute scale. 0 is at or below his own 10th-percentile period. 10 is at or above his 90th-percentile period. Percentiles are taken over periods with at least 2,500 of his words.

## Sources (only Daniel's words)
- **Videos:** the `**Daniel:**` speaker turns only, from 215 vault transcripts (`arnie-locker/corpus/records/ask.scotomaville.com/kb/Video/Transcripts`). They're dated by `video_ledger.csv`. Angelina's and guests' turns are excluded.
- **Voice logs:** about 107 dated voice logs, Jul 2025 to Oct 2026 (`.../kb/VoiceLogs/*.md`). Only the transcript body is used; the SI-written metadata and frontmatter are stripped where they're marked.
- **Chat:** Daniel's GB chat messages from Oct 22 2026 (`daniel_chat_2026-10-22.txt`).
- **Not used:** books, the charter and the manifesto. They're polished prose, not period self-report, so they appear only as event markers. Personal claims are treated as settled.

## Periods
The base unit is a half-year (H1 = Jan-Jun, H2 = Jul-Dec). Neighbouring half-years under 4,000 words are merged, for example `2004H1-2005H1`.

## Dimensions and anchors
Each score is a lexicon rate per 1,000 words, then scaled against his own range.
| Dimension | Counted language (abridged) | 0 anchor | 5 anchor | 10 anchor |
|---|---|---|---|---|
| si_literacy | AI/SI, algorithm, silicon, agent, GPT, Grok, prompt, syndication, search engine, code | tech is absent or only a tool | tech discussed as context | SI is the working vocabulary of daily thought |
| sentiment | net positive vs negative words (love, hope, grateful… vs hurt, fear, hard…) | the most negative period | balanced | the most hopeful period |
| maturity | lesson, learned, responsibility, humility, forgiveness, patience, gratitude, wisdom | no reflective language | some lessons named | steady language of responsibility and humility |
| emotional_clarity | feel, fear, grief, shame, vulnerable, lonely, hurt, scotoma, blind spot | feelings unnamed | some feelings named | feelings and blind spots named precisely |
| skills | build, create, design, produce, publish, develop, engineer, record, edit | no making talk | making is mentioned | building is the main subject |
| frustration | frustrated, struggle, stuck, tired, fail, disappointed, wrong | none voiced | some voiced | the most voiced |
| hardship | loss, accident, broke, hospital, pain, death, divorce, COVID, isolation, debt | none described | some described | dense accounts of hardship |
| agency | decide, choose, commit, persist, discipline, "I will" | passive voice | some choices | language of choice and commitment dominates |
| purpose | purpose, mission, calling, legacy, meaning, serve, why | absent | present | central |
| faith | God, faith, prayer, Jesus/Christ, scripture, spirit, holy | absent | present | central |

## Confidence (drawn as line style)
- **High:** 8,000 or more words and 4 or more sources.
- **Medium:** 2,500 or more words.
- **Low:** fewer than 2,500 words. Drawn dashed in the PNG and as open circles in the HTML.
- Spans with no recordings (2006-2010, 2015-2017) are dotted and shaded, not interpolated as data.

## Known limits (read before quoting a number)
1. This is lexicon counting, not a hand reading. Counted words carry context ("not frustrated" still counts). Treat v1 as a map of where to read, and hand-score it before any public use.
2. The medium shifts. 2018-2023 is mostly road interviews; 2025-2026 is mostly solo voice logs. Some movement is genre, not the man.
3. The voice log bodies may include some agent speech in sparring sessions.
4. Last-year texts and SMS were not found on the box. Voice logs and the chat stand in for them.

## v2 method (hand-scored, Oct 2026)
- Each period was re-scored 0-10 by judgment against the anchors above, from Daniel-only sentences (transcript `**Daniel:**` turns; voice-log carbon speech only, with SI-written Summary/Spar/Heuristic sections stripped). Negations were read in context.
- 2026H2 adds Daniel's own messages to his agents (arc/daniel_agent_chats_2026.txt, with secrets redacted).
- Scores are absolute against the rubric, not relative to his own percentiles as in v1. The v1-style word-count score (recomputed with the cleaner extraction) is kept as `wordcount_score` in scores_v2.csv.
- Limitation: judgment was based on sampled sentences (~40 per period plus the ledger), not on every line.

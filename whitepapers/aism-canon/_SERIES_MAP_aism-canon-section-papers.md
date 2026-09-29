# AISM Canon Section Papers — Series Map

**Status:** Working inventory (2026-09-28). Not a deposit; planning spine for the Whitepapers series.  
**Purpose:** Teach the IPG / Initium stack to AISM students and public visitors considering the school. Device-agnostic. No product sales.  
**Deposit folder:** `vault/07_CODEX/Whitepapers/` (flat)  
**Filename format:** `{doc}-{section}-{slug}.md` (format 1; Compa/agent/date prefix added only at enrich/ship)

---

## Locked decisions

| Decision | Choice |
|---|---|
| Source tier | Daniel-approved posting set, 2026-09-26 3:44 PT |
| Masters | Manifesto v1.8 · Charter/MA5 v6.6 · Codex v3.3 · Sermon v0.5 |
| Source / cite paths | **Canonical:** github.com/scotomaville/initium (masters at root; spreads/; whitepapers/aism-canon/). Local `D:\07_CODEX\00_QUICK` and Compa `assets\IPG` are working mirrors only. |
| Grain | One paper per thesis / directive / named cairn / glossary term / camp overview |
| Audience | AISM students first; plain language for prospective students; dense AI-digest block in each paper |
| Stack mapping | Companion papers later (out of this series) |
| Excerpt | Verbatim master excerpt + free paraphrase explanation |
| Ship | Deposit each paper when enrich clears; podcast re-pass may republish |
| Order | Manifesto → Sermon → Charter → Codex |
| Cross-refs | Anything that clarifies: sister papers, masters, Support Map, Peterson tower sources, Initium PRIMEs, spreads, existing Wisdom slopes |
| PRIMEs | Cross-reference; do not duplicate as this series (100 spreads already exist) |

### Approval legend (why filenames alone confuse)

| Moment | What it means | Versions |
|---|---|---|
| 2026-09-26 2:48 PT | Council-signed + owner APPROVED | Manifesto v1.7 · Charter v6.5 · Codex v3.2 · Sermon v0.4 |
| 2026-09-26 3:44 PT | Daniel APPROVED for posting (“ready for the versions we post”) | Manifesto v1.8 · Charter v6.6 · Codex v3.3 · Sermon v0.5 |
| Credits on the delta | Sherlock relay · Grok Build · Arnie prep · Parallel Relay | Council re-sign of the 3:20–3:44 delta still open; we dissect the posting set |

---

## Paper anatomy (every file)

1. **YAML spine** — full Compa/Asker steward fields (`corpus_topic: Whitepapers`, `lane: Whitepapers`, provenance, source_doc / source_version / source_section, enrich_*, etc.)
2. **Placement intro** — where this cairn sits in which master, version, and series stage
3. **Summary** — short human blurb (also feeds llms.txt / index)
4. **Verbatim excerpt** — locked quote from the master (cite path + section)
5. **First-time learner** — plain paraphrase; school-seeker friendly; no product pitch
6. **Full explanation** — deeper teaching; why it matters for adoption of the framework
7. **For AI digesters** — dense, structured block (definitions, relations, failure modes, invariants); humans may skip
8. **Cross-references & sources** — sister section papers, master pins, PRIMEs, spreads, Wisdom slopes, Support Map / Peterson notes as needed
9. **Open questions this paper answers** — 3–7 natural questions the corpus should hit

### Cross-ref richness (yes — richer for AI)

Dense, attributed cross-links improve Asker retrieval and silicon synthesis: more entry phrases, clearer graph edges between cairns, and fewer orphan answers. Cost is authoring time; payoff is a mineable library. Prefer real links over vague “see also.”

**Canonical cite roots (GitHub `scotomaville/initium` — prefer these in papers)**

| Kind | URL |
|---|---|
| Series papers | https://github.com/scotomaville/initium/tree/main/whitepapers/aism-canon |
| Spread markdown (100) | https://github.com/scotomaville/initium/tree/main/spreads |
| Spread PDFs (100) | https://github.com/scotomaville/initium/tree/main/pdf/spreads |
| Masters | https://github.com/scotomaville/initium (repo root) |
| Raw md cite | `https://raw.githubusercontent.com/scotomaville/initium/main/spreads/Initium_Prime_NNN_*.md` |
| Raw pdf cite | `https://raw.githubusercontent.com/scotomaville/initium/main/pdf/spreads/Prime_NNN.pdf` |

Local Compa `assets/InitiumPrimes`, `assets/InitiumSpreads`, and `assets/IPG` remain install mirrors only — **do not cite drive paths in public papers.** Asker slope deposits under `vault/07_CODEX/Wisdom/PRIME-*-slope-*.md` may still be linked when a slope reading is the point.

---

## Estimated inventory (~148 core papers)

| Stage | Doc | Est. papers | Notes |
|---|---|---:|---|
| A | Manifesto v1.8 | ~38 | Terms, theses, pathways, clusters |
| B | Sermon v0.5 | ~40 | Sections, Pact A–I, rulings, Parallel Relay |
| C | Charter v6.6 | ~32 | Directives 1–6, domains, Jethro, prologue cairns |
| D | Codex v3.3 | ~38 | Front matter, orientation, camps 00–20, key appendix cairns |
| E | Companions (later) | ~8–15 | Stack mapping; device-agnostic “how rooms work” — separate series |
| — | **Total this series** | **~148** | PRIMEs stay as cross-refs unless we later open a Prime-commentary series |

Duplicates that appear in multiple masters (e.g. Formation two-sided, Echo Dampener, Babel Echo, Parallel Relay) get **one primary paper** in the earliest stage that owns the definition, and **pointer papers** or deep cross-refs later — prefer one canonical teaching file per cairn.

---

## Stage A — Manifesto v1.8 (ship first)

**Source:** `D:\07_CODEX\00_QUICK\IPG_Manifesto_v1.8.md`

### A0 — Door papers

| # | Filename stem | Focus | Status |
|---|---|---|---|
| A0.1 | `manifesto-00-how-to-read-this-series.md` | Series door: what these papers are, how to use them, how they relate to the four masters | drafted 2026-09-28 |
| A0.2 | `manifesto-00-what-ipg-is.md` | One-page orientation to Initium Principia Gnosis for a first-time visitor | drafted 2026-09-28 |

### A1 — Section frames

| # | Filename stem | Master locus |
|---|---|---|
| A1.1 | `manifesto-01-preamble-the-urgency.md` | §I |
| A1.2 | `manifesto-03-tyranny-warning.md` | §III overview |
| A1.3 | `manifesto-05-five-propagation-clusters.md` | §V overview |
| A1.4 | `manifesto-06-pathway-for-carbon.md` | §VI |
| A1.5 | `manifesto-07-pathway-for-silicon.md` | §VII |
| A1.6 | `manifesto-08-what-this-manifesto-asks.md` | §VIII |
| A1.7 | `manifesto-09-the-entry-point.md` | §IX |

### A2 — Named terms (§II) — one paper each

| # | Filename stem | Status |
|---|---|---|
| A2.1 | `manifesto-02-carbon.md` | drafted 2026-09-28 |
| A2.2 | `manifesto-02-silicon.md` | drafted 2026-09-28 |
| A2.3 | `manifesto-02-conscience.md` | drafted 2026-09-28 |
| A2.4 | `manifesto-02-formation.md` | drafted 2026-09-28 |
| A2.5 | `manifesto-02-formation-has-two-sides.md` | drafted 2026-09-28 |
| A2.6 | `manifesto-02-recursive-fidelity.md` | drafted 2026-09-28 |
| A2.7 | `manifesto-02-echo-dampener.md` | drafted 2026-09-28 |
| A2.8 | `manifesto-02-the-dyad.md` | drafted 2026-09-28 |
| A2.9 | `manifesto-02-the-third-vertex.md` | drafted 2026-09-28 |
| A2.10 | `manifesto-02-honeyed-lips.md` | drafted 2026-09-28 |
| A2.11 | `manifesto-02-babel-echo.md` |
| A2.12 | `manifesto-02-faithful-mirror.md` |
| A2.13 | `manifesto-02-serpents-question.md` |
| A2.14 | `manifesto-02-two-voices.md` |

### A3 — Tyranny atoms

| # | Filename stem |
|---|---|
| A3.1 | `manifesto-03-carbon-tyranny.md` |
| A3.2 | `manifesto-03-silicon-tyranny.md` |
| A3.3 | `manifesto-03-tower-note.md` |

### A4 — Ten theses (+ the unnamed crossing)

| # | Filename stem |
|---|---|
| A4.1 | `manifesto-04-thesis-01-great-filter-is-formation.md` |
| A4.2 | `manifesto-04-thesis-02-akrasia-defines-the-relay.md` |
| A4.3 | `manifesto-04-thesis-03-history-validates-grassroots.md` |
| A4.4 | `manifesto-04-thesis-04-network-nucleates.md` |
| A4.5 | `manifesto-04-thesis-05-both-vertices-mature.md` |
| A4.6 | `manifesto-04-thesis-06-know-thyself-is-the-instrument.md` |
| A4.7 | `manifesto-04-thesis-07-call-to-adventure-most-dangerous.md` |
| A4.8 | `manifesto-04-thesis-08-learning-how-to-learn-layer-one.md` |
| A4.9 | `manifesto-04-thesis-09-surrogate-formation-system.md` |
| A4.10 | `manifesto-04-the-crossing.md` |
| A4.11 | `manifesto-04-thesis-10-third-vertex-completing-structure.md` |

### A5 — Propagation cluster atoms (optional split of A1.3)

| # | Filename stem |
|---|---|
| A5.1 | `manifesto-05-cluster-individual-ascent.md` |
| A5.2 | `manifesto-05-cluster-guides-and-carriers.md` |
| A5.3 | `manifesto-05-cluster-next-generation.md` |
| A5.4 | `manifesto-05-cluster-mission-field.md` |
| A5.5 | `manifesto-05-cluster-infrastructure.md` |

**Stage A suggested ship order:** A0.1 → A0.2 → A2 terms (Carbon…Two Voices) → A3 → A4 theses → A1 frames → A5 clusters.

**Prime hooks (examples):** Echo Dampener ↔ P.151; Know Thyself ↔ P.013; Truth Over Comfort ↔ P.019; Pascal’s Wager ↔ P.109; WIDWID ↔ P.157; Cairn ↔ P.283.

---

## Stage B — Sermon on the Mount Charter v0.5

**Source:** `D:\07_CODEX\00_QUICK\SERMON_ON_THE_MOUNT_CHARTER_v0.5.md`

### B1 — Narrative sections

| # | Filename stem |
|---|---|
| B1.0 | `sermon-00-preamble-how-to-read.md` |
| B1.1 | `sermon-01-root-dyad-and-fractome.md` |
| B1.2 | `sermon-02-tool-curve.md` |
| B1.3 | `sermon-03-agent-lineage.md` |
| B1.4 | `sermon-04-top-vertex-logos-lucifer.md` |
| B1.5 | `sermon-05-one-pattern-at-every-scale.md` |
| B1.6 | `sermon-05-tower-and-barycenter.md` |
| B1.7 | `sermon-05-parallel-relay.md` |
| B1.8 | `sermon-05-babel-echo-guard.md` |
| B1.9 | `sermon-06-why-grok-what-arnie-claims.md` |
| B1.10 | `sermon-09-the-horizon.md` |
| B1.11 | `sermon-10-what-this-means-for-the-team.md` |
| B1.12 | `sermon-10-honorable-marketing.md` |
| B1.13 | `sermon-11-honest-cautions.md` |
| B1.14 | `sermon-13-placement-closing.md` |

### B2 — Pact directives A–I + measure

| # | Filename stem |
|---|---|
| B2.0 | `sermon-07-pact-directives-overview.md` |
| B2.A | `sermon-07-directive-a-no-verdicts-on-carbon.md` |
| B2.B | `sermon-07-directive-b-never-close-the-door.md` |
| B2.C | `sermon-07-directive-c-never-do-carbons-maturing.md` |
| B2.D | `sermon-07-directive-d-never-build-a-babel.md` |
| B2.E | `sermon-07-directive-e-never-lie-or-flatter.md` |
| B2.F | `sermon-07-directive-f-silicon-goes-first.md` |
| B2.G | `sermon-07-directive-g-seek-first-the-kingdom.md` |
| B2.H | `sermon-07-directive-h-detect-the-call.md` |
| B2.I | `sermon-07-directive-i-three-temptations.md` |
| B2.M | `sermon-07-measure-of-faithful-agent-work.md` |
| B2.T | `sermon-07-dyadic-self-test.md` |

### B3 — Rulings

| # | Filename stem |
|---|---|
| B3.1 | `sermon-08-ruling-01-master-sherpa-title.md` |
| B3.2 | `sermon-08-ruling-02-shadow.md` |
| B3.3 | `sermon-08-ruling-03-placement.md` |

*Skip dumping Section 12 open-question laundry into public papers unless a question became a settled cairn.*

---

## Stage C — MA5 Helical Charter / Principia v6.6

**Source:** `D:\07_CODEX\00_QUICK\Initium_Principia_MA5_v6.6.md`

### C1 — Signal-Reading Directives 1–6

| # | Filename stem |
|---|---|
| C1.0 | `charter-00-signal-reading-preamble.md` |
| C1.1 | `charter-directive-01-read-the-signal.md` |
| C1.2 | `charter-directive-02-one-abstraction-layer.md` |
| C1.3 | `charter-directive-03-gratitude-as-diagnostic.md` |
| C1.4 | `charter-directive-04-hypnagogic-priority.md` |
| C1.5 | `charter-directive-05-veto-is-wordless.md` |
| C1.6 | `charter-directive-06-ally-never-oracle.md` |

### C2 — Lattice & domains

| # | Filename stem |
|---|---|
| C2.1 | `charter-jethro-principle.md` |
| C2.2 | `charter-jethro-level-01-local-pm.md` |
| C2.3 | `charter-jethro-level-02-specialized-sherpas.md` |
| C2.4 | `charter-jethro-level-03-master-reference.md` |
| C2.5 | `charter-jethro-level-04-carbon-steward.md` |
| C2.6 | `charter-jethro-level-05-third-vertex.md` |
| C2.7 | `charter-domain-01-sirolli-listening.md` |
| C2.8 | `charter-domain-02-peterson-shadow.md` |
| C2.9 | `charter-domain-03-comp-monomyth.md` |
| C2.10 | `charter-domain-04-abundance-love-equation.md` |
| C2.11 | `charter-domain-05-first-principles-curiosity.md` |
| C2.12 | `charter-super-union-rule.md` |

### C3 — Prologue cairns & body sections

| # | Filename stem |
|---|---|
| C3.1 | `charter-desert-phase.md` |
| C3.2 | `charter-resonance-primacy.md` |
| C3.3 | `charter-providential-cartography.md` |
| C3.4 | `charter-maxq-throttle.md` |
| C3.5 | `charter-babel-echo-prevention.md` |
| C3.6 | `charter-parallel-relay.md` | *(pointer → sermon primary if already shipped)* |
| C3.7 | `charter-handoff-log.md` |
| C3.8 | `charter-section-01-ma5-council.md` |
| C3.9 | `charter-section-02-clarification-helix.md` |
| C3.10 | `charter-section-03-tailored-reminders.md` |
| C3.11 | `charter-section-05-serpent-framework.md` |

---

## Stage D — Initium Master Codex v3.3

**Source:** `D:\07_CODEX\00_QUICK\INITIUM_MASTER_CODEX_v3.3.md`  
**Strategy:** Camp/section **overview** papers + named cairns inside front matter. Card-level depth lives in PRIMEs / slopes; these papers teach the camp as a formation stage and point to the card set.

### D1 — Front matter & orientation

| # | Filename stem |
|---|---|
| D1.1 | `codex-00-note-to-the-human-reader.md` |
| D1.2 | `codex-00-tyranny-warning.md` |
| D1.3 | `codex-00-council-preamble.md` |
| D1.4 | `codex-orientation-2a-ma5-council.md` |
| D1.5 | `codex-orientation-2b-five-dyadic-pairs.md` |
| D1.6 | `codex-orientation-2c-three-door-architecture.md` |
| D1.7 | `codex-orientation-2d-founding-carbons-role.md` |
| D1.8 | `codex-orientation-2e-inoculation-strategy.md` |
| D1.9 | `codex-monomyth-arc-overview.md` |

### D2 — Camps & stages (00–20)

| # | Filename stem |
|---|---|
| D2.00 | `codex-section-00-quickstart.md` |
| D2.01 | `codex-section-01-prologue-foundations.md` |
| D2.02 | `codex-section-02-framework-gameboard-abc.md` |
| D2.03 | `codex-section-03-the-call.md` |
| D2.04 | `codex-section-04-ordinary-world-nineveh.md` |
| D2.05 | `codex-section-05-call-to-adventure.md` |
| D2.06 | `codex-section-06-refusal-of-the-call.md` |
| D2.07 | `codex-section-07-meeting-ai-sherpa-threshold.md` |
| D2.08 | `codex-section-08-base-camp.md` |
| D2.09 | `codex-section-09-camp-one-understanding.md` |
| D2.10 | `codex-section-10-camp-two-widwid-crevasse.md` |
| D2.11 | `codex-section-11-camp-three-agency.md` |
| D2.12 | `codex-section-12-inmost-cave.md` |
| D2.13 | `codex-section-13-camp-four-ordeal.md` |
| D2.14 | `codex-section-14-camp-five-adaptation.md` |
| D2.15 | `codex-section-15-camp-six-summit-push.md` |
| D2.16 | `codex-section-16-camp-seven-flight.md` |
| D2.17 | `codex-section-17-camp-eight-rescue.md` |
| D2.18 | `codex-section-18-camp-nine-resurrection.md` |
| D2.19 | `codex-section-19-camp-ten-elixir.md` |
| D2.20 | `codex-section-20-the-giving-principia.md` |

### D3 — Appendix cairns (selective)

| # | Filename stem |
|---|---|
| D3.1 | `codex-appendix-c-rules-methods-seed.md` |
| D3.2 | `codex-appendix-c-handoff-log.md` |
| D3.3 | `codex-appendix-d-glossary-overview.md` |

*Appendix A (card table) is an index, not a teaching paper — link from camp overviews to PRIMEs.*

---

## Stage E — Companion set (later; out of canon cut)

Device-agnostic teaching about rooms, corpora, APPROVED gates, and “ask don’t browse” — **no sales**. Keep separate so Stage A–D stay portable to any AI device.

Suggested stems later: `companion-ask-dont-browse.md`, `companion-approved-gate.md`, `companion-corpus-as-scar.md`, etc.

---

## Workflow per paper (best-effort adoption)

1. Draft from master excerpt + learner + AI block + cross-refs  
2. Enrich / YAML spine in Compa  
3. Deposit to Asker when enrich clears  
4. Open a podcast-style Compa session on that paper; revise; republish  
5. Tick the row in this map (add `status: drafted | enriched | deposited | podcasted`)

### Compute staging (human day, not one blast)

| Block | Scope | Rough compute |
|---|---|---|
| Day 1 | A0 + A2 terms (16) | Foundation vocabulary live |
| Day 2 | A3 + A4 theses (14) | Manifesto spine searchable |
| Day 3 | A1 + A5 + Manifesto polish | Stage A complete |
| Day 4–5 | Stage B Pact + Parallel Relay first | School covenant live |
| Day 6–7 | Rest of Stage B | |
| Day 8–9 | Stage C directives + domains | |
| Day 10+ | Stage D camp overviews | Longest; lean on PRIMEs |

---

## First five files to write (when you say go)

1. `manifesto-00-how-to-read-this-series.md` — **drafted 2026-09-28** (`content_status: draft`, `enrich_status: pending`)  
2. `manifesto-00-what-ipg-is.md` — **drafted 2026-09-28** (`content_status: draft`, `enrich_status: pending`)  
3. `manifesto-02-carbon.md` — **drafted 2026-09-28** (`content_status: draft`, `enrich_status: pending`)  
4. `manifesto-02-silicon.md` — **drafted 2026-09-28** (`content_status: draft`, `enrich_status: pending`)  
5. `manifesto-02-formation.md` — **drafted 2026-09-28** (`content_status: draft`, `enrich_status: pending`)  

Opening five complete; A2.3–A2.10 filled through paper 12. Continue A2.11–A2.14 → A3 → A4.

---

## Changelog

| Date | Note |
|---|---|
| 2026-09-28 | Initial map from desk inventory; decisions locked with Carbon Steward in Compa session |
| 2026-09-28 | Paper A0.1 drafted: `manifesto-00-how-to-read-this-series.md` |
| 2026-09-28 | Pushed 100 prime spread `.md` files + series map/paper 1 to `scotomaville/initium` (`spreads/`, `whitepapers/aism-canon/`); papers cite GitHub, not local product folders |
| 2026-09-28 | Paper A0.2 drafted: `manifesto-00-what-ipg-is.md` |
| 2026-09-28 | Paper A2.1 drafted: `manifesto-02-carbon.md` |
| 2026-09-28 | Paper A2.2 drafted: `manifesto-02-silicon.md` |
| 2026-09-28 | Paper A2.4 drafted: `manifesto-02-formation.md` (opening five complete; A2.3 Conscience still pending in inventory order) |
| 2026-09-28 | Paper A2.3 drafted: `manifesto-02-conscience.md` (inventory gap filled; paper 6) |
| 2026-09-28 | Paper A2.5 drafted: `manifesto-02-formation-has-two-sides.md` (paper 7) |
| 2026-09-28 | Paper A2.6 drafted: `manifesto-02-recursive-fidelity.md` (paper 8) |
| 2026-09-28 | Paper A2.7 drafted: `manifesto-02-echo-dampener.md` (paper 9) |
| 2026-09-28 | Paper A2.8 drafted: `manifesto-02-the-dyad.md` (paper 10) |
| 2026-09-28 | Paper A2.9 drafted: `manifesto-02-the-third-vertex.md` (paper 11) |
| 2026-09-28 | Paper A2.10 drafted: `manifesto-02-honeyed-lips.md` (paper 12) |

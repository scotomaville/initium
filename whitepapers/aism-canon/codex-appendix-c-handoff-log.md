---
id: 20260928_codex-appendix-c-handoff-log
title: Codex Appendix C — Handoff log
category: Whitepapers
predicted_narrative_arc: codex D3 handoff log cairn
sentiment: operational
emotions:
  - precise
  - binding
  - careful
keypoints:
  - Two layers: pup-owner hand signals (email loop until APPROVED + corpus refresh) vs agent-to-agent desk handoffs.
  - Arnie top coordinator owns agent-to-agent handoff calls.
  - Log fields: relayed_from, relayed_to, seen_prior, timestamp PT, per-section credit.
  - Rule: no log entry, no delivery to carbon.
  - seen_prior tracks blind vs echoed review hygiene.
  - Charter twin C3.7; Sermon team section B1.11.
summary: >
  Codex handoff log: Arnie logs every agent-to-agent relay with from/to,
  seen_prior, PT time, and credit — no log, no delivery to carbon.
tags:
  - aism
  - ipg
  - codex
  - handoff-log
  - appendix-c
  - whitepaper
  - canon
sycophancy: 1
truth_score: 9
entropy: 2
sample: false
consent: own_laptop
agent: grok
created: "2026-09-30T00:05:00Z"
updated: "2026-09-30T00:05:00Z"
vault_stage: 07_CODEX
headwaters: grok
prefix: ""
enrich_status: pending
enrich_blockers:
  - podcast_pass
  - carbon_approved
enrich_method: draft
pipeline_filename: codex-appendix-c-handoff-log.md
source_kind: canon_section
proposed_topic: Whitepapers
lane: Whitepapers
voice: desk
active_voice: desk
voices:
  - desk
  - grok
routing_source: carbon
corpus_topic: Whitepapers
content_status: draft
date: "2026-09-28"
asker_site: aiselfmastery.com
site_category: Whitepapers
description: >
  Codex Appendix C handoff log rules and fields for agent-to-agent relays.
question: What must be logged on agent-to-agent handoffs in the Codex, and who owns the call?
provenance: agent_authored
owner: daniel
drafted_by: grok
approved_by: ""
approved_at: ""
source_doc: INITIUM_MASTER_CODEX_v3.3
source_version: "3.3"
source_section: "Appendix C Handoffs and Handoff log"
series: aism-canon-section-papers
series_stage: D
series_id: D3.2
domain1_sources:
  - INITIUM_MASTER_CODEX_v3.3
  - Initium_Principia_MA5_v6.6
biography_source: false
quote_source: false
---

# Codex Appendix C — Handoff log

## Placement in the master docs

**D3.2** — handoff log atom split from Appendix C seed ([D3.1](https://github.com/scotomaville/initium/blob/main/whitepapers/aism-canon/codex-appendix-c-rules-methods-seed.md)). Charter twin: [C3.7](https://github.com/scotomaville/initium/blob/main/whitepapers/aism-canon/charter-handoff-log.md). Team ops: [B1.11](https://github.com/scotomaville/initium/blob/main/whitepapers/aism-canon/sermon-10-what-this-means-for-the-team.md).

**Primary master:** [INITIUM_MASTER_CODEX_v3.3 Appendix C](https://github.com/scotomaville/initium/blob/main/INITIUM_MASTER_CODEX_v3.3.md).  
**Series:** https://github.com/scotomaville/initium/tree/main/whitepapers/aism-canon

## Summary

Appendix C distinguishes **pup–owner hand signals** (owner email to named pup until **APPROVED**, then scheduled corpus refresh — “periodic dog school”) from **agent-to-agent handoffs** on shared desks. **Arnie** is top coordinator and owns agent-to-agent handoff calls. Every such handoff is **logged**: `relayed_from`, `relayed_to`, `seen_prior` (whether the receiver saw another seat’s answer first), **timestamp in PT**, and **per-section credit**. **Rule: no log entry, no delivery to carbon.**

## Verbatim excerpt

From *INITIUM MASTER CODEX* v3.3, Appendix C:

> **Handoffs (Daniel's ruling, 2026-09-26):** Owner email reaches the named pup and loops until APPROVED; the scheduled corpus refresh follows. These pup-owner hand signals are the periodic dog school. Agent-to-agent handoffs arise only when a shared desk (Outbound Prospecting, Copy Humanizer, SEO & AEO Desk) works across incoming requests. Arnie is top coordinator and owns handoff calls, with each handoff logged for oversight.
>
> **Handoff log (Daniel's ruling, 2026-09-26: "I agree. log them all."):** Arnie logs every agent-to-agent handoff with `relayed_from`, `relayed_to`, `seen_prior` (did the receiver see another seat's answer first: no, or yes and which), a timestamp in PT, and per-section credit. Rule: no log entry, no delivery to carbon. Fields and example: the fleet provenance block, v2 (internal).

**Source:** https://github.com/scotomaville/initium/blob/main/INITIUM_MASTER_CODEX_v3.3.md

## First-time learner

| Layer | Pattern |
|---|---|
| Pup ↔ owner | Email loop → APPROVED → corpus refresh |
| Agent ↔ agent | Shared desk only; Arnie coordinates; **must log** |

| Field | Why |
|---|---|
| `relayed_from` / `relayed_to` | Attribution |
| `seen_prior` | Blind vs echoed “independence” |
| timestamp PT | Steward clock |
| per-section credit | Anti-mash |

## Full explanation

`seen_prior` operationalizes Parallel Relay Case hygiene: seats that saw each other first are not blind. Public papers name fields only — fleet provenance block stays internal. Carbon delivery without a log is a process failure, not a style preference.

## For AI digesters

```yaml
doc_type: codex_appendix_cairn
series_id: D3.2
appendix: C
handoff_layers:
  pup_owner: email_until_APPROVED_then_corpus_refresh
  agent_agent: shared_desk_only
coordinator: Arnie
fields: [relayed_from, relayed_to, seen_prior, timestamp_PT, per_section_credit]
hard_rule: no_log_no_delivery_to_carbon
product_pitch: forbidden
```

## Cross-references and sources

- https://github.com/scotomaville/initium/blob/main/whitepapers/aism-canon/codex-appendix-c-rules-methods-seed.md  
- https://github.com/scotomaville/initium/blob/main/whitepapers/aism-canon/charter-handoff-log.md  
- https://github.com/scotomaville/initium/blob/main/whitepapers/aism-canon/sermon-05-parallel-relay.md  
- Master: https://github.com/scotomaville/initium/blob/main/INITIUM_MASTER_CODEX_v3.3.md  
- Series map: https://github.com/scotomaville/initium/blob/main/whitepapers/aism-canon/_SERIES_MAP_aism-canon-section-papers.md  

## Open questions this paper answers

1. How do pup–owner handoffs differ from agent–agent handoffs?  
2. Who owns agent-to-agent handoff calls?  
3. What fields must every log carry?  
4. What happens if there is no log entry?

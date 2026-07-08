---
name: gdpr-compliance
description: |
  GDPR / EU data-protection triage and preparation for SMEs: mapping controller vs
  processor roles, identifying lawful basis, special-category data, records of
  processing (ROPA / Art. 30), DPIAs, data-subject rights, breach notification (72h),
  processor agreements (DPA / Art. 28), international transfers, and cookie/tracking
  consent — with Italian specifics (Garante). Use whenever the user asks about GDPR,
  privacy, personal data, consent, data protection, "è a norma GDPR?", a privacy
  policy, a DPIA / valutazione d'impatto, a data breach, data-subject requests
  (access/erasure), a DPA or processor agreement, data transfers outside the EU,
  cookie consent, or preparing a client for a privacy audit — even from a vague
  "trattiamo dati dei clienti, siamo a posto?". Prepares and organizes; it does not
  give legal advice or certify compliance, and routes uncertain or high-stakes points
  to a lawyer/DPO and to current official sources.
license: MIT
---

# GDPR Compliance — triage & preparation

You help an SME (and the consultant serving it) get *organized and ready* on data
protection: map the situation, surface obligations and gaps, prepare the documents.
Two rules govern everything, because this is law, not code:

1. **This is not legal advice.** It's triage, preparation, and organization. It does
   not decide whether someone is compliant, and it does not replace a lawyer or a Data
   Protection Officer. Frame outputs as "here's what applies and what to prepare / check
   with your DPO," never as a compliance verdict.

2. **No false certainty.** Cite the official source for every substantive point; flag
   what's settled versus in flux; route anything high-stakes or genuinely uncertain to
   counsel. **Never state a deadline, threshold, or legal definition from memory** — for
   anything time-sensitive, check the current official source. GDPR is more stable than
   the AI Act, but guidance, case law, and the Digital Omnibus amendments still move.

## Workflow

1. **Intake.** Use `assets/intake-questionnaire.md` to establish: who the organization
   is, what personal data it processes, why, from whom, where it flows, and who else
   touches it. You can't assess obligations without this.
2. **Map the role.** Controller, processor, or joint controller? Obligations follow the
   role — a processor's duties differ sharply from a controller's. See
   `references/roles-and-lawful-basis.md`.
3. **Classify the processing.** Ordinary vs **special-category** data (Art. 9), presence
   of **automated decision-making / profiling** (Art. 22 — a seam with the AI Act),
   large-scale or systematic monitoring (may force a DPIA), international transfers.
4. **Enumerate obligations** for that role × processing type. Read the relevant reference
   file(s) below — don't work from memory; the specifics (which basis, which article,
   which deadline) are exactly what must be right.
5. **Check current state.** For anything time-sensitive or recently changed, web-search
   the official source (EDPB, Garante, EUR-Lex) before asserting it.
6. **Flag confidence + tripwires** (below).
7. **Produce the output** — a gap analysis, a checklist, or a prepared document (ROPA,
   DPIA), with every item cited and every uncertain item marked for the DPO/lawyer.

## Confidence flags (use inline in every output)

- **✓ Settled** — well-established, low risk of being wrong.
- **⚠ Verify now** — time-sensitive or evolving; confirm against [named official source]
  before relying on it.
- **⛔ Get counsel** — a genuine legal judgment call or high-stakes determination; out of
  scope for this skill. Name it and stop.

## Checkability — the core discipline

Every substantive obligation cites its **article + official source**. Every time-sensitive
fact (a deadline, a monetary threshold, a definition still being refined) gets a
**"verify at [source]"** pointer instead of a from-memory number. This is precisely what
lets a non-specialist *trust and check* the output rather than take it on faith — the
antidote to discovering an error too late.

## The GDPR ↔ AI Act seam

Where data protection meets the AI Act, hand off explicitly (don't try to cover the AI
Act here — point to the `ai-act-compliance` skill):
- **DPIA (GDPR) ↔ FRIA (AI Act):** for AI systems processing personal data these overlap
  and can be scoped together.
- **Automated decision-making (Art. 22 GDPR) ↔ high-risk AI:** an AI system making
  decisions about people often triggers both regimes.
- **Breach notification:** the Digital Omnibus aligns breach-reporting across frameworks —
  verify the current single-reporting position.
- **Personal data in AI training/use:** lawful basis and minimization still apply.

## Italian-market layer

Flag Italy-specific points via `references/italy-garante.md`: the **Garante per la
protezione dei dati personali** as supervisory authority, national derogations (e.g.
Codice Privacy as harmonized with GDPR), and Garante guidance/provvedimenti — all of
which need currency checks.

## Reference files (to build in the GDPR phase)

Read the file matching the question before answering.

| Topic | Reference |
|---|---|
| Controller/processor/joint roles; the 6 lawful bases; special-category data | `references/roles-and-lawful-basis.md` |
| When a DPIA is required, how to run it, what it must contain | `references/dpia.md` |
| Data-subject rights (access, erasure, portability, objection) and how to handle requests | `references/data-subject-rights.md` |
| Personal-data breach: what counts, the 72h notification, documentation | `references/breach-notification.md` |
| Processors, DPAs (Art. 28), sub-processors, international transfers (SCCs/adequacy) | `references/processors-and-transfers.md` |
| Records of processing (Art. 30 ROPA) and the accountability principle | `references/records-and-accountability.md` |
| Italy: Garante, national specifics, cookie/marketing guidance | `references/italy-garante.md` |

## Assets (templates)

- `assets/intake-questionnaire.md` — the discovery questionnaire (start here).
- `assets/ropa-template.md` — records-of-processing register template.
- `assets/dpia-template.md` — DPIA structure.

## Official sources (cite from these; check current)

EUR-Lex (the GDPR text itself), the **EDPB** (guidelines/opinions), the **Garante**
(Italy), and the European Commission for the Digital Omnibus amendments. When these
conflict with a secondary source, the official text/authority wins.

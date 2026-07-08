# Italy: the Garante and national specifics

> Italy applies the GDPR through the **Codice Privacy** (D.lgs. 196/2003 as amended by D.lgs. 101/2018)
> and the supervision of the **Garante per la protezione dei dati personali**. **Verify national
> specifics and any recent Garante provvedimenti/linee guida on garanteprivacy.it before asserting them.**

## The supervisory authority
- **Garante per la protezione dei dati personali** is Italy's data-protection authority: guidance,
  investigations, sanctions, prior consultation, breach notifications, and the national DPIA list.
- Breaches are notified to the Garante via its **online procedure**; data-subject complaints go to the
  Garante too.

## National layer worth flagging
- **Codice Privacy** harmonised with the GDPR: national derogations and specifics (e.g. age of digital
  consent set at **14** in Italy, employment-context rules, some special-category specifics). ⚠ Verify the
  exact figure/rule when it matters.
- **Workplace monitoring** interacts with the **Statuto dei Lavoratori (art. 4, L. 300/1970)**: remote
  controls on employees have constraints beyond the GDPR. Flag for any employee-monitoring or AI-at-work
  case (seam with `ai-act-compliance`).
- **Cookies and tracking:** follow the Garante's **cookie guidelines** and the ePrivacy rules (consent for
  non-technical cookies, no pre-ticked boxes, an accept/reject-symmetric banner). ⚠ Verify the current
  Garante cookie guidance.
- **Marketing / telemarketing:** Italian rules (Registro Pubblico delle Opposizioni) and Garante
  provvedimenti apply on top of the GDPR.

## The Garante and AI
The Garante has been active on AI and personal data (it has intervened on generative-AI services). For AI
processing personal data, its guidance stacks on top of the AI Act. Hand the AI-Act-specific questions to
the `ai-act-compliance` skill, but keep the **data-protection** analysis here.

## How to use this file
- For an Italian client, state that the GDPR applies **directly**, and the **Codice Privacy + Garante**
  add national specifics (age of consent, workplace monitoring, cookies, marketing).
- For anything national and time-sensitive (a specific provvedimento, the current cookie rules), ⚠ verify
  on garanteprivacy.it rather than asserting from memory.

## Official sources
- **Garante** — garanteprivacy.it (provvedimenti, linee guida, FAQ, breach and complaint procedures).
- **Normattiva** — consolidated Codice Privacy (D.lgs. 196/2003) and D.lgs. 101/2018.
- **EDPB** — europa.eu, for EU-level guidelines the Garante applies.

## Confidence
- That the **Garante** supervises and the **Codice Privacy** applies is ✓ **Settled**.
- Specific figures (age of consent), current cookie/marketing rules, and individual provvedimenti are ⚠:
  verify on the official sources above.

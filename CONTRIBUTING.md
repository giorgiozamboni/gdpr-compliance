# Contributing to gdpr-compliance

Thanks for wanting to make gdpr-compliance better. This skill deals with **law**, so contributions must
keep it **accurate, correctly sourced, and clearly non-advisory**.

## Good first contributions

- **Reference detail.** Add concrete, article-cited guidance to `references/` (roles-and-lawful-basis,
  dpia, data-subject-rights, breach-notification, processors-and-transfers, records-and-accountability,
  italy-garante).
- **Currency fixes.** When guidance or law changes (e.g. the Digital Omnibus on breach notification or the
  definition of personal data), update the affected file with the **official source** and the date verified.
- **Template improvements.** Sharpen the intake questionnaire, the ROPA template, or the DPIA template.
- **Italian specifics.** Garante provvedimenti, cookie/marketing rules, workplace-monitoring specifics.
- **Trigger keywords.** Real phrasing (EN or IT) the skill missed.

## Ground rules (non-negotiable)

1. **Not legal advice.** Triage and preparation only. No file may read as a compliance verdict. Keep the
   "route to DPO/counsel" (⛔) framing.
2. **No deadline, threshold, or definition from memory.** Cite the **article**, and add a **"verify at
   [official source]"** pointer for anything time-sensitive (the breach deadline is exactly such an item).
3. **Official sources win.** EUR-Lex, the EDPB, and the Garante over any secondary source.
4. **Confidence flags** on substantive points: ✓ Settled · ⚠ Verify now · ⛔ Get counsel.
5. **No em dashes.** House style: period, comma, colon, or parentheses.

## How to submit

1. Fork the repo and create a branch.
2. Make your change. If you touched `SKILL.md`, keep the `description` under 1024 characters.
3. Open a pull request stating the source you checked and the date you verified it.

## Reporting issues

Found a stale deadline, a wrong article reference, or a missing obligation?
[Open an issue](https://github.com/giorgiozamboni/gdpr-compliance/issues) with the official source and what
it should say.

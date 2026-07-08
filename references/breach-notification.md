# Personal-data breach notification

> A personal-data breach has strict, time-boxed duties (Arts. 33-34). This is an area the **Digital
> Omnibus** proposes to change, so it carries a strong ⚠. **Verify the current rule against Arts. 33-34
> EUR-Lex and the Garante before quoting any threshold or deadline.**

## What counts as a breach (Art. 4(12))
A breach of security leading to accidental or unlawful **destruction, loss, alteration, unauthorised
disclosure of, or access to** personal data. It is not only "data stolen": ransomware (loss of
availability) and accidental disclosure count.

## The two notifications (current law)
1. **To the supervisory authority (Art. 33)** — **without undue delay and, where feasible, within 72
   hours** of becoming aware, **unless** the breach is **unlikely to result in a risk** to individuals. If
   later than 72 hours, give reasons. In Italy, notify the **Garante** (via its online procedure).
2. **To the affected individuals (Art. 34)** — **without undue delay** **when** the breach is likely to
   result in a **high risk** to them, in clear language, with the nature of the breach, likely
   consequences, and measures. Exceptions: strong encryption of the affected data, measures that neutralise
   the high risk, or disproportionate effort (then a public communication).

## Always: internal documentation (Art. 33(5))
Document **every** breach (facts, effects, remedial action), even those you decide not to notify. This is
how you demonstrate the decision was reasoned.

## ⚠ What the Digital Omnibus would change (PROPOSED, published 19 Nov 2025, not yet adopted)
Do not apply these yet; flag them as coming and **verify status**:
- **Raise the authority-notification threshold** to "likely to result in a **high risk**", aligning it with
  the data-subject-notification threshold (fewer, higher-impact notifications).
- **Extend the deadline from 72 to 96 hours.**
- **A single EU entry point** for incident reporting across GDPR, NIS2, eIDAS, DORA, etc.
- (Separately) a **tightened definition of personal data** codifying the CJEU *SRB* case (relative
  identifiability).

Until adopted and in force, **the current regime applies: 72 hours, current threshold.** The EDPB has
issued a position; the proposal is contested. Treat any change as ⚠ until it appears in the OJ.

## Incident-response quick checklist
1. Contain and assess (what data, how many people, what risk).
2. Start the clock at "awareness"; log everything.
3. Decide: authority notification? individual notification? (apply the current thresholds).
4. Notify the Garante within the deadline if required; notify individuals if high risk.
5. Record the reasoning and remediation. Review controls (link to the `security-audit` skill).

## Confidence
- The **structure (two notifications + internal log)** is ✓ **Settled**.
- The **exact threshold and deadline** are ⚠ **because a change is in the pipeline**: verify which regime
  is in force at the time of the breach.

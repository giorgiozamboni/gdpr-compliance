# Data Protection Impact Assessment (DPIA)

> When processing is **likely to result in a high risk** to individuals, a DPIA (Art. 35) is required
> **before** processing starts. **Verify triggers against Art. 35, the EDPB DPIA guidelines (WP248), and
> the Garante's list of processing requiring a DPIA.**

## When a DPIA is required (Art. 35)
Mandatory in at least these cases:
- **Systematic and extensive evaluation / profiling** with legal or similarly significant effects.
- **Large-scale** processing of **special-category** (Art. 9) or **criminal** (Art. 10) data.
- **Large-scale systematic monitoring** of a publicly accessible area.

Beyond these, use the **EDPB's nine criteria** (evaluation/scoring, automated decisions with significant
effect, systematic monitoring, sensitive data, large scale, matching/combining datasets, vulnerable data
subjects, innovative use of technology, preventing rights/access to a service). ⚠ Meeting **two or more**
usually means "do a DPIA". Also check the **Garante's national list** of processing that requires one.

The AI seam: an AI system doing profiling or automated decisions about people frequently triggers **both**
a DPIA and, under the AI Act, a **FRIA**. Scope them together (hand off to `ai-act-compliance`).

## What a DPIA must contain (Art. 35(7))
1. A **systematic description** of the processing and its purposes (incl. legitimate interest, if used).
2. An assessment of **necessity and proportionality**.
3. An assessment of the **risks** to the rights and freedoms of data subjects.
4. The **measures** to address the risks (safeguards, security, mechanisms to protect data and demonstrate
   compliance).

Use `assets/dpia-template.md`. Consult the DPO (where one exists) and, where appropriate, seek data
subjects' views.

## Prior consultation (Art. 36)
If, after mitigation, a **high residual risk** remains, you must **consult the supervisory authority**
(the Garante in Italy) **before** processing. ⛔ This is a judgment call: name it.

## How to use this file
1. Screen the processing against the mandatory cases + EDPB nine criteria + the Garante list.
2. If a DPIA is needed, run the four-part structure and record it.
3. If high residual risk remains after mitigation, flag **prior consultation** with the Garante.

## Confidence
- The **trigger logic and required content** are ✓ **Settled**.
- **Whether a specific processing crosses the "high risk" line**, and whether prior consultation is
  needed, are ⚠/⛔ (verify against the Garante list and route close calls to the DPO/counsel).

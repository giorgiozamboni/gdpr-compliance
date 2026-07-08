# GDPR intake questionnaire

> Start here. You cannot assess obligations without this map of who, what, why, from whom, where it flows,
> and who else touches the data. Fill it before classifying anything.

## A. The organisation
1. Name, sector, size (number of employees), EU/Italy establishment.
2. Is there a **DPO**? If not, has the DPO trigger been assessed? (see records-and-accountability.md)
3. Who owns data protection internally?

## B. What personal data, and why
4. List the **processing activities** (e.g. customer management, marketing, HR/payroll, website analytics,
   support, an AI feature). One row each.
5. For each: **purpose(s)** and the intended **lawful basis** (Art. 6).
6. **Categories of data subjects** (customers, prospects, employees, applicants, minors, suppliers).
7. **Categories of data** per activity. Any **special-category** (health, biometrics, etc.) or **criminal**
   data? Any data on **minors**?
8. **Automated decision-making / profiling** with significant effects? (Art. 22 → also `ai-act-compliance`)

## C. Where the data comes from and goes
9. **Source**: directly from the person, or from third parties?
10. **Recipients**: who receives it (internally and externally)?
11. **Processors/vendors**: every SaaS/cloud/tool touching personal data. Is there a **DPA** for each?
    Known **sub-processors**?
12. **International transfers**: does any data leave the EEA (including remote access/support from abroad)?
    Which transfer tool (adequacy / SCCs+TIA)?

## D. How long, how secure
13. **Retention**: how long is each category kept, and why?
14. **Security measures** in place (Art. 32): access control, encryption, backups, logging. (→ security-audit)
15. **Privacy notice** given to data subjects? Where and when?

## E. Rights, breaches, risk
16. How are **data-subject requests** received and handled today? (intake, deadline tracking)
17. Any **breach** history and a documented **response process**?
18. Any processing likely to be **high risk** (profiling, large-scale sensitive data, monitoring) → **DPIA**?

## F. Italy specifics
19. **Employee monitoring**, **cookies/tracking**, **marketing/telemarketing**? (Garante + Statuto dei
    Lavoratori + ePrivacy, see italy-garante.md)

## Output of intake
- A processing inventory (feeds the **ROPA**, `assets/ropa-template.md`).
- Role per activity (controller/processor/joint).
- A gap shortlist: missing DPAs, transfers without a tool, no privacy notice, DPIA triggers, rights process.
- Confidence flags on each item (✓ / ⚠ verify at source / ⛔ counsel).

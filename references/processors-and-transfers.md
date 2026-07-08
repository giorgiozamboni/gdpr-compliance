# Processors, DPAs, sub-processors, and international transfers

> Two topics that trip up SMEs constantly: the contracts with your vendors (Art. 28) and sending data
> outside the EU (Chapter V). **Verify against Arts. 28 and 44-49 EUR-Lex, the EDPB transfer guidance, and
> the current Commission adequacy decisions and SCCs.**

## Processor agreements (Art. 28 — the "DPA")
Whenever a **processor** handles personal data for you (cloud host, SaaS, email/marketing tool, analytics,
an AI API), you need a **written contract** (a Data Processing Agreement) that includes the Art. 28(3)
mandatory terms:
- Process **only on documented instructions**.
- **Confidentiality** of personnel.
- **Security** measures (Art. 32).
- **Sub-processors** only with authorisation + flow-down of the same duties.
- **Assist** the controller with data-subject rights and with Arts. 32-36 (security, breach, DPIA).
- **Delete or return** data at the end of the service.
- Make available information to demonstrate compliance and **allow audits**.

⚠ Using a vendor with **no DPA** (or with unvetted **sub-processors**) is one of the most common SME gaps.
For AI vendors, check what they do with your inputs (training? retention?) and whether that matches your
notice and basis.

## Sub-processors
The processor's sub-processors (e.g. the sub-cloud a SaaS runs on) must be authorised and bound by
equivalent terms. Keep a list; watch for change-notifications.

## International transfers (Chapter V)
Sending personal data **outside the EEA** (including many cloud/AI services, and remote access from a third
country) needs a **transfer tool**:
1. **Adequacy decision (Art. 45)** — the destination country (or framework) is deemed adequate by the
   Commission. ⚠ Verify the current list and any framework specifics (these change).
2. **Appropriate safeguards (Art. 46)** — most commonly the **Standard Contractual Clauses (SCCs)**, plus a
   **Transfer Impact Assessment (TIA)** assessing the destination's laws and adding supplementary measures
   where needed (post-*Schrems II*). Also BCRs for groups.
3. **Derogations (Art. 49)** — explicit consent, contract necessity, etc.: narrow, case-by-case, not for
   routine bulk transfers.

⚠ "The data is in the EU region" is not the end of the analysis: **remote access** from a third country and
**sub-processors** abroad are transfers too.

## How to use this file
1. Inventory every vendor touching personal data; confirm a **valid DPA** and the **sub-processor** list.
2. For each, map **where the data actually goes** (including support access) and confirm a transfer tool +
   TIA where it leaves the EEA.
3. For AI vendors specifically, confirm inputs are not used for training unless that is covered.

## Confidence
- The **need for a DPA and a transfer tool** is ✓ **Settled**.
- **Adequacy status of a given country/framework** and **whether a TIA's safeguards suffice** are ⚠/⛔:
  verify current Commission decisions and route hard calls to counsel.

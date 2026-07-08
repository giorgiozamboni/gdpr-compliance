# GDPR roles, lawful bases, and special-category data

> Obligations follow the **role** and the **lawful basis**. Get both right first. **Verify articles
> against the GDPR text on EUR-Lex and current EDPB guidance.**

## Roles (who is who)
- **Controller (Art. 4(7))** — decides the **purposes and means** of processing. Bears the primary
  accountability. An SME processing its own customers/employees is usually a controller.
- **Processor (Art. 4(8))** — processes **on behalf of** a controller, on its instructions (e.g. a SaaS
  vendor, a cloud host, an email tool). Duties are narrower but real (Art. 28, 32).
- **Joint controllers (Art. 26)** — two parties jointly determine purposes and means; they must agree and
  document who does what, especially on data-subject rights.

⚠ Getting the role wrong cascades: a "processor" that decides purposes is really a controller. Check what
the party actually **decides**, not what the contract labels it.

## The six lawful bases (Art. 6)
Every processing needs **one** basis, fixed before you start:
1. **Consent (Art. 6(1)(a))** — freely given, specific, informed, unambiguous, revocable. Not "freely
   given" if bundled or if there is a power imbalance (often weak for employees).
2. **Contract (b)** — necessary to perform a contract with the data subject (or pre-contract steps).
3. **Legal obligation (c)** — required by EU/Member-State law (e.g. tax, accounting).
4. **Vital interests (d)** — life-or-death situations.
5. **Public task (e)** — official authority / public interest.
6. **Legitimate interests (f)** — your (or a third party's) legitimate interest, **balanced** against the
   data subject's rights (do and document a **LIA**, legitimate-interests assessment). Not available to
   public authorities for their tasks.

Pick the **most appropriate** basis; do not stack "consent + legitimate interests" as a hedge. Marketing,
profiling, and cookies interact with consent and ePrivacy (see italy-garante.md).

## Special-category data (Art. 9)
Data revealing racial/ethnic origin, political opinions, religion, trade-union membership, genetic data,
biometric data for unique identification, **health**, sex life, or sexual orientation is **prohibited to
process** unless an Art. 9(2) exception applies (explicit consent, employment/social-security law,
substantial public interest, health-care, etc.). Criminal-conviction data has its own regime (Art. 10).

→ If a system does biometric identification or infers sensitive traits, this is also an **AI Act** matter
(hand off to the `ai-act-compliance` skill).

## The transparency duty (Arts. 13-14)
Whatever the basis, you must tell people (privacy notice): who you are, purposes and bases, recipients,
retention, transfers, their rights, and (for indirect collection) the source.

## How to use this file
1. Fix the **role** for each processing activity.
2. Assign the **lawful basis** per purpose; for legitimate interests, record the LIA; for consent, check
   it is truly free and revocable.
3. Flag **special-category** and **criminal** data as needing an Art. 9/10 gateway.

## Confidence
- Roles, the six bases, and Art. 9 are ✓ **Settled** (stable core of the GDPR).
- The **right basis for a specific processing** and **whether consent is valid** in a given context are
  often ⚠/⛔ (route to DPO/counsel and current EDPB guidance).

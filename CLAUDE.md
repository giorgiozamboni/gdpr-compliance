# CLAUDE.md — gdpr-compliance (Claude Skill)

> Mappa per Claude Code. Corta e aggiornata: è la prima cosa che leggo a ogni sessione.

## Cos'è
Claude Skill che aiuta una PMI (e il consulente che la segue) a **organizzarsi e prepararsi** sulla
protezione dei dati: mappa la situazione, fa emergere obblighi e gap, prepara i documenti (ROPA, DPIA).
**Non è consulenza legale**: cita l'articolo e la fonte ufficiale, e instrada al DPO/legale i punti delicati.

- **Categoria:** Skill · **Stato:** attivo · **v0.9.0** (contenuto legale da rivedere)
- **Stack:** Claude Skill, Markdown

## Due regole non negoziabili (in testa a `SKILL.md`)
- **Non è consulenza legale.** Triage, preparazione, organizzazione; mai un verdetto di conformità.
- **Nessuna falsa certezza.** Cita la fonte per ogni punto sostanziale; **mai** una scadenza/soglia/
  definizione a memoria: per il time-sensitive, verifica la fonte ufficiale (il GDPR è più stabile
  dell'AI Act, ma il **Digital Omnibus** tocca breach e definizione di "dato personale").

## Come si avvia / testa (SENZA spendere)
- Non è un'app: si attiva su *"siamo a norma GDPR?"*, *"data breach"*, *"serve una DPIA?"*, *"cookie/consenso"*,
  *"trattiamo dati dei clienti, siamo a posto?"*.
- Test dal vivo: `cp -r . ~/.claude/skills/gdpr-compliance`.
- **Serve accesso web** per verificare le fonti: la skill NON restringe gli strumenti (nessun `allowed-tools`).

## Mappa file → responsabilità
| File / Cartella | Ruolo |
|---|---|
| `SKILL.md` | Workflow, confidence flag, seam con AI Act, indice reference |
| `references/roles-and-lawful-basis.md` | Titolare/responsabile/contitolare, 6 basi (Art. 6), dati particolari (Art. 9) |
| `references/dpia.md` | Quando serve una DPIA, contenuto, consultazione preventiva (Art. 36) |
| `references/data-subject-rights.md` | Diritti (accesso, cancellazione, portabilità, opposizione) e gestione richieste |
| `references/breach-notification.md` | Cos'è un breach, 72h all'autorità, comunicazione agli interessati (+ modifiche Omnibus) |
| `references/processors-and-transfers.md` | DPA (Art. 28), sub-responsabili, trasferimenti extra-UE (SCC/adeguatezza) |
| `references/records-and-accountability.md` | ROPA (Art. 30), accountability, DPO, by-design |
| `references/italy-garante.md` | Garante, Codice Privacy, cookie, marketing, monitoraggio lavoratori |
| `assets/intake-questionnaire.md` · `ropa-template.md` · `dpia-template.md` | Template operativi |

## Seam con altre skill
- **`ai-act-compliance`**: DPIA↔FRIA, ADM Art. 22↔high-risk AI. Passa lì la parte AI Act.
- **`security-audit`**: misure di sicurezza tecniche (Art. 32), breach come incidente.

## Dettagli on-demand (Progressive Disclosure)
- `references/` — leggi **solo** il file che serve; ogni punto sostanziale con articolo + fonte.
- `_MAP.md` — generato dal sync dashboard: **non modificare a mano**.

## Convenzioni
- Contenuto in EN (scatta anche in IT). **Niente em-dash**. Confidence flag inline: ✓ Settled · ⚠ Verify now · ⛔ Get counsel.

## NON toccare / attenzione
- Non affermare scadenze/soglie a memoria (specie il breach: 72h attuali, ma l'Omnibus propone 96h). Usa i "verify pointer".

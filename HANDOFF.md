# HANDOFF — gdpr-compliance (Claude Skill)

> Passaggio di consegne tra sessioni. Prima di chiudere, aggiorna QUI stato e prossimi passi.

## AS-IS — dove siamo
- `SKILL.md` pre-esistente (era in `files2/`). **Reference (7) e template (3) scritti il 2026-07-08**, con verifica web delle parti volatili (Digital Omnibus lato GDPR).
- Portata a standard MySkill: vestito completo (README, LICENSE, CONTRIBUTING, scheda, banner, git locale).
- Stato: attivo · **v0.9.0** · **non pubblicata**.

## Punto critico (leggere prima di usarla con clienti)
- Contenuto **legale**. Il core GDPR è stabile; la skill impone "non è consulenza legale" e "verifica sulle fonti".
- **Fatti verificati il 2026-07-08 (da ri-verificare):** il **Digital Omnibus** (proposta 19 nov 2025, **NON adottata**) propone di alzare la soglia di notifica all'autorità a "rischio elevato", **72h → 96h**, punto unico UE di segnalazione, e una ridefinizione di "dato personale" (CJEU SRB). **Finché non è adottato vale il regime attuale: 72h.** L'EDPB ha una posizione critica.
- Italia: **Garante** + **Codice Privacy** (D.lgs. 196/2003 e 101/2018); età consenso digitale 14; monitoraggio lavoratori (art. 4 Statuto); cookie guidelines: tutti con "verify pointer".

## TO-BE — prossimi passi
- [ ] **Revisione legale** delle reference prima dell'uso con clienti → poi v1.0.0.
- [ ] Aggiornare `breach-notification.md` e `italy-garante.md` quando il Digital Omnibus è adottato/in GUUE.
- [ ] Test dal vivo: `cp -r . ~/.claude/skills/gdpr-compliance`, provare 3 casi (ROPA da zero, un data breach, una richiesta di accesso).
- [ ] Repo GitHub pubblico e primo push (**azione da confermare**, non fatta).

## Decisioni & gotcha
- **v0.9.0** apposta: contenuto scritto ora, da rivedere. Non spacciarlo per parere legale.
- Nessun `allowed-tools`: serve il web per verificare le fonti.
- Coppia con `ai-act-compliance` (seam DPIA↔FRIA, Art. 22↔high-risk). `_MAP.md` rigenerato dal sync. **Niente em-dash**.

## Storico (leggero · più recente in alto)
- 2026-07-08 — Cartella creata da `files2/`, reference+template scritti con ricerca fonti, portata a standard.

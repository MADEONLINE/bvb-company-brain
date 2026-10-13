---
id: 202610131207
title: Attivare il plugin BVB Marketing OS
type: project
status: attivo
area: "[[Marketing OS BVB]]"
deadline: 2026-10-31
tags: [marketing-os, plugin, progetto]
aliases: [Plugin marketing, Rollout plugin]
created: 2026-10-13
updated: 2026-10-13
review: 2026-10-27
---

# Attivare il plugin BVB Marketing OS

## Obiettivo
Entro il 31 ottobre 2026 Massimo e Marta usano il plugin Claude Code `bvb-marketing-os` per i lavori di marketing quotidiani (piano settimanale, reel, articoli, lead magnet, schede prodotto, LinkedIn, newsletter, tagging, ads) con la stessa catena Analista → Stratega → Regista del backend, e il plugin resta allineato alle skill del repo.

## Prossima azione
- [ ] Installare il plugin: `/plugin marketplace add madeonline/bvb-ai-os` poi `/plugin install bvb-marketing-os@bvb-ai-os` (oppure `claude --plugin-dir ./plugins/bvb-marketing-os` dal repo).
- [ ] Primo uso guidato: `/bvb-marketing-os:piano-settimana 2026-W43` con i connettori Airtable e Brevo attivi; confrontare l'output con il piano del backend.
- [ ] Decidere i comandi che Marta usa da sola (scheda-prodotto, newsletter-brevo, tagging-brevo) e quelli che richiedono Massimo (campagna-ads, linkedin-*).

## Stato
2026-10-13 — Plugin creato nel repo (`plugins/bvb-marketing-os`): 9 agenti, 18 comandi, 27 skill sincronizzate con `npm run sync-plugin`, marketplace alla radice. Non ancora installato da nessuno.

## Collegamenti
- Area: [[Marketing OS BVB]]
- Mappa: [[MOC Marketing OS BVB]], [[MOC Ruoli]]
- Note atomiche pertinenti: [[La pubblicazione resta umana]], [[Ogni contenuto nasce con obiettivo e KPI]]
- Risorse: [[Plugin BVB Marketing OS]], [[Backend BVB AI OS]]
- Persone: [[Massimo Serreri]], [[Marta Dessena]]

## Log decisioni
- 2026-10-13 — Progetto aperto.
- 2026-10-13 — Il plugin replica i ruoli come agenti e le skill come copie sincronizzate, non come link: deve funzionare anche fuori dal repo ([[Decisione — Catena Analista Stratega Regista]]).

## Packet prodotti
- [[Brief standard tra i ruoli]], [[Checklist qualità del Regista]]

## Domande aperte
- I comandi devono creare direttamente i record Airtable quando il connettore è attivo, o consegnare solo il testo del record? Da decidere dopo due settimane d'uso.

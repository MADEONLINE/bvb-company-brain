---
id: 202610131208
title: Speciality tagging dei contatti Brevo
type: project
status: attivo
area: "[[Canale Email Brevo]]"
deadline: 2026-11-15
tags: [email, brevo, progetto]
aliases: [Tagging Brevo, Segmentazione per specialità]
created: 2026-10-13
updated: 2026-10-13
review: 2026-10-27
---

# Speciality tagging dei contatti Brevo

## Obiettivo
Entro il 15 novembre 2026 ogni contatto attivo delle 36 liste Brevo ha compilati INTERESSE_PRINCIPALE, SPECIALITA, RUOLO_CLINICA, TIPO_STRUTTURA, FONTE, STEP_PERCORSO e LEAD_SCORE, i 9 segmenti standard esistono in Brevo, le liste duplicate sono unificate e la newsletter mensile parte per segmento invece che per lista.

## Prossima azione
- [x] Attributi SPECIALITA (multi-scelta) e RUOLO_CLINICA (testo) creati in Brevo il 13 ottobre 2026 via n8n, con i valori della tassonomia in [[Skill bvb-brevo-speciality-tagging]].
- [ ] Eseguire `/bvb-marketing-os:tagging-brevo "lista 2" --solo-proposta` e rivedere la tabella con Marta prima di applicare.
- [ ] Unificare "Clienti AI Start" id 21 e 22 e decidere la sorte di WooCommerce_NonSubscribers (id 35).

## Stato
2026-10-13 — Progetto aperto. Skill di tagging pronta (tassonomia, regole, segmenti, blocchi `json:brevo-action`). Attributi SPECIALITA e RUOLO_CLINICA creati nell'account il 13 ottobre 2026. Lista newsletter: 320 iscritti; Lead Magnet Guida Sistema Agentico (id 42) a 0 iscritti, da rilanciare.

## Collegamenti
- Area: [[Canale Email Brevo]]
- Mappa: [[MOC Canali]]
- SOP: [[SOP Speciality tagging Brevo]]
- Note atomiche pertinenti: [[Il tagging per specialità rende l'email pertinente]], [[Il Master non si propone mai ai contatti freddi]]
- Risorse: [[Brevo account BVB]], [[Specialist Email Brevo]]
- Persone: [[Marta Dessena]]

## Log decisioni
- 2026-10-13 — Progetto aperto.
- 2026-10-13 — Attributi creati via workflow n8n temporaneo con la credenziale "Brevo account 2"; la credenziale "Brevo account" ha la chiave disabilitata.
- 2026-10-13 — Nessuna cancellazione di contatti: i dormienti vanno in una lista dedicata dopo 90 giorni senza aperture.

## Packet prodotti
- 

## Domande aperte
- Per i contatti senza fonte nota (import storici), si assegna STEP_PERCORSO = freddo o si lascia vuoto e si chiede con un sondaggio di 1 domanda in newsletter?

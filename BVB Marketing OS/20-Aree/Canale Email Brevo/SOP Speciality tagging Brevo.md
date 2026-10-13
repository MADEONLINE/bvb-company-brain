---
id: 202610131220
title: SOP Speciality tagging Brevo
type: sop
area: "[[Canale Email Brevo]]"
owner: "[[Marta Dessena]]"
version: 1
tags: [sop, email, brevo]
aliases: [SOP tagging]
created: 2026-10-13
updated: 2026-10-13
review: 2026-11-13
---

# SOP Speciality tagging Brevo

## Scopo
Ogni contatto Brevo ha attributi coerenti che permettono di inviare il messaggio giusto allo step giusto e di misurare da dove arrivano i clienti.

## Quando si applica
Ogni settimana sui nuovi contatti; in blocco nel progetto [[Speciality tagging dei contatti Brevo]]; a ogni acquisto o iscrizione. Comando: `/bvb-marketing-os:tagging-brevo`.

## Chi
Specialist Email Brevo (proposta e blocchi di azione), Marta (applicazione e creazione attributi), n8n (tagging automatico su acquisto e iscrizione, dove configurato).

## Procedura
1. Leggere i contatti (connettore Brevo o CSV) con fonte di iscrizione, liste, prodotti acquistati, comportamento.
2. Assegnare secondo la tassonomia: INTERESSE_PRINCIPALE (management, AI, business, leadership), SPECIALITA (multi), RUOLO_CLINICA (titolare, manager, DVM, ASV, front office), TIPO_STRUTTURA, FONTE, STEP_PERCORSO (freddo → lead → cliente-entry → cliente-live → alumni → master), LEAD_SCORE 0–100.
3. Dichiarare la regola usata per ogni assegnazione; in dubbio, lasciare vuoto e proporre il sondaggio a 1 domanda.
4. Produrre i blocchi `json:brevo-action`; con `--solo-proposta` solo la tabella.
5. Marta applica (o approva l'applicazione via connettore); nessuna cancellazione, i dormienti vanno nella lista dedicata dopo 90 giorni senza aperture.
6. Aggiornare i 9 segmenti standard e verificarne la dimensione.

## Errori frequenti
- Assegnare STEP_PERCORSO = cliente a chi ha solo scaricato un lead magnet.
- Dedurre la specialità dal nome della clinica senza evidenza.
- Cancellare contatti invece di spostarli.

## Materiali e link
- [[Skill bvb-brevo-speciality-tagging]], [[Brevo account BVB]], [[Il tagging per specialità rende l'email pertinente]]

## Storico revisioni
- v1 — 2026-10-13 — prima stesura

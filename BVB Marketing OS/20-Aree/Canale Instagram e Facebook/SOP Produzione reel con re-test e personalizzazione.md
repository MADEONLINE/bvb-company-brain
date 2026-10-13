---
id: 202610131214
title: SOP Produzione reel con re-test e personalizzazione
type: sop
area: "[[Canale Instagram e Facebook]]"
owner: "[[Marta Dessena]]"
version: 1
tags: [sop, social, reel]
aliases: [SOP reel]
created: 2026-10-13
updated: 2026-10-13
review: 2026-11-28
---

# SOP Produzione reel con re-test e personalizzazione

## Scopo
Produrre ogni reel BVB come esperimento a una variabile, personalizzato sulla clinica veterinaria italiana, e trasformare in template ciò che supera la mediana.

## Quando si applica
A ogni reel per Instagram e Facebook (e ai derivati per YouTube Shorts e LinkedIn), nuovo o rifatto. Comando del plugin: `/bvb-marketing-os:reel-retest`; singolo reel: `/bvb-marketing-os:reel`.

## Chi
Ruolo Analista (baseline e lettura), Ruolo Regista (griglia e qualità), Specialist Social Instagram Facebook (script), Specialist Grafica e Video (asset, Buzzy), Massimo (riprese in camera, approvazione se porta la sua firma), Marta (approvazione e Upload-Post).

## Procedura
1. **Baseline** (Analista, venerdì): mediana a 30 giorni di views, reach, salvataggi, condivisioni, retention 3 s; top 3 e bottom 3 con ipotesi; 5 domande del pubblico da comment-mining. Senza baseline non si produce.
2. **Riferimenti** (Analista): smontare 3 reel con bvb-reel-analyzer (1 nostro top, 2 esterni del settore), generare 10 hook con bvb-hook-mining.
3. **Griglia** (Regista): compilare la [[Griglia di test reel]]: 6 celle in 2 settimane, una variabile per cella, controllo dichiarato, data e orario (7:45 / 12:45 / 19:15). Record Airtable in `idea` con campo "variabile in test".
4. **Script** (Specialist Social): hook nei primi 3 s (testo + parlato), promessa, 3 beat, CTA; 20–45 s; sottotitoli; cover; copy con prima riga = hook; 3–5 hashtag.
5. **Personalizzazione obbligatoria**: scena di clinica italiana nei primi 3 s; ruoli reali (titolare, front office, DVM, ASV); un numero della clinica; lessico del titolare; grafica e font brand; nessun template "da imprenditore".
6. **Produzione** (Grafica e Video): varianti faceless con Buzzy `faceless-reels` (o `ugc-ads` per testimonianze), prompt in inglese, revisione umana; varianti in camera con indicazioni di ripresa per Massimo (inquadratura, luce, durata per beat, testo da dire e da mostrare). Sessione unica da 60 minuti per 3 reel.
7. **Qualità** (Regista): [[Checklist qualità del Regista]] completa; record in `bozza`.
8. **Approvazione e pubblicazione** (Marta): stato `approvato`; BVB-SOCIAL-05 pubblica via Upload-Post nell'orario della griglia.
9. **Lettura** (Analista, venerdì successivo): a 7 giorni, variante contro controllo; vince con +30% su salvataggi o retention 3 s. Record in `analizzato`.
10. **Template**: due vittorie consecutive → nota packet "Template reel [nome]" in 70-Packet con hook, struttura, scena; aggiornare [[MOC Reel]].

## Errori frequenti
- Cambiare due cose insieme (hook e durata): il risultato non insegna nulla.
- Giudicare dalle views: un reel che gira ma non viene salvato non porta iscritti.
- Hook generici ("Vuoi far crescere la tua clinica?"): niente scena, niente numero.
- Pubblicare fuori dagli orari della griglia: l'orario è una variabile e va tenuto fermo.
- Video AI con volti realistici di persone non consenzienti o loghi di terzi.

## Materiali e link
- [[Griglia di test reel]], [[Checklist qualità del Regista]], [[Metriche Meta Graph API]], [[Buzzy e generazione video]]
- Skill: [[Skill bvb-content-audit]], [[Skill bvb-reel-analyzer]], [[Skill bvb-hook-mining]], [[Skill bvb-reel-architect]], [[Skill bvb-video-director]], [[Skill higgsfield-social-hook]]
- Progetto: [[Ritestare e personalizzare i reel BVB]]

## Storico revisioni
- v1 — 2026-10-13 — prima stesura

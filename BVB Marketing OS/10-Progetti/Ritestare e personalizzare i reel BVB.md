---
id: 202610131206
title: Ritestare e personalizzare i reel BVB
type: project
status: attivo
area: "[[Canale Instagram e Facebook]]"
deadline: 2026-11-28
tags: [social, reel, progetto]
aliases: [Re-test reel, Protocollo reel]
created: 2026-10-13
updated: 2026-10-13
review: 2026-10-24
---

# Ritestare e personalizzare i reel BVB

## Obiettivo
Entro il 28 novembre 2026 avere 2–3 template di reel BVB che superano stabilmente la mediana a 30 giorni su salvataggi e retention al secondo 3, ottenuti con 6 settimane di test a una variabile, e sostituire i reel "generici da imprenditore" con reel personalizzati sulla clinica veterinaria italiana (scene, ruoli, numeri, lessico, grafica brand).

## Prossima azione
- [ ] Eseguire `/bvb-marketing-os:reel-retest 6 30` (o chiedere al backend l'audit) per fissare la baseline: mediana views, reach, salvataggi, condivisioni, retention 3 s; top 3 e bottom 3 con ipotesi. Scrivere i numeri nella sezione Stato.
- [ ] Smontare 3 reel di riferimento con bvb-reel-analyzer (1 nostro top, 2 esterni) e generare 10 hook con bvb-hook-mining.
- [ ] Compilare la [[Griglia di test reel]] per le settimane 43 e 44 e creare i 6 record Airtable in stato `idea` con il campo "variabile in test".
- [ ] Registrare con Massimo 3 reel in camera (stesso script delle 3 varianti faceless Buzzy) in un'unica sessione di 60 minuti.

## Stato
2026-10-13 — Progetto aperto su nota di Massimo: i reel vanno ritestati e personalizzati. Il sistema di produzione (bvb-reel-architect, bvb-video-director, Buzzy, Upload-Post, metriche Meta con mediana) è in produzione; manca un protocollo che tratti i reel come esperimenti. Baseline ancora da leggere: `[DA AGGIORNARE: mediana views / reach / saved / retention 3 s]`.

Suggerimenti immediati (da eseguire nella prima settimana):
1. Non produrre reel nuovi senza aver letto la baseline: tre giorni di audit valgono più di dieci reel alla cieca.
2. Primo test sull'hook: tre reel con lo stesso corpo e tre hook diversi (domanda, numero della clinica, errore comune). È la variabile con il ritorno più rapido.
3. Secondo test sul formato: lo stesso script in camera (Massimo) e faceless (Buzzy `faceless-reels`). Decide i dati, non il gusto.
4. Personalizzazione minima obbligatoria da subito: scena di clinica nei primi 3 secondi, un ruolo reale nominato, un numero, sottotitoli, cover brand.
5. CTA "salva" o "commenta [parola]" al posto di "link in bio" finché il reel non ha dimostrato di trattenere.
6. Lettura il venerdì, criterio di vittoria +30% sul controllo su salvataggi o retention; le views da sole non contano.

## Collegamenti
- Area: [[Canale Instagram e Facebook]]
- Mappa: [[MOC Reel]]
- SOP: [[SOP Produzione reel con re-test e personalizzazione]]
- Decisione: [[Decisione — Reel come esperimenti a una variabile]]
- Note atomiche pertinenti: [[I reel si giudicano contro la mediana, non in assoluto]], [[Un reel cambia una sola variabile per volta]]
- Skill: [[Skill bvb-content-audit]], [[Skill bvb-reel-analyzer]], [[Skill bvb-hook-mining]], [[Skill bvb-reel-architect]], [[Skill bvb-video-director]]
- Persone: [[Massimo Serreri]] (riprese in camera, approvazione), [[Marta Dessena]] (pubblicazione)

## Log decisioni
- 2026-10-13 — Progetto aperto.
- 2026-10-13 — I reel si testano una variabile alla volta, 6 reel in 2 settimane, lettura il venerdì ([[Decisione — Reel come esperimenti a una variabile]]).

## Packet prodotti
- [[Griglia di test reel]]

## Domande aperte
- Buzzy `faceless-reels` regge la voce italiana con il lessico del titolare, o serve ElevenLabs con voce clonata di Massimo (con suo consenso)?
- Quanti reel al mese può registrare Massimo in camera senza che la qualità cali? Da fissare dopo la prima sessione.

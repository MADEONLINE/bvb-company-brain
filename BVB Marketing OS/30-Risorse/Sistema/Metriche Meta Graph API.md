---
id: 202610131238
title: Metriche Meta Graph API
type: resource
tags: [social, sistema]
aliases: [Metriche reel, Mediana reel]
created: 2026-10-13
updated: 2026-10-13
confidence: alta
sources: ["docs/RUNBOOK_SETUP_SOCIAL_ENGINE.md"]
related: ["[[Ruolo Analista]]"]
---

# Metriche Meta Graph API

## Sintesi
Il sistema legge da Meta Graph API (v21.0) le metriche di reel e post Instagram e Facebook: reach, views, salvataggi, condivisioni, commenti, e calcola la mediana a 30 giorni e il multiplo di ogni contenuto rispetto a essa. È il benchmark ufficiale dei reel e la base del progetto di re-test.

## Punti chiave
- Giudizio di un reel: ×mediana su salvataggi e retention al secondo 3, non views assolute.
- Il token Meta è nelle variabili d'ambiente di Render; scade e va rinnovato (procedura nel runbook).
- Lettura ufficiale il venerdì a 7 giorni dalla pubblicazione.
- Retention al secondo 3 va letta da Insights quando l'API non la espone: segnare `[NON LETTO]` se manca.

## Collegamenti
- [[I reel si giudicano contro la mediana, non in assoluto]] — perché: il principio che ne deriva.
- [[SOP Report performance del venerdì]], [[SOP Produzione reel con re-test e personalizzazione]]
- [[Canale Instagram e Facebook]]

## Domande aperte
- La retention per secondo è disponibile via API per i reel della pagina o solo in Insights?

## Fonti
- [[Runbook setup social engine]]

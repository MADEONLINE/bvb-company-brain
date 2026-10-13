---
id: 202610131235
title: Linea n8n BVB-SOCIAL
type: resource
tags: [marketing-os, sistema]
aliases: [BVB-SOCIAL, Workflow social n8n]
created: 2026-10-13
updated: 2026-10-13
confidence: alta
sources: ["docs/RUNBOOK_SETUP_SOCIAL_ENGINE.md"]
related: ["[[Backend BVB AI OS]]", "[[Upload-Post publisher]]"]
---

# Linea n8n BVB-SOCIAL

## Sintesi
Diciotto workflow n8n numerati BVB-SOCIAL-01…18 che coprono intake (RSS, YouTube, fonti), produzione, pubblicazione (05, via Upload-Post), guardiano degli errori (11), raccolta metriche e aggiornamento degli stati del Calendario editoriale. Tutti esposti via MCP per il backend e per Claude.

## Punti chiave
- Critici: 05 publisher e 11 guardiano.
- Anomalia risolta il 13 ottobre 2026: BVB-SOCIAL-01c (intake RSS YouTube) falliva ogni giorno alle 6:30 con 404 dal feed; il channel id UCu1q-wnJ6ka9_rrhpNu_-kg è corretto e il feed risponde a mano. Aggiunto retry (3 tentativi) sul nodo RSS e schedule spostato alle 7:10. Da verificare il 14 ottobre.
- Le combinazioni Blotato sono state rimosse.
- Non si duplicano workflow: si usano quelli esistenti.

## Collegamenti
- [[Upload-Post publisher]] — perché: il 05 lo chiama.
- [[Airtable Social Agentico BVB]] — perché: gli stati che i workflow leggono e scrivono.
- [[Metriche Meta Graph API]] — perché: i workflow di metriche la interrogano.
- [[Backend BVB AI OS]]

## Domande aperte
- L'esecuzione delle 7:10 del 14 ottobre è andata a buon fine? Se no, sostituire il nodo RSS con HTTP Request con User-Agent da browser (testato funzionante).

## Fonti
- [[Runbook setup social engine]]

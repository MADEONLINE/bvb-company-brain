---
id: 202610131234
title: Upload-Post publisher
type: resource
tags: [social, sistema]
aliases: [Upload-Post]
created: 2026-10-13
updated: 2026-10-13
confidence: alta
sources: ["docs/RUNBOOK_SETUP_SOCIAL_ENGINE.md"]
related: ["[[Linea n8n BVB-SOCIAL]]"]
---

# Upload-Post publisher

## Sintesi
Servizio di pubblicazione multi-piattaforma usato come unico publisher di BVB (utente `bravevetbusiness`): pagina Facebook, Instagram, pagina LinkedIn, YouTube. Chiamato dal workflow BVB-SOCIAL-05 quando un record del Calendario editoriale passa ad `approvato`.

## Punti chiave
- Orari standard di pubblicazione: 7:45, 12:45, 19:15.
- Restituisce gli id dei post usati per leggere le metriche.
- Errori intercettati dal guardiano BVB-SOCIAL-11 con avviso Telegram; il record resta in `approvato`.
- Chiave API nelle variabili d'ambiente di Render e nelle credenziali n8n, mai nei file.

## Collegamenti
- [[Decisione — Upload-Post unico publisher]] — perché: la decisione che lo rende unico.
- [[Linea n8n BVB-SOCIAL]] — perché: chi lo chiama.
- [[Canale Instagram e Facebook]], [[Canale LinkedIn]]

## Domande aperte
- Supporta la pubblicazione di caroselli PDF su LinkedIn pagina? Da testare.

## Fonti
- [[Runbook setup social engine]]

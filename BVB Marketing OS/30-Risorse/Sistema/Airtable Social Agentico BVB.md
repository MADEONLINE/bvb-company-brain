---
id: 202610131236
title: Airtable Social Agentico BVB
type: resource
tags: [marketing-os, sistema]
aliases: [Calendario editoriale, Libreria Asset]
created: 2026-10-13
updated: 2026-10-13
confidence: alta
sources: ["docs/RUNBOOK_SETUP_SOCIAL_ENGINE.md"]
related: ["[[Linea n8n BVB-SOCIAL]]"]
---

# Airtable Social Agentico BVB

## Sintesi
Base Airtable "Social Agentico BVB" con due tabelle operative: **Calendario editoriale** (stati idea → bozza → approvato → pubblicato → analizzato, con canale, formato, hook, copy, asset, data e orario, KPI, metriche) e **Libreria Asset** (file, diritti, fonte). È la fonte di verità su cosa è stato pubblicato e con quale risultato.

## Punti chiave
- Ogni contenuto nasce come record in `idea` o `bozza`; solo Marta o Massimo portano in `approvato`.
- Da aggiungere: campo "variabile in test" per i reel ([[Decisione — Reel come esperimenti a una variabile]]).
- Il venerdì i record pubblicati passano in `analizzato` con le metriche.
- Connettore Airtable disponibile per il plugin: l'Analista può leggere direttamente.

## Collegamenti
- [[Linea n8n BVB-SOCIAL]] — perché: i workflow leggono e scrivono gli stati.
- [[La pubblicazione resta umana]] — perché: lo stato `approvato` è il cancello.
- [[Marketing OS BVB]]

## Domande aperte
- Serve una vista "Test reel" con controllo e variante affiancati?

## Fonti
- [[Runbook setup social engine]]

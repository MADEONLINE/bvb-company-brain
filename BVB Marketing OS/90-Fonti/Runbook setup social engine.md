---
id: 202610131265
title: Runbook setup social engine
type: source
source_type: documento
author: Team agentico BVB
url: https://github.com/madeonline/bvb-ai-os/blob/main/docs/RUNBOOK_SETUP_SOCIAL_ENGINE.md
date_source: 2026-10-13
tags: [social, fonte]
aliases: [Runbook social]
created: 2026-10-13
updated: 2026-10-13
confidence: alta
processed: true
---

# Runbook setup social engine

## Sintesi
Procedura passo passo per mettere in produzione la linea social: variabili d'ambiente su Render, token Meta e suo rinnovo, utente e chiave Upload-Post, abilitazione MCP dei workflow n8n BVB-SOCIAL-01…18, base Airtable, script di verifica `scripts/verify_social_engine.js` e `scripts/n8n_enable_mcp.js`.

## Punti chiave
- **Workflow critici: 05 publisher e 11 guardiano.**
- Lo script di verifica è la prova che il sistema è completo.
- I segreti stanno in Render e in n8n, mai nei file.

## Note atomiche derivate
- [[La pubblicazione resta umana]]

## Domande aperte
- Aggiungere al runbook la sostituzione del channel id YouTube nell'intake 01c.

## Originale
`docs/RUNBOOK_SETUP_SOCIAL_ENGINE.md` nel [[Repo bvb-ai-os]].

---
id: 202610131263
title: Repo bvb-ai-os
type: source
source_type: documento
author: Brave Vet Business
url: https://github.com/madeonline/bvb-ai-os
date_source: 2026-10-13
tags: [marketing-os, fonte]
aliases: [bvb-ai-os]
created: 2026-10-13
updated: 2026-10-13
confidence: alta
processed: true
---

# Repo bvb-ai-os

## Sintesi
Repository GitHub del sistema operativo AI di Brave Vet Business: backend dispatcher, knowledge base (25 file), 27 skill, client React, script di sincronizzazione, documentazione di setup, plugin Claude Code `bvb-marketing-os` e questa stessa cartella (`second-brain/BVB Marketing OS`). Deploy del backend su Render dal ramo `main`.

## Punti chiave
- **`context/context_loader.js` è la verità su quali skill usa ogni agente.**
- `skills/` è la libreria; il plugin la copia con `npm run sync-plugin`.
- `knowledge/00_BRAND_CORE/prodotti_attivi.md` è il catalogo prodotti.
- `docs/BRIEF_TEAM_SOCIAL_2026-10-13.md` e `docs/RUNBOOK_SETUP_SOCIAL_ENGINE.md` documentano la linea social.
- Nessun segreto nel repo: `.env`, credenziali Google e `.mcp.json` sono ignorati da git.

## Note atomiche derivate
- [[La pubblicazione resta umana]], [[Ogni contenuto nasce con obiettivo e KPI]]

## Domande aperte
- Il repo del company brain è separato: la cartella va copiata a mano o con uno script di sincronizzazione?

## Originale
Repository remoto; non copiato nel vault.

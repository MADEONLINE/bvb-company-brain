---
id: 202610131233
title: Backend BVB AI OS
type: resource
tags: [marketing-os, sistema]
aliases: [BVB AI OS, Dispatcher BVB]
created: 2026-10-13
updated: 2026-10-13
confidence: alta
sources: ["dispatcher/server.js", "context/context_loader.js", "docs/BRIEF_TEAM_SOCIAL_2026-10-13.md"]
related: ["[[Plugin BVB Marketing OS]]", "[[Linea n8n BVB-SOCIAL]]"]
---

# Backend BVB AI OS

## Sintesi
Applicazione Node/Express su Render (deploy dal ramo `main` del repo) che fa da dispatcher a 10 agenti, ciascuno con system prompt in `knowledge/03_SUBAGENTI/` e skill assegnate in `context/context_loader.js`. Chiama i modelli Claude con prompt caching sul blocco statico, ha un Proactive Engine a cron, notifiche Telegram e un client React su Netlify.

## Punti chiave
- Agenti: social_specialist, youtube_linkedin_specialist, graphic_designer, analytics_community_manager, copy_specialist, market_analyst, digital_office_manager, email_funnel_specialist, ad_manager, platform_lms_specialist.
- Il loader inietta sempre il `SKILL.md` di ogni skill dell'agente e i riferimenti su richiesta (per intero per brave-social-planner, brave-community-manager, brave-analytics-specialist).
- Knowledge in `knowledge/` (25 file: brand core, dispatcher, marketing super agent, subagenti, workflow, monitoring).
- Variabili d'ambiente su Render: chiavi dei modelli, Telegram, Meta, Upload-Post, Airtable, Brevo. Mai nei file.
- Verifica del sistema: `scripts/verify_social_engine.js`; runbook in `docs/RUNBOOK_SETUP_SOCIAL_ENGINE.md`.

## Collegamenti
- [[Plugin BVB Marketing OS]] — perché: stessa libreria di skill, uso interattivo in Claude Code.
- [[Linea n8n BVB-SOCIAL]] — perché: il backend produce, n8n pubblica e misura.
- [[MOC Ruoli]] — perché: mappa agenti del backend ↔ ruoli del plugin.
- [[Marketing OS BVB]]

## Domande aperte
- Quando aggiungere al backend un endpoint che espone il report dell'Analista come JSON per il plugin?

## Fonti
- [[Repo bvb-ai-os]], [[Brief team social 2026-10-13]], [[Runbook setup social engine]]

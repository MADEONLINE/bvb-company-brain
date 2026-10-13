---
id: 202610131240
title: Plugin BVB Marketing OS
type: resource
tags: [marketing-os, sistema, plugin]
aliases: [bvb-marketing-os]
created: 2026-10-13
updated: 2026-10-13
confidence: alta
sources: ["plugins/bvb-marketing-os/README.md"]
related: ["[[Backend BVB AI OS]]"]
---

# Plugin BVB Marketing OS

## Sintesi
Plugin Claude Code in `plugins/bvb-marketing-os` del repo: 9 agenti (Analista, Stratega, Regista e sei specialist di canale), 18 comandi slash, le 27 skill copiate da `skills/` e il brand core copiato da `knowledge/00_BRAND_CORE`, con `context/REGOLE_OPERATIVE.md` come contratto comune. Installabile dal marketplace del repo (`.claude-plugin/marketplace.json`) o con `claude --plugin-dir`.

## Punti chiave
- Allineamento: `npm run sync-plugin` copia skill e brand; `npm run sync-plugin:check` fallisce se non allineato.
- Comandi: brief, piano-settimana, audit-contenuti, report-performance, reel, reel-retest, post-social, carosello, articolo-blog, lead-magnet, scheda-prodotto, linkedin-post, linkedin-articolo, newsletter-linkedin, newsletter-brevo, funnel-email, tagging-brevo, campagna-ads.
- Nessun comando pubblica, invia o spende.
- Funziona anche senza connettori: gli agenti chiedono gli export e dichiarano le fonti non lette.

## Collegamenti
- [[Backend BVB AI OS]] — perché: stessi ruoli, stesse skill.
- [[Attivare il plugin BVB Marketing OS]] — perché: progetto di rollout.
- [[MOC Ruoli]], [[MOC Skill]]

## Domande aperte
- Pubblicare il plugin anche in un marketplace privato separato dal repo del backend?

## Fonti
- `plugins/bvb-marketing-os/README.md` ([[Repo bvb-ai-os]]).

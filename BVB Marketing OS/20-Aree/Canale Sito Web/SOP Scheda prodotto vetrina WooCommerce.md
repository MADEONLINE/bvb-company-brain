---
id: 202610131218
title: SOP Scheda prodotto vetrina WooCommerce
type: sop
area: "[[Canale Sito Web]]"
owner: "[[Marta Dessena]]"
version: 1
tags: [sop, sito-web]
aliases: [SOP vetrina]
created: 2026-10-13
updated: 2026-10-13
review: 2026-11-13
---

# SOP Scheda prodotto vetrina WooCommerce

## Scopo
Ogni corso, evento, masterclass e consulenza del catalogo ha una scheda WooCommerce aggiornata, coerente con il catalogo e con il workflow n8n Gestione Acquisti.

## Quando si applica
Nuovo prodotto, nuova edizione o data, cambio di prezzo, revisione mensile. Comando: `/bvb-marketing-os:scheda-prodotto`.

## Chi
Specialist Sito Web (scheda), Ruolo Regista (qualità), Massimo (campi non verificabili), Marta (pubblicazione con checklist).

## Procedura
1. Specialist Sito Web legge il catalogo reale (`knowledge/00_BRAND_CORE/prodotti_attivi.md`) e produce il blocco `json:woo-product`: nome come da catalogo (città e data per i live), SKU dal foglio Unified Acquisti Tracker, prezzo verificato o `[DA AGGIORNARE]`, descrizione breve, descrizione lunga in HTML pulito (problema → cosa impari → per chi → programma → docenti → cosa include → FAQ → CTA), attributi (edizione, città, data, docenti), categoria, immagine 1200×1200, Yoast, schema Course o Event, prodotti correlati (il prodotto successivo nella scala, mai il Master dalle schede entry).
2. Regista: checklist di qualità; ogni campo non verificabile va segnalato a Massimo e la scheda resta in bozza.
3. Marta: [[Checklist pubblicazione scheda prodotto]] punto per punto; test di acquisto a 0 € con coupon di test; verifica email di benvenuto e riga nel foglio acquisti.
4. Marta avvisa Specialist Social (post di vendita) e Specialist Email Brevo (segmento) con il link pubblico.

## Errori frequenti
- SKU diverso dal foglio acquisti: il workflow non riconosce l'ordine.
- Prezzo scontato senza data di fine.
- Master collegato come prodotto correlato di una scheda entry.
- Stili inline nell'HTML.

## Materiali e link
- [[Skill bvb-woocommerce-vetrina]], [[Checklist pubblicazione scheda prodotto]], [[Catalogo prodotti e lead magnet BVB]]

## Storico revisioni
- v1 — 2026-10-13 — prima stesura

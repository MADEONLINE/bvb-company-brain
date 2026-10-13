---
id: 202610131209
title: Decisione — Upload-Post unico publisher
type: decision
status: presa
project: "[[Attivare il plugin BVB Marketing OS]]"
decided_by: "[[Massimo Serreri]]"
tags: [marketing-os, decisione, social]
aliases: [Upload-Post publisher unico]
created: 2026-10-13
updated: 2026-10-13
---

# Decisione — Upload-Post unico publisher

## Decisione
Tutti i contenuti social di Brave Vet Business (Instagram, Facebook, pagina LinkedIn, YouTube) vengono pubblicati attraverso Upload-Post, con l'utente `bravevetbusiness`, dal workflow n8n BVB-SOCIAL-05.

## Contesto
Fino a ottobre 2026 convivevano due publisher (Blotato e Upload-Post), con workflow duplicati e stati del calendario non coerenti. Alternative valutate: tenere Blotato come riserva, pubblicare a mano, usare le API native di ogni piattaforma.

## Perché
- Un solo publisher significa un solo stato "pubblicato" e un solo punto di errore controllato dal guardiano BVB-SOCIAL-11.
- Upload-Post copre tutti i canali attivi e restituisce gli id dei post per leggere le metriche.
- Pubblicare a mano era la prima causa di contenuti approvati e mai usciti.

## Conseguenze attese
- Tutti i workflow e le combinazioni Blotato sono stati rimossi ([[Decisione — Blotato dismesso]]).
- Se Upload-Post fallisce, il contenuto resta in `approvato` e Marta viene avvisata su Telegram: non si pubblica da un'altra parte.

## Cosa ci farebbe cambiare idea
- Upload-Post che perde il supporto a un canale attivo o supera il 5% di pubblicazioni fallite al mese per due mesi.

## Collegamenti
- [[Upload-Post publisher]], [[Linea n8n BVB-SOCIAL]], [[Marketing OS BVB]]

# BVB Marketing OS — cartella per il BVB company brain

Questa cartella è una sezione pronta da incollare nel vault Obsidian "BVB company brain". Contiene la conoscenza del team agentico di marketing di Brave Vet Business al 13 ottobre 2026: ruoli, specialist di canale, skill, sistema in produzione, SOP per canale, decisioni, progetti aperti (a partire dal re-test dei reel), KPI e mappe di contenuto.

## Come inserirla nel company brain

1. Clonare il repo `MADEONLINE/bvb-company-brain` dentro il vault (`git clone https://github.com/MADEONLINE/bvb-company-brain`): contiene questa cartella e riceve gli aggiornamenti con `git pull`. In alternativa copiare la cartella a mano.
2. I link `[[...]]` sono per nome di nota e si risolvono ovunque la cartella venga messa; i nomi sono prefissati (Canale…, Ruolo…, Specialist…, Skill…, SOP…, MOC…) per non collidere con note già esistenti nel vault.
3. Se il vault ha già `_templates`, cancellare la copia qui dentro: sono gli stessi 13 template dello schema canonico.
4. Aprire [[MOC Marketing OS BVB]]: è la porta d'ingresso.
5. Prima review: 13 novembre 2026 (campo `review` nelle note di area e progetto).

## Cosa c'è dentro

| Cartella | Contenuto |
|---|---|
| `10-Progetti` | 3 progetti aperti e 5 decisioni retroattive |
| `20-Aree` | l'area Marketing OS BVB e 5 aree di canale, ciascuna con le proprie SOP |
| `30-Risorse` | ruoli direttivi, specialist, 27 note Skill (generate), sistema in produzione, KPI, catalogo |
| `50-Note` | 9 note atomiche: i principi che governano il sistema |
| `60-Mappe` | MOC Marketing OS BVB, MOC Canali, MOC Ruoli, MOC Skill, MOC Reel |
| `70-Packet` | brief standard, griglia di test reel, checklist del Regista, checklist scheda prodotto, sequenza 5 email |
| `80-Persone` | Massimo Serreri e Marta Dessena (solo ruolo e contesto) |
| `90-Fonti` | il repo bvb-ai-os, il brief del team social, il runbook di setup |
| `_log` | log dell'ingest del 13 ottobre 2026 |

## Manutenzione

- Le note `Skill …` e `MOC Skill` sono generate da `scripts/build_second_brain.js` nel repo `bvb-ai-os`: si modifica il `SKILL.md` e si rigenera, non si modificano a mano.
- Tutto il resto si aggiorna a mano seguendo `_istruzioni-ai.md`.
- Controllo di igiene: `python3 lint_vault.py "BVB Marketing OS" --strict` (script della skill second-brain-architect).

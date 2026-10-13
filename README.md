# BVB company brain — sezioni condivise

Repository delle sezioni del vault Obsidian "BVB company brain" generate e mantenute dal team agentico di Brave Vet Business. Ogni cartella di primo livello è una sezione pronta da aprire o da collegare nel vault.

| Sezione | Contenuto | Origine |
|---|---|---|
| `BVB Marketing OS` | ruoli, specialist, skill, sistema, SOP per canale, progetti, decisioni, KPI, mappe | repo `bvb-ai-os`, cartella `second-brain/BVB Marketing OS` |

## Uso nel vault

Clona il repo dentro il vault (o accanto, con un link simbolico):

```
cd "<cartella del vault>"
git clone https://github.com/MADEONLINE/bvb-company-brain
```

Obsidian vede le cartelle del repo come parte del vault; i link `[[...]]` si risolvono per nome di nota. Per ricevere gli aggiornamenti: `git pull` dentro la cartella clonata.

## Aggiornamenti

Le sezioni vengono rigenerate dal repo `bvb-ai-os` (note Skill da `scripts/build_second_brain.js`) e spinte qui. Le modifiche fatte a mano nel vault vanno committate qui, altrimenti il prossimo aggiornamento le sovrascrive.

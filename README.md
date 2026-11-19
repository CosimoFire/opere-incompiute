# Opere pubbliche incompiute 2025 – dataviz Radar QN

Dataviz sull'elenco-anagrafe delle opere pubbliche incompiute (art. 44-bis DL 201/2011, DM MIT 42/2013), anno di riferimento 2025: elenco nazionale (amministrazioni centrali) e 19 elenchi regionali e delle Province autonome pubblicati a giugno 2026.

Indice con anteprime e codice per il CMS: https://cosimofire.github.io/opere-incompiute/

| Dataviz | URL |
|---|---|
| Le 10 opere pubbliche incompiute più costose | https://cosimofire.github.io/opere-incompiute/top10-importo/ |
| Opere incompiute per stato dei lavori (treemap) | https://cosimofire.github.io/opere-incompiute/treemap-stato/ |
| Opere incompiute per provincia (mappa) | https://cosimofire.github.io/opere-incompiute/mappa-province/ |

## Dati (`data/`)
- `top10_importo.csv` – le 10 opere con il totale dell'intervento più alto, escluse 7 opere con dati non affidabili negli elenchi (importi incongruenti, CUP non validi o ripetuti, stato incoerente).
- `treemap_stato.csv` – opere per stato dei lavori (DM 42/2013, art. 1, lett. a/b/c) e per ente.
- `opere_province.csv` – opere per provincia (unità territoriali ISTAT), attribuite tramite il codice ISTAT del comune indicato nell'elenco.
- `province.topo.json` – confini provinciali ISTAT semplificati.

Abruzzo e Valle d'Aosta non hanno pubblicato l'elenco 2025; la Provincia di Bolzano lo ha pubblicato vuoto.

Fonte: MIT e Regioni, elenco-anagrafe delle opere incompiute. Elaborazione Radar – QN.

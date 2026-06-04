---
owner: JG
category: P
status: active
created: 2026-06-04
---

# Road Classics 2026 — Trainer (web + second brain hub)

Projekt = **interaktivny web** (tracker treningu, vyzivy, cvikov + GPX tras) napojeny na
**knowledge zapisy v second brain**. Web je vykladna skrina, pravda zije v Context dokumentoch nizsie.

## Live web

- URL: https://jurajgiacko.github.io/road-classics-2026/
- Repo (GitHub Pages): https://github.com/jurajgiacko/road-classics-2026
- Zdroj: `index.html` (single-file app) + `routes/` (GPX subory)
- Cache-busting: query param `?v=NN` v zdielanom linku (pri update bumpni cislo)

## Cielova sezona

| # | Monument | Datum | Vzdialenost | Prevysenie | Vysledok |
|---|---|---|---|---|---|
| 1 | Palava | 16.5.2026 | 123 km | 1 592 m | FINISHER 5:50:42 |
| 2 | Vysocina | 18.7.2026 | 102 km | 1 750 m | — |
| 3 | Jested | 19.9.2026 | 106 km | 2 200 m | — |

## Second brain — naviazane zapisy (zdroj pravdy)

| Oblast | Subor | Co obsahuje |
|---|---|---|
| Treningovy plan | [road-classics-training-plan-2026.md](../../Context/personal/road-classics-training-plan-2026.md) | Bloky, fazy, tyzdenne struktury, race protokoly |
| Treningovy log | [road-classics-training-log-2026.md](../../Context/personal/road-classics-training-log-2026.md) | Tyzden-po-tyzdni realne data z jazd a sily |
| Treningova historia | [training-history-reference.md](../../Context/personal/training-history-reference.md) | Referencne programy z minulosti |
| Bike purchase | [gravel-bike-purchase-decision.md](../../Context/personal/gravel-bike-purchase-decision.md) | Vyber biku (Canyon Grail CF 8), alternativy, faza 1-3, budget, oblecenie |
| Longevity / vyziva | [health-longevity.md](../../Context/personal/health-longevity.md) | Longevity stack + suplementy (zrkadli sa na webe) |

## Bike setup (zhrnutie, detaily v bike purchase decision)

- **Bike:** Canyon Grail CF 8 1by White Sprint (S) — GRX 820 1x12 (40T/10-45T), 8,88 kg
- **Pedale:** Shimano PD-EH500 (SPD/flat combo)
- **Topanky:** Shimano SH-RX801 Wide EU43
- **Computer:** Garmin Edge 840 + HRM 600 + Varia RearVue 820
- **Wheelset (Faza 2):** ICAN G27 carbon + Continental GP 5000 AS TR 35mm (road) / stock DT Swiss + Schwalbe G-One R 40mm (gravel)
- **Sedlo:** PPS 716-726 mm

## Workflow pri zmenach

1. Uprav obsah v prislusnom Context zapise (zdroj pravdy).
2. Premietni do `index.html` (data objekty: `EXERCISES`, `PLAN`, vyziva, supl.).
3. Over funkcnost (napr. YouTube odkazy cvikov cez oEmbed status 200).
4. Commit + push do `road-classics-2026` repo, bumpni `?v=NN` v zdielanom linku.

## Stav

- 2026-06-04: Opravenych 8 mrtvych YouTube odkazov pri cvikoch (overene vsetkych 53 → 0 broken). Vytvoreny tento hub.

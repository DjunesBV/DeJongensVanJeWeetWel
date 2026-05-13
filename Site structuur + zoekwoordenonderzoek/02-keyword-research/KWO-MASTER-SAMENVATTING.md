# KWO Master Samenvatting — alle SEMrush-data verwerkt

**Bron:** SEMrush Keyword Magic Tool, database NL, currency EUR.
**Datum:** 2026-05-13.
**Methode:** 70+ seeds gedraaid via Chrome-MCP. Per seed top 5-15 relevante
keywords met volume / KD / intent vastgelegd. Pagina's met < 30/mnd zonder
extra rechtvaardiging zijn geschrapt.

## Eindresultaat

| Metriek | Origineel | Na KWO | Wijziging |
| --- | --- | --- | --- |
| Totaal nieuwe URLs | 130 | 81 | **-38%** |
| Stad-subs Breda | 20 | 14 | -6 |
| Stad-subs Utrecht | 20 | 15 | -5 |
| Stad-subs Eindhoven | 20 | 13 | -7 |
| Stad-subs Rotterdam | 20 | 16 | -4 |
| Stad-subs Renesse | 20 | 8 | -12 |
| Silo's (hubs) | 5 | 5 | nieuw: pianobar + pianoshow; weg: jubileumband + pianoband |
| Silo-subs | 20 | 10 | -10 |

Concrete bestanden:
- `01-sitemap-v2.csv` — 93 URLs met hoofd-KW + volume + KD + intent + prio
- `02-keyword-research/steden/{breda,utrecht,eindhoven,rotterdam,renesse}-kwo.csv`
- `02-keyword-research/silos/silos-kwo.csv`

## Strategische bevindingen die de hele structuur raken

### 1. Pianobar is een NATIONAAL keyword, niet lokaal

- `pianobar` NL: **390/mnd** (KD 26)
- `pianobar amsterdam`: 590 (waar wij niet zitten)
- `pianobar scheveningen`: 480 (waar wij niet zitten)
- `pianobar rotterdam`: 30 (onze enige meetbare stad)
- `pianobar breda/utrecht/eindhoven/renesse`: **0**

**Implicatie:** geen 5× `/[stad]/pianobar` pagina's, maar één nationale silo
`/pianobar` + Rotterdam-specifieke vermelding. Bonus: "de grootste pianobar
van nederland" = 70/mnd → directe brand-claim positionering.

### 2. Pianoshow is de quick-win van de hele site

- `pianoshow boeken`: 110/mnd, **KD 6** — laagste KD in heel het onderzoek
- `pianoshow`: 110, KD 15
- "pianoband": slechts 30/mnd — schrap

`/pianoshow` als silo + `/pianoshow/boeken` sub is met deze KD's binnen weken
op #1 te krijgen. Past 1-op-1 op brand-positionering ("de meest geboekte
live pianoshow").

### 3. Jubileumband bestaat niet als zoekterm

- `jubileumband`: 0 volume
- `band jubileum`: alleen niche merknaam-zoekopdrachten

**Implicatie:** geen aparte `/jubileumband` silo. Integreer als sub-pagina
binnen `/bedrijfsfeest-band/bedrijfsjubileum`.

### 4. `bedrijfsfeest band` is laag direct (90), maar groot indirect

- `bedrijfsfeest band`: 90/mnd (KD 9!)
- `band voor personeelsfeest`: 40 (KD 3 — bizar laag)
- Maar cumulatief over de 5 steden: `bedrijfsuitje [stad]` levert **1.500+/mnd**
  via stad-pagina's, met KD's 6-25.

**Implicatie:** silo `/bedrijfsfeest-band` als nationale hub die naar de 5
`/[stad]/bedrijfsuitje` pagina's linkt vangt zo veel intent op.

### 5. `wat te doen in [stad]` is de grootste traffic-driver per stad

| Stad | wat te doen in [stad] | + "dit weekend" | + "vandaag" |
| --- | --- | --- | --- |
| Utrecht | 3.600 | 880 | 390 |
| Breda | 2.400 | 1.300 | 390 |
| Rotterdam | (geen exact) | - | 720 (vandaag dominant) |
| Eindhoven | (geen exact) | 480 | 590 (vandaag dominant) |
| Renesse | 480 | 110 | 140 |

**Implicatie:** elke stad-hub krijgt een prominent "vandaag/dit weekend"-agenda-
blok dat doorlinkt naar de juiste sub-pagina. Voor Rotterdam/Eindhoven is
"vandaag"-variant de dominante intent.

### 6. Vrijgezellenfeest-clusters hebben absurd lage KD's

Per stad cluster + KD's:
- Breda: 1.500/mnd, KD **3-11**
- Utrecht: 1.500/mnd, KD **5-13**
- Rotterdam: 1.500/mnd, KD **5-12**
- Eindhoven: 500/mnd, KD **3-11**

In alle steden zit een doelgroep-splitsing (`vrouwen` / `mannen`) met KD 3-8.
Overweging: aparte sub-sub-pagina's per doelgroep:
- `/[stad]/vrijgezellenfeest/vrouwen`
- `/[stad]/vrijgezellenfeest/mannen`

Niet meegenomen in v2 om scope te beperken — overweging voor v3.

### 7. Bedrijfsuitje is extreme quick-win

- Bedrijfsuitje breda: 320, **KD 6**
- Bedrijfsuitje utrecht: 880, **KD 12**
- Bedrijfsuitje eindhoven: 480, KD 24
- Bedrijfsuitje rotterdam: 390, KD 25

KD 6 voor 320/mnd is uniek. Combinatie met `/bedrijfsfeest-band` silo maakt
dit een sterke B2B funnel.

### 8. Cafe/restaurant met live muziek alleen sterk in Rotterdam

| Stad | cafe met live muziek | restaurant met live muziek |
| --- | --- | --- |
| Rotterdam | **170** (KD 16) | **140** (KD 14) |
| Utrecht | (in cluster) | 110 (KD 19) |
| Breda | 20 | 20 |
| Eindhoven | 20 | (laag) |
| Renesse | 0 | 0 |

**Implicatie:** alleen Rotterdam houdt twee aparte pagina's. Utrecht houdt
`/utrecht/restaurant-met-live-muziek` (110 is genoeg). Breda/Eindhoven/Renesse
schrappen, content opnemen als sectie binnen `/[stad]/live-muziek`.

### 9. Renesse is een ander beest

Klein toeristisch dorp, dus volumes 5-10× lager dan grote steden. Maar wel:
- `strandtent renesse`: **720/mnd** (KD 41) — TOPPER van Renesse
- `wat te doen in renesse`: 480 (KD 16)
- `vakantie renesse`: 320 (KD 17, transactional)
- `activiteiten renesse`: 320 (KD 16)
- `renesse uitgaan`: 320 (KD 21)

Renesse krijgt 8 pagina's i.p.v. 20 — gefocust op toerisme/vakantie/strandtenten.

### 10. Bruiloftband: betere primary keyword is "band voor bruiloft"

- `bruiloftband`: 170 (KD 23)
- `band voor bruiloft`: **390** (KD 16) — commercial intent
- `band bruiloft`: 480 (KD 14) — informational
- `bruiloft bands`: 390 (KD 14)

Cluster ~2.000/mnd voor de "band + bruiloft" combinatie. Silo `/bruiloftband`
slug behouden voor herkenbaarheid, maar H1 + meta gebruiken "band voor
bruiloft" als hoofd-keyword.

## Top 10 quick-wins (volume × lage KD)

| # | URL | Hoofd-KW | Volume | KD |
| --- | --- | --- | --- | --- |
| 1 | `/pianoshow` (boeken) | pianoshow boeken | 110 | **6** |
| 2 | `/breda/bedrijfsuitje` | bedrijfsuitje breda | 320 | **6** |
| 3 | `/utrecht/bedrijfsuitje` | bedrijfsuitje utrecht | 880 | 12 |
| 4 | `/bedrijfsfeest-band` | bedrijfsfeest band | 90 | **9** |
| 5 | `/utrecht/vrijgezellenfeest` | vrijgezellenfeest utrecht | 590 | 11 |
| 6 | `/breda/vrijgezellenfeest` | vrijgezellenfeest breda | 390 | 11 |
| 7 | `/rotterdam/vrijgezellenfeest` | vrijgezellenfeest rotterdam | 590 | 12 |
| 8 | `/eindhoven/date-activiteiten` | date eindhoven ideeen | 260 | **10** |
| 9 | `/coverband/coverband-bruiloft` | coverband bruiloft | 170 | 12 |
| 10 | `/renesse/wat-te-doen` | wat te doen in renesse | 480 | 16 |

## P0-pagina's om eerst te bouwen (33 stuks)

Alle 5 stad-hubs, alle 5 silo-hubs, en de top sub-pagina's met de hoogste
volume/KD-ratio per stad — staan in `01-sitemap-v2.csv` met prio = P0.

## Volgende stappen

1. **Akkoord op sitemap v2** — schrap-keuzes verifiëren
2. **Concurrentieanalyse per silo + per stad-hub** (top 10 SERP via SEMrush)
3. **Pagina-templates** per type (stad-hub, stad-sub, silo-hub, silo-sub)
4. **Content-briefings** met H-structuur per pagina (Google Docs)
5. **Interne linkmatrix** (`05-internal-links.csv`)
6. **Sync naar Google Sheets + Google Docs** voor uitvoering door collega's

# Welkom collega — start hier

> **Lees dit eerst.** Hierna weet je wat er in deze projectmap staat, hoe je
> ermee werkt, en wat je morgen kunt doen.

## Wat is dit project?

Een complete SEO-strategie voor **dejongensvanjeweetwel.nl** — De Jongens
Van Je Weet Wel, de meest geboekte live pianoshow van Nederland.

Het doel: **81 nieuwe pagina's bouwen** verdeeld over:
- 5 **stad-hubs** met sub-pagina's (Breda, Utrecht, Eindhoven, Rotterdam, Renesse)
- 5 **silo-hubs** met sub-pagina's (pianoshow, pianobar, coverband, bruiloftband, bedrijfsfeest-band)

Iedere pagina is **al onderbouwd met SEMrush-data**: hoofd-keyword, zoekvolume,
moeilijkheid, intent, prioriteit. Je hoeft niets meer te onderzoeken — alles
ligt klaar om te schrijven en publiceren.

## Hoe is de map opgebouwd?

```
Site structuur + zoekwoordenonderzoek/
│
├── START-HIER-COLLEGA.md              ← Dit bestand (lees eerst!)
├── README.md                          ← Korte project-intro
├── SITEMAP-LEESBAAR.md                ← De sitemap in begrijpelijke vorm
│
├── 06-strategie-handleiding.md        ← Workflow per pagina (hoe schrijf je 'm)
├── 08-content-calendar.md             ← 12-weken sprint-planning (wanneer wat)
│
├── 01-sitemap-v2.csv                  ← Alle 93 URLs als data (Excel/Sheets)
├── 05-internal-links.csv              ← Welke pagina linkt naar welke
├── 07-meta-titles-descriptions.csv    ← Kant-en-klare titles + meta-descriptions
│
├── 02-keyword-research/               ← SEMrush-data (alle KW's met volume + KD)
│   ├── KWO-MASTER-SAMENVATTING.md     ← Strategische bevindingen
│   ├── steden/                        ← 1 CSV per stad
│   └── silos/                         ← 1 CSV met alle silo's
│
├── 03-concurrenten/                   ← Wie rankt er nu, wat doen ze, wat missen ze
│   ├── OVERZICHT.md                   ← Rode draad over alle 5 silo's
│   └── *.md                           ← 1 bestand per silo + master CSV
│
├── 04-briefings/                      ← De brief om pagina's mee te schrijven
│   ├── TEMPLATES.md                   ← Standaard template per pagina-type
│   ├── silos/                         ← 5 silo-briefings (kort)
│   ├── steden/                        ← 5 stad-briefings met al hun sub-pagina's
│   └── quick-wins/                    ← 8 volledig uitgewerkte briefings (10 pag)
│
├── .gitignore                          ← Project is GitHub-ready
└── archief/                            ← Oude versies (niet gebruiken)
```

## Wat moet je doen om aan de slag te gaan?

### Stap 1 — Lees deze 3 documenten (30 min)
1. **`SITEMAP-LEESBAAR.md`** — wat gaan we bouwen?
2. **`06-strategie-handleiding.md`** — hoe bouwen we het?
3. **`08-content-calendar.md`** — in welke volgorde?

### Stap 2 — Open de sitemap
`01-sitemap-v2.csv` opent in Excel of Google Sheets. Filter op:
- `prioriteit = P0` (33 pagina's die als eerste komen)
- Sorteer op `kd` oplopend (laagste moeilijkheid eerst)

### Stap 3 — Begin met de eerste quick win
Open `04-briefings/quick-wins/1-pianoshow.md`. Dit is een **volledig
uitgewerkte briefing** met:
- Title-tag + meta-description (kant-en-klaar te plakken)
- H1 + 8 H2-secties met inhoudelijke richtlijnen
- 6 FAQ-vragen mét antwoorden
- Schema-markup als JSON-snippet
- Lijst met verplichte interne links
- Definition of done om af te vinken

Schrijven, publiceren, en status updaten in `01-sitemap-v2.csv` (kolom `status`
van `TBD KWO-VAL` naar `content klaar` of `live`).

### Stap 4 — Werk de calendar af
`08-content-calendar.md` geeft per dag aan welke pagina je oppakt. 12 weken,
4 sprints, ~6 pagina's per week.

## De 3 belangrijkste bestanden voor jou

| Voor wat | Open dit |
| --- | --- |
| "Welke pagina moet ik nu pakken?" | `01-sitemap-v2.csv` (filter op P0, sort KD) + `08-content-calendar.md` |
| "Hoe ziet die pagina eruit?" | `04-briefings/quick-wins/[nummer].md` (voor de 10 quick wins) of `04-briefings/silos/` of `04-briefings/steden/` |
| "Waar moet ik vandaan en naartoe linken?" | `05-internal-links.csv` (filter op je URL) |

## Veelgestelde vragen

**Hoe weet ik welke keyword bij welke pagina hoort?**
→ Staat in `01-sitemap-v2.csv` kolom `hoofd_keyword`. Volledige keyword-lijst
per pagina in `02-keyword-research/steden/[stad]-kwo.csv` of
`02-keyword-research/silos/silos-kwo.csv`.

**Welke schema markup moet ik gebruiken?**
→ In elke briefing staat het schema als JSON-snippet. Standaard:
- Stad-hub: `LocalBusiness` + `Place` + `Event` + `FAQPage`
- Stad-sub: `LocalBusiness` + `FAQPage`
- Silo-hub: `Service` + `AggregateRating` + `FAQPage` + `Offer`
- Silo-sub: `BreadcrumbList` + `FAQPage`

**Hoe weet ik wat de concurrentie doet?**
→ `03-concurrenten/[silo].md` per silo. Voor stad-pagina's: minder belangrijk
want lokale SERP is minder competitief.

**Wat als ik een keyword met 0 volume tegenkom?**
→ Dat zou niet moeten gebeuren — alles is gevalideerd. Mocht het wel: kies
een gerelateerde long-tail uit het KWO-bestand en update de sitemap-status.

**Mag ik afwijken van de briefing?**
→ Hoofd-KW, URL, title-tag en interne links zijn **vast**. Tekstuele invulling
mag je beter maken dan voorgesteld — maar maak het **beter dan de concurrentie**
(zie `03-concurrenten/` per silo voor de gaps).

**Wat zijn de quick wins?**
→ 10 pagina's met KD ≤ 16, allemaal in `04-briefings/quick-wins/`. Begin daar.
Beste 3:
1. `/pianoshow` — pianoshow boeken (KD 6)
2. `/breda/bedrijfsuitje` — bedrijfsuitje breda (KD 6)
3. `/bedrijfsfeest-band` — bedrijfsfeest band (KD 9)

## Wat is er **niet** in deze map?

- Geen voorgeschreven content (alleen briefings) — schrijven is jouw werk
- Geen technische SEO-audit van de huidige site (apart traject)
- Geen backlink-strategie (apart traject)
- Geen design-mockups (apart traject)

## Wie heeft dit gemaakt?

Sven heeft dit project samen met Claude (Anthropic's AI) opgezet over 1 dag.
Vragen over de strategische keuzes? Lees `02-keyword-research/KWO-MASTER-SAMENVATTING.md` —
daar staat de "waarom" achter alle beslissingen.

Vragen over de uitvoering? Lees `06-strategie-handleiding.md` of bel Sven.

## In één zin

> Alles wat je nodig hebt om 81 SEO-pagina's te schrijven en publiceren staat
> in deze map. Begin bij `04-briefings/quick-wins/1-pianoshow.md` en werk
> systematisch door de calendar.

**Veel succes! 🎹**

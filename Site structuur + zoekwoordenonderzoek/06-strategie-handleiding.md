# Strategie & Uitvoeringshandleiding

> Voor collega's die de SEO-strategie van De Jongens Van Je Weet Wel gaan
> uitvoeren. Lees dit één keer door, dan kun je zelfstandig pagina's bouwen
> en publiceren.

## 1. Wat is dit project?

We bouwen voor **dejongensvanjeweetwel.nl** een SEO-structuur met:
- **5 stad-hubs** met sub-pagina's (Breda, Utrecht, Eindhoven, Rotterdam, Renesse)
- **5 silo-hubs** met sub-pagina's (pianoshow, pianobar, coverband, bruiloftband, bedrijfsfeest-band)
- Totaal **81 nieuwe pagina's** (+ 12 bestaande die deels worden bijgewerkt)
- Alle pagina-keywords zijn **gevalideerd via SEMrush** (zie `02-keyword-research/`)

## 2. Bestanden in deze map — wat doe je waar mee?

| Bestand / map | Wat staat erin | Voor wie |
| --- | --- | --- |
| `SITEMAP-LEESBAAR.md` | Volledige sitemap in begrijpelijke vorm | Iedereen (project-introductie) |
| `01-sitemap-v2.csv` | Sitemap als data (Excel/Sheets-vriendelijk) | Project-management, voortgang bijhouden |
| `02-keyword-research/KWO-MASTER-SAMENVATTING.md` | 10 strategische findings | Strategie / iedereen |
| `02-keyword-research/steden/*-kwo.csv` | Alle SEMrush-data per stad | Content-schrijvers |
| `02-keyword-research/silos/silos-kwo.csv` | SEMrush-data silo's | Content-schrijvers |
| `03-concurrenten/OVERZICHT.md` | Concurrenten-rode draad | Content-schrijvers, designers |
| `03-concurrenten/*.md` (5 stuks) | Concurrentieanalyse per silo | Content-schrijvers |
| `03-concurrenten/concurrenten-master.csv` | Alle concurrenten data | Analyse |
| `04-briefings/TEMPLATES.md` | Briefing-template per pagina-type | Content-schrijvers (referentie) |
| `04-briefings/silos/*.md` (5 stuks) | Briefing per silo-hub | Schrijver bouwt de pagina |
| `04-briefings/steden/*.md` (5 stuks) | Briefing per stad-hub + sub-pagina's | Schrijver bouwt de pagina |
| `05-internal-links.csv` | Linkmatrix met regels | Iedereen die een pagina bouwt |
| `06-strategie-handleiding.md` | Dit document | Iedereen (start hier) |
| `README.md` | Korte project-intro | Iedereen |
| `01-sitemap-v1-ARCHIEF.csv` | Originele sitemap (gearchiveerd) | Niet gebruiken — historie |

## 3. URL-conventies (verplicht)

- Slugs in **lower-case** met streepjes (`/cafe-met-live-muziek`)
- Geen diakritische tekens (`cafe` niet `café`)
- Stad-hubs op root: `/breda` (sterkste lokaal signaal)
- Silo-hubs op root: `/pianoshow`
- Geen trailing slash in interne links

## 4. Pagina-bouw workflow

### Stap 1 — Pak een pagina uit `01-sitemap-v2.csv`
Begin met **P0** (33 pagina's). Sorteer op KD oplopend voor snelste wins.

### Stap 2 — Lees de briefing
- Voor silo-pagina's: `04-briefings/silos/[naam].md`
- Voor stad-hub: `04-briefings/steden/[stad].md` — bovenste sectie
- Voor stad-sub: `04-briefings/steden/[stad].md` — relevante sub-sectie
- Voor pagina-types waar geen specifieke briefing voor is: gebruik `04-briefings/TEMPLATES.md`

### Stap 3 — Schrijf de pagina volgens briefing
Verplichte elementen voor elke pagina:
- Title-tag ≤ 60 chars met hoofd-KW
- Meta-description ≤ 155 chars met CTA
- H1 met hoofd-KW
- Hoofd-KW in eerste 100 woorden
- 5-10 H2-secties (zie briefing)
- ≥ 1 foto + ≥ 1 video (gebruik bestaande content uit `/impressie` en `/video`)
- FAQPage-schema (waar relevant)
- Reviews-blok (5.0★ uit `/reviews`)

### Stap 4 — Plaats de interne links
Open `05-internal-links.csv`. Filter op je URL (kolom `van_url`). Plaats alle
**verplichte** links volgens de aanwijzingen. Optionele links waar logisch.

### Stap 5 — Schema markup
Standaard per pagina-type:
- **Stad-hub:** `LocalBusiness` + `Place` (venue) + `Event` (agenda) + `FAQPage`
- **Stad-sub:** `LocalBusiness` + `FAQPage` (+ `Event` als agenda relevant)
- **Silo-hub:** `Service` + `Organization` + `AggregateRating` + `FAQPage` + `Offer`
- **Silo-sub:** `BreadcrumbList` + `FAQPage`

### Stap 6 — Status updaten
In `01-sitemap-v2.csv` kolom `status` aanpassen:
`TBD KWO-VAL` → `briefing klaar` → `content klaar` → `live`

## 5. SEO-fundamenten (verplicht voor alle pagina's)

Deze gelden voor ELKE nieuwe pagina, geen uitzondering:

1. **Hoofd-KW** in title-tag, H1, eerste 100 woorden, en 2-3× in body
2. **Mobiel-vriendelijk** layout (test in Chrome DevTools mobile-view)
3. **Lighthouse Performance ≥ 90** (afbeeldingen comprimeren met WebP)
4. **Geen orphan-pagina's** — minimaal 1 interne link IN volgens `05-internal-links.csv`
5. **CTA-knop "Boek nu" of "Check je datum"** boven én onder de fold
6. **Schema markup** volgens pagina-type (zie 4.5)
7. **Sticky telefoon-CTA op mobile** (cross-sell op alle pagina's)
8. **Alt-tags op alle foto's** met locatie- of onderwerp-KW

## 6. Tone of voice & branding

Vanuit huidige site afgeleid:
- **Warm en energiek** — geen corporate-koud
- **"Wij" als band** — niet "het bedrijf"
- **Lokaal verbonden** — verwijs naar venues (Studio Dependance, Club Poema, etc.)
- **Cijfers gebruiken** — "400+ optredens per jaar", "5.0★", "23 verified reviews"
- **Brand-claim consequent**: "De meest geboekte live pianoshow van Nederland"
- **Klantlogo's**: Heineken, Rabobank, Booking.com — gebruik prominent op bedrijfsfeest-band en silo-hubs

## 7. Volgorde van uitvoeren (aanbevolen)

### Sprint 1 (week 1-2) — De 10 quick wins
Begin met deze 10 pagina's (hoogste volume × laagste KD):
1. `/pianoshow` (KD 6)
2. `/breda/bedrijfsuitje` (KD 6)
3. `/bedrijfsfeest-band` (KD 9)
4. `/eindhoven/date-activiteiten` (KD 10)
5. `/utrecht/bedrijfsuitje` (KD 12)
6. `/coverband/coverband-bruiloft` (KD 12)
7. `/breda/vrijgezellenfeest` (KD 11)
8. `/rotterdam/vrijgezellenfeest` (KD 12)
9. `/utrecht/vrijgezellenfeest` (KD 11)
10. `/renesse/wat-te-doen` (KD 16)

### Sprint 2 (week 3-4) — Alle hubs
Alle 5 stad-hubs + 5 silo-hubs (10 pagina's). Verplicht voor het sitewide
hub-and-spoke linkmodel.

### Sprint 3-4 (week 5-8) — Resterende P0 (13 pagina's) + P1

### Sprint 5+ (week 9+) — P2-pagina's en sub-subs

## 8. Veelgestelde vragen

**V: Mag ik afwijken van de briefing?**
A: De briefing is een richtlijn, niet een keurslijf. Hoofd-KW, title-tag,
URL en interne links zijn **vast**. Inhoud mag je verbeteren — maak het altijd
**beter** dan de concurrentie (zie `03-concurrenten/`).

**V: Wat als ik geen volume zie voor een variant?**
A: Kies een gerelateerde long-tail uit het KWO-bestand voor die stad/silo.
Indien niets passend, schrap de pagina en update `01-sitemap-v2.csv`.

**V: Wat als een concurrent veel beter rankt?**
A: Bestudeer hun H-structuur en woordaantal. Doe **alles** wat zij doen plus
één gap uit `03-concurrenten/[silo].md` ("content-gaps om te exploiteren").

**V: Hoe meet ik succes per pagina?**
A: Eens per maand check je in SEMrush of Google Search Console:
- Position voor hoofd-KW
- Impressies + clicks
- Bounce rate < 60% (anders content verbeteren)

## 9. Tools & afhankelijkheden

| Tool | Waarvoor | Toegang |
| --- | --- | --- |
| **SEMrush** | KWO-validatie + ranking-monitoring | Bestaande account |
| **Google Search Console** | Performance per URL | Property dejongensvanjeweetwel.nl |
| **Google Analytics 4** | Verkeer per pagina | Property koppelen |
| **Schema Markup Validator** | schema.org valid? | https://validator.schema.org/ |
| **PageSpeed Insights** | Lighthouse-check | https://pagespeed.web.dev/ |

## 10. Project-status

Zie `01-sitemap-v2.csv` kolom `status` voor live-overzicht.
Update na elke afgeleverde pagina.

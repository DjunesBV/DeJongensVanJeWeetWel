# Concurrentieanalyse — Overzicht alle 5 silo's

Korte samenvatting van bevindingen + rode draad. Detail per silo in losse
bestanden + master-CSV.

## Bestanden

- `pianoshow.md` — Silo Pianoshow (KD 6 quick win)
- `pianobar.md` — Silo Pianobar (venue-zoekopdracht)
- `coverband.md` — Silo Coverband (880/mnd, platform-dominantie)
- `bruiloftband.md` — Silo Bruiloftband (cluster 2.000/mnd + PAA-vragen)
- `bedrijfsfeest-band.md` — Silo Bedrijfsfeest-band (KD 3-9, corporate social proof)
- `concurrenten-master.csv` — alle concurrenten in één tabel

## Rode draad over alle silo's

### 1. Platforms en bureaus domineren — bands ontbreken

In 4 van de 5 silo's (Pianoshow, Coverband, Bruiloftband, Bedrijfsfeest-band) is
de top 10 voor 70-100% boekingsplatforms en artiestenbureaus. Slechts 1-2
directe bands ranken per silo.

**Strategische implicatie:** een goed geoptimaliseerde band-eigen pagina kan
concurreren omdat:
- Aggregators hebben dunne, gestandaardiseerde individuele-artiest-pagina's
- Wij hebben unieke content (eigen video, reviews, branding, prijs-transparantie)
- "Direct bij de band boeken, geen tussenpersoon" is een onderscheidende hoek

**Uitzondering:** Pianobar — daar zijn het fysieke venues (Crazy Pianos, Maxim,
The Piano Bar). Onze hoek daar = "pianobar op locatie" + "grootste pianobar
van NL"-claim.

### 2. Wat platforms goed doen — en wat wij overnemen

| Wat zij doen | Wij doen het beter |
| --- | --- |
| Veel reviews aggregeren | Onze 5.0★ + 23 reviews met namen prominent |
| Top 10-lijstjes (ShowBird) | Eigen blog-content "top 10 trouwliedjes" etc. |
| Prijs-indicatie bovenaan | Vanaf-prijzen uit `/bezettingen` overnemen |
| Veel concurrenten in één tabel | Wij vergelijken bezettingen onderling |

### 3. Wat alle concurrenten missen

| Gap | Hoe wij dit exploiteren | Geldt voor silo's |
| --- | --- | --- |
| Geen lokale spreiding | 5 stad-hubs als interne link-cluster | Alle 5 |
| Geen "meest geboekte"-claim | "De meest geboekte live pianoshow van NL" | Pianoshow + Coverband |
| Geen corporate referenties | Heineken/Rabobank/Booking.com logo's | Bedrijfsfeest-band |
| Geen FAQ met schema markup | FAQPage-schema overal | Alle 5 |
| Geen video bovenaan | Bestaande `/video` content inzetten | Alle 5 |
| Geen prijs-transparantie (m.u.v. Groove Piano) | Vanaf-prijzen tonen | Alle 5 |
| Geen "direct boeken, geen marge" | USP voor B2C en B2B | Coverband + Bruiloftband + Bedrijfsfeest-band |

### 4. People Also Ask is direct content

Voor `band voor bruiloft` heeft Google 4 PAA-vragen:
- Wat kost een band voor een bruiloft?
- Wat zijn de beste bands voor een bruiloft?
- Wat zijn de top 10 trouwliedjes?
- Waar kan ik een band boeken voor mijn bruiloft?

**Direct verwerken in `/bruiloftband` FAQ-blok** voor kans op rich snippet.
Voor andere silo's: PAA's checken bij content-schrijven.

### 5. Welke directe band-concurrenten te benchmarken

| Silo | Directe band-concurrent | Wat overnemen |
| --- | --- | --- |
| Pianoshow | Groove Piano (groovepiano.nl) | prijzen + reviews + agenda structuur |
| Pianoshow | Mike's Pianoshow (mikespianoshow.com) | warme branding-tekst |
| Coverband | Band Escape (band-escape.nl) #11 — net buiten top 10 | hun structuur snel checken bij briefing |
| Bruiloftband | Benga Band (bengaband.com) — Google Ads | hun unique selling points |
| Bedrijfsfeest-band | YourBand — #9 directe band | hun zwakke positionering ("you decide, we play") laat ruimte |

## Standaard SEO-fundamenten voor alle 5 silo-pagina's

Elk silo-briefing krijgt deze elementen:

- **Title-tag** ≤ 60 chars met hoofd-KW + brand
- **H1** met hoofd-KW + USP
- **Meta description** ≤ 155 chars met CTA
- **8-10 H2 secties** (zie individuele briefings)
- **Woordaantal** 1.500-2.500 (afhankelijk van concurrentie)
- **Schema**: Organization (sitewide) + LocalBusiness + FAQPage + AggregateRating
- **Internal links naar:**
  - `/bezettingen` (eindbestemming offerte)
  - `/boeken` / `/offerte` (CTA)
  - 5 stad-hubs (geografische autoriteit)
  - Andere silo's (thematische autoriteit)
- **Externe signaal**: klantlogo's (Heineken, Rabobank, Booking.com)
- **Reviews**: 5.0★ × 23 — overal prominent
- **Video**: bestaande `/video` content embedden

## Volgende stap

Op basis van deze concurrentieanalyse worden de content-briefings per
P0-pagina geschreven in `04-briefings/`.

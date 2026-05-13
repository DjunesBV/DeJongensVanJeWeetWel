# Content-briefing templates — 4 pagina-types

Gebruik per pagina de template die past op het type. Vervang `[…]` velden.

## Page-type 1 — STAD-HUB (`/breda`, `/utrecht`, …)

```
URL: /[stad]
Hoofd-KW: uitgaan [stad] (of "uitgaan in [stad]")
Secundaire KW: [stad] uitgaan / uitgaan in [stad] / uitgaan [stad] vandaag
Intent: Commercial / informational
Doel: 1) Bezoekers → sub-pagina's | 2) Branding "De Jongens spelen wekelijks in [stad]"

TITLE-TAG (max 60): Uitgaan in [stad] — alle hotspots & agenda | De Jongens
META-DESC (max 155): Op zoek naar uitgaan in [stad]? Ontdek de leukste pianobars, restaurants met live muziek en hotspots — plus waar de Jongens deze week spelen.
H1: Uitgaan in [stad] — alle hotspots, agenda en live muziek

WOORDAANTAL: 1.200-1.500

STRUCTUUR (H2):
1. Wat is er deze week te doen in [stad]? — agenda-blok (auto-updaten met events)
2. De [N] beste plekken om uit te gaan in [stad] (links naar sub-pagina's)
3. Eten, drinken & live muziek in [stad] (link naar sub-pagina's restaurant/cafe/live muziek)
4. Bedrijfsuitjes en feestlocaties in [stad] (link naar /bedrijfsuitje, /feestlocatie, /trouwlocatie)
5. De Jongens Van Je Weet Wel wekelijks live in [stad] (venue + link naar /boeken)
6. Veelgestelde vragen over uitgaan in [stad]

MUST-HAVES:
- Agenda-blok bovenaan ("vandaag/dit weekend"-intent, 1.300-3.600/mnd!)
- Lijst van sub-pagina's als grid (card-style)
- CTA "Boek De Jongens voor je feest in [stad]" → /boeken
- 5.0★ reviews-block
- Foto's van de stad-venue (Studio Dependance / Club Poema / etc.)
- Map embed met de venue

SCHEMA: LocalBusiness + Place + Event (agenda) + FAQPage

INTERNE LINKS:
IN: vanaf /, /locaties, alle stad-sub-pagina's van [stad], alle silo's (footer)
UIT: alle 13-15 [stad]/sub-pagina's, /bezettingen, /boeken, /pianoshow, /pianobar
```

---

## Page-type 2 — STAD-SUB (`/breda/bedrijfsuitje`, `/utrecht/wat-te-doen`, …)

```
URL: /[stad]/[onderwerp]
Hoofd-KW: [zie sitemap-v2.csv per pagina]
Doel: rank op lokale long-tail + funnel naar boeking

TITLE-TAG (max 60): [Hoofd-KW kapitalized] | De Jongens Van Je Weet Wel
META-DESC (max 155): [Antwoord op zoekintentie in 1 zin] + USP + CTA.
H1: [Hoofd-KW] — [USP-zinnetje]

WOORDAANTAL:
- Bij hoog volume (>500/mnd): 1.500-2.000
- Bij midden (100-500): 1.000-1.500
- Bij laag (<100): 600-900

STRUCTUUR (H2) — varieert per onderwerp, standaard 5-7 secties:
1. Intro met hoofd-KW + USP
2. [Onderwerp-specifieke H2 — bv. "De 10 beste pianobars in [stad]"]
3. [Onderwerp-specifieke H2]
4. Waarom kiezen voor De Jongens? (brand-injectie)
5. Wij komen ook bij jouw [onderwerp] (CTA naar boeking, indien commercieel/transactional)
6. FAQ over [onderwerp] in [stad]

MUST-HAVES:
- Hoofd-KW in title, H1, eerste 100 woorden, meta-desc, en 2-3x in body
- 1× link naar stad-hub /[stad]
- 1× link naar relevante silo (vb. /bedrijfsuitje → /bedrijfsfeest-band)
- 1× link naar /boeken
- 1 foto + 1 video (eigen content)
- FAQ-blok onderaan (Schema)

SCHEMA: LocalBusiness + FAQPage (+ Event als agenda relevant)

INTERNE LINKS:
IN: stad-hub /[stad] + andere relevante /[stad]/sub-pagina's
UIT: stad-hub /[stad] + relevante silo + /boeken / /bezettingen
```

---

## Page-type 3 — SILO-HUB (`/pianoshow`, `/coverband`, …)

```
URL: /[silo]
Hoofd-KW: [zie sitemap-v2.csv]
Doel: thematische autoriteit + B2C/B2B funnel

TITLE-TAG (max 60): [Hoofd-KW] | De meest geboekte [silo] van Nederland
META-DESC (max 155): [Hoofd-KW] direct bij de band — vanaf €[X]. 400+ optredens, 5.0★ rating. Check je datum.
H1: [Hoofd-KW] — [USP-zinnetje]

WOORDAANTAL: 1.800-2.500 (silo-hubs zijn de zwaargewichten)

STRUCTUUR (H2) — 8-10 secties:
1. Intro: wat is een [silo] van De Jongens?
2. Waarom direct bij de band? (vs platforms/bureaus — concurrentie-hoek)
3. Onze bezettingen voor [silo] (link /bezettingen)
4. Repertoire — wat spelen we (verzoekje-systeem)
5. Wat kost een [silo]? (vanaf-prijs + factoren)
6. Wekelijks live in 5 steden (links naar 5 stad-hubs)
7. Klanten / cases (Heineken/Rabobank/Booking.com)
8. Reviews — 5.0★, 23 geverifieerde
9. Veelgestelde vragen (FAQPage met 6 vragen, incl. PAA)
10. Boek de [silo] van De Jongens (CTA → /boeken)

MUST-HAVES:
- Hero met video boven de fold
- Vanaf-prijs prominent (Mike's en bureaus tonen geen prijs — wij wel)
- Klant-logo's (corporate social proof)
- Reviews-grid met namen
- FAQ-schema met 6 vragen
- 3-5 interne links naar relevante silo's

SCHEMA: Organization + Product/Service + AggregateRating + FAQPage + Offer

INTERNE LINKS:
IN: footer (sitewide), /, /bezettingen, gerelateerde stad-sub-pagina's
UIT: /bezettingen, /boeken, 5 stad-hubs, andere silo's, eigen silo-subs
```

---

## Page-type 4 — SILO-SUB (`/coverband/coverband-bruiloft`, `/pianoshow/wat-kost-een-pianoshow`, …)

```
URL: /[silo]/[sub]
Hoofd-KW: [zie sitemap-v2.csv]
Doel: long-tail intent (vergelijking, prijs, sub-niche)

TITLE-TAG (max 60): [Hoofd-KW] | De Jongens
META-DESC (max 155): [Antwoord op intent in 1 zin] + CTA.
H1: [Hoofd-KW]

WOORDAANTAL: 800-1.200

STRUCTUUR (H2) — 4-6 secties:
1. Direct antwoord op intent (eerste 100 woorden = het antwoord)
2. Detail / uitwerking
3. Voorbeelden / specifieke gevallen
4. Hoe past dit bij De Jongens?
5. Boek nu (CTA)
6. FAQ

MUST-HAVES:
- Direct antwoord boven de fold ("[silo] kost vanaf €X, afhankelijk van Y en Z")
- 1× breadcrumb met link naar silo-hub
- 1× link naar /boeken
- 1 visualisatie of foto

SCHEMA: BreadcrumbList + FAQPage (afhankelijk van intent)

INTERNE LINKS:
IN: silo-hub /[silo] + relevante stad-sub-pagina's
UIT: silo-hub /[silo] + /boeken + /bezettingen
```

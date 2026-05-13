# Briefing — Breda stad-hub + sub-pagina's

Eén document met de **stad-hub** + korte briefings voor de **14 sub-pagina's**.
Alle KW-data uit `02-keyword-research/steden/breda-kwo.csv`.

---

## HUB: `/breda`

**Hoofd-KW:** uitgaan breda (880, KD 17) | **Cluster:** ~1.700/mnd | **Prio:** P0

- **Title-tag (60):** Uitgaan in Breda — alle hotspots & agenda | De Jongens
- **Meta-desc (153):** Op zoek naar uitgaan in Breda? Ontdek de leukste pianobars, restaurants met live muziek en hotspots — plus waar de Jongens deze week spelen.
- **H1:** Uitgaan in Breda — alle hotspots, agenda en live muziek

**Woordaantal: 1.300**

### Structuur (H2)

1. **Wat is er deze week te doen in Breda?** — agenda-blok (event-list)
2. **De leukste plekken om uit te gaan in Breda** — grid met 5-7 sub-pagina kaarten
3. **Eten, drinken & live muziek** — link naar `/breda/live-muziek` + Studio Dependance highlight
4. **Bedrijfsuitje, vrijgezellenfeest of trouwlocatie zoeken?** — links naar `/breda/bedrijfsuitje`, `/breda/vrijgezellenfeest`, `/breda/trouwlocatie`, `/breda/feestlocatie`
5. **De Jongens Van Je Weet Wel — wekelijks live in Studio Dependance** — venue-blok + Google map embed + linkboek
6. **Veelgestelde vragen over uitgaan in Breda**
   1. Waar kan ik leuk uitgaan in Breda?
   2. Wat is er vandaag te doen in Breda?
   3. Waar speelt De Jongens Van Je Weet Wel in Breda?
   4. Welke leeftijd voor uitgaan in Breda? (30+, 16-jaar long-tails)

### Schema
`LocalBusiness` + `Place` (Studio Dependance) + `Event` (agenda) + `FAQPage`

### Interne links UIT
Alle 13 sub-pagina's van `/breda`, plus `/pianoshow`, `/bezettingen`, `/boeken`, `/locaties`.

### Interne links IN
Footer sitewide, `/locaties`, alle 13 sub-pagina's, alle silo's onder "wij spelen wekelijks in Breda".

---

## SUB-PAGINA'S BREDA (samenvattingen)

### `/breda/wat-te-doen` ⭐ TOPPER

- **KW:** wat te doen in breda (**2.400**, KD 25) — hoogste van Breda
- **Cluster:** 6.500/mnd ("dit weekend" 1.300, "vandaag" 390, "centrum" 260, "met vriendinnen" 90 KD 10)
- **Woordaantal:** 1.800
- **Title:** Wat te doen in Breda? Top 25 ideeën voor elk moment
- **H1:** Wat te doen in Breda — van agenda tot verborgen tips
- **Structuur:**
  1. Top 5 hotspots vandaag/dit weekend (agenda-blok)
  2. Wat te doen in Breda: 10 ideeën
  3. Wat te doen met vriendinnen / kinderen (PAA-varianten)
  4. Wat te doen in Breda centrum
  5. De Jongens in Studio Dependance — live optreden vanavond?
  6. FAQ
- **Interne links uit:** `/breda` hub, `/breda/uitjes`, `/breda/date-activiteiten`, `/breda/live-muziek`, `/bezettingen`
- **Schema:** ItemList (top 10) + FAQPage

### `/breda/uitjes` ⭐

- **KW:** uitjes breda (880, KD 28) | **Cluster:** 3.300/mnd
- **Sub-cluster:** team uitje (70, KD 6) + zakelijk uitje (30)
- **Woordaantal:** 1.500
- **Hoek:** Mix recreatie + zakelijk (team uitje sub-blok)
- **Structuur:** intro → 10 uitjes → team uitje sub-blok → 2 personen / kinderen varianten → CTA → FAQ
- **Interne links:** `/breda/bedrijfsuitje` (zakelijke variant), `/breda/wat-te-doen`, `/breda` hub

### `/breda/bedrijfsuitje` ⭐⭐ QUICK WIN

- **KW:** bedrijfsuitje breda (320, **KD 6**!)
- **Woordaantal:** 1.200
- **Title:** Bedrijfsuitje in Breda — origineel, actief, georganiseerd
- **Structuur:** intro → 10 ideeën → onze pianoshow als bedrijfsuitje (link `/bedrijfsfeest-band`) → cases → FAQ → CTA
- **Schema:** LocalBusiness + FAQPage
- **Interne links:** `/bedrijfsfeest-band` silo, `/breda` hub, `/breda/uitjes`, `/breda/evenementenlocatie`, `/boeken`

### `/breda/vrijgezellenfeest` ⭐ QUICK WIN

- **KW:** vrijgezellenfeest breda (390, **KD 11**) | **Cluster:** 1.500/mnd
- **Sub-cluster:** vrouwen 270 (KD 4-6), mannen 140 (KD 3-5)
- **Woordaantal:** 1.500
- **Structuur:** intro → ideeën → vrouwen sectie → mannen sectie → pakketten waaronder pianoshow → boeken
- **Interne links:** `/breda` hub, `/breda/wat-te-doen`, `/coverband`, `/pianoshow`, `/boeken`
- **Mogelijke sub-sub:** `/breda/vrijgezellenfeest/vrouwen` en `/.../mannen` (later — KD <6)

### `/breda/trouwlocatie`
- **KW:** trouwlocatie breda (320, KD 21) | **Cluster:** 600
- **Woordaantal:** 1.200
- **Hoek:** mooie locaties + band als entertainment-toevoeging
- **Interne links:** `/bruiloftband` silo, `/breda` hub

### `/breda/feestlocatie`
- **KW:** feestlocatie breda (210, KD 15) | KW "kleine feestlocatie breda" KD 9
- **Woordaantal:** 1.100
- **Interne links:** `/bedrijfsfeest-band`, `/breda` hub, `/breda/evenementenlocatie`

### `/breda/live-muziek`
- **KW:** live muziek breda (110, KD 14) — "vandaag" variant 320
- **Woordaantal:** 1.200
- **Hoek:** agenda-pagina met De Jongens prominent
- **Sub-content opnemen:** cafe + restaurant met live muziek (te laag voor eigen pagina's)
- **Schema:** Event-list + Place
- **Interne links:** `/breda` hub, `/pianoshow`, `/pianobar`

### `/breda/bezienswaardigheden`
- **KW:** bezienswaardigheden breda (880, KD 26)
- **Woordaantal:** 1.500
- **Toon:** toeristisch/informational
- **CTA-light:** "Na de Grote Markt? Eindig je dag bij De Jongens in Studio Dependance"

### `/breda/kroegen`
- **KW:** kroegen breda (390, KD 19) — meervoud heeft lagere KD dan "breda kroeg" (KD 63)
- **Woordaantal:** 1.000
- **Hoek:** top-10 lijst + Studio Dependance featured

### `/breda/date-activiteiten`
- **KW:** date breda (140, KD 12) — KD 4 op "daten in breda"
- **Woordaantal:** 900
- **Toon:** romantisch
- **Hoek:** "10 dates voor in Breda — eindig de avond bij De Jongens"

### `/breda/evenementenlocatie`
- **KW:** evenementenlocatie breda (210, KD 34) — B2B
- **Woordaantal:** 1.000
- **Interne links:** `/bedrijfsfeest-band`, `/breda/bedrijfsuitje`

### `/breda/stappen`
- **KW:** stappen breda (140, KD 15)
- **Woordaantal:** 800
- **Toon:** jong publiek, kroegen-uittocht

### `/breda/avondje-uit`
- **KW:** avondje uit breda (110, KD 11)
- **Woordaantal:** 800
- **Hoek:** "Plan je avondje uit in Breda" — combineer eten + uitgaan + muziek

---

## GEZAMENLIJKE STANDAARDEN (geldig voor alle 14)

- Brand-toon: warm, energiek, lokaal verbonden
- ALT-tags op alle foto's met "[onderwerp] in Breda"
- Iedere pagina ≥ 1 foto + ≥ 1 video
- Footer-CTA: "Boek De Jongens voor jouw feest" → `/boeken`
- Sticky telefoon-CTA op mobile

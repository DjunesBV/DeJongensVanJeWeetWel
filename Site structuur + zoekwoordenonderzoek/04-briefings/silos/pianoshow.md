# Briefing — `/pianoshow`

**Type:** silo-hub | **Prio:** P0 (snelste win van de site) | **Concurrentie:** [03-concurrenten/pianoshow.md](../../03-concurrenten/pianoshow.md)

## Keyword-targets

| Type | Keyword | Volume | KD |
| --- | --- | --- | --- |
| Hoofd | pianoshow boeken | 110 | **6** |
| Secundair | pianoshow | 110 | 15 |
| Secundair | de pianoshow | 30 | - |

## Title & meta

- **Title-tag (58):** Pianoshow boeken | De meest geboekte van Nederland — De Jongens
- **Meta-desc (152):** Boek dé pianoshow van Nederland. 400+ optredens per jaar, 5.0★ rating, alles-in-één. Vanaf €3.495. Check je datum direct.
- **H1:** Pianoshow boeken — de meest geboekte live pianoshow van Nederland

## Woordaantal: 1.800-2.000

## Structuur

### H2: 1. Wat is een pianoshow van De Jongens Van Je Weet Wel?
- Korte introductie (150 woorden): live pianoshow met verzoeknummers, interactie, alles-in-één
- "Onze gasten bepalen wat we spelen" — kernpositie
- Embedded video bovenaan

### H2: 2. Waarom kiezen voor de meest geboekte pianoshow van Nederland?
- USP's in 4 punten met icoontjes:
  - 400+ optredens per jaar
  - 5.0★ rating, 23+ verified reviews
  - Alles-in-één (muziek + techniek + licht + geluid)
  - 100% op verzoek
- Geen tussenpersoon (concurrentie-hoek)

### H2: 3. Onze drie bezettingen
- Kleine Jongens (€3.495+) — piano + drums
- De Jongens Van Je Weet Wel (€3.995+) — piano + drums + gitaar (meest geboekt)
- Grote Jongens (€4.495+) — piano + drums + gitaar + brass
- → link naar `/bezettingen`

### H2: 4. Wat kost een pianoshow?
- Vanaf €3.495 (alles-in-één)
- Wat zit erin: muziek + techniek + licht + geluid + technicus
- Factoren: locatie, datum, duur
- → CTA "Vraag een offerte aan" → `/offerte`

### H2: 5. Wekelijks live in 5 steden
- Breda · Utrecht · Eindhoven · Rotterdam · Renesse
- Mini-grid met foto + venue-naam per stad
- Elke kaart linkt naar `/[stad]` (stad-hub)

### H2: 6. Klanten die voor ons kozen
- Logo-grid: Heineken · Rabobank · Booking.com · etc. (uit huidige homepage)

### H2: 7. Wat klanten zeggen
- 4-6 testimonials uit bestaande reviews met namen
- Schema: AggregateRating 5.0/5 (23 reviews)

### H2: 8. Veelgestelde vragen
**FAQ-schema (FAQPage):**
1. Wat kost een pianoshow van De Jongens?
2. Hoe lang spelen jullie?
3. Hebben jullie eigen techniek (geluid/licht)?
4. Spelen jullie verzoeknummers?
5. Tot hoeveel personen kunnen jullie spelen?
6. Hoe lang van tevoren moet ik boeken?

### H2: 9. Pianoshow boeken — check je datum
- Grote CTA-knop → `/boeken`
- Alternatief: WhatsApp + telefoonnummer

## Must-haves

- ✅ Video bovenaan (uit `/video`)
- ✅ Vanaf-prijs in eerste 100 woorden
- ✅ Klantlogo's
- ✅ Reviews met namen
- ✅ FAQ-schema
- ✅ 5 stad-links

## Schema markup

```json
{
  "@context": "https://schema.org",
  "@type": "Service",
  "name": "Pianoshow boeken — De Jongens Van Je Weet Wel",
  "provider": { "@type": "Organization", "name": "De Jongens Van Je Weet Wel" },
  "areaServed": ["Breda","Utrecht","Eindhoven","Rotterdam","Renesse"],
  "offers": { "@type": "Offer", "price": "3495", "priceCurrency": "EUR" },
  "aggregateRating": { "@type": "AggregateRating", "ratingValue": "5.0", "reviewCount": "23" }
}
```
Plus `FAQPage` schema voor de FAQ-sectie.

## Interne links

| Richting | Aantal | Doel |
| --- | --- | --- |
| **Uit** | 1× `/bezettingen` | bezettingen-detail |
| **Uit** | 1× `/offerte` of `/boeken` | CTA |
| **Uit** | 5× `/[stad]` hubs | geografische autoriteit |
| **Uit** | 1× `/pianobar` | thematische cluster |
| **Uit** | 1× `/coverband` | thematische cluster |
| **In** | sitewide footer | autoriteit bouwen |
| **In** | vanuit 5 stad-hubs ("De Jongens spelen wekelijks in [stad]") | geografisch bewijs |

## Concurrentie-overweging

- **Mike's Pianoshow** mist prijzen en reviews — onze prijs + reviews bovenaan is direct onderscheid
- **Groove Piano** is sterkste — heeft wel prijzen (€825/€1.625) + reviews. Wij positioneren hoger ("meest geboekte" + €3.495+ = premium-positie)
- **7/10 SERP is bureau/platform** — onze hoek "direct bij de band, geen marge" werkt

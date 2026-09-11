# Examen 1 Grupparbete - Grupp 10
## Gruppen
Ihab Abdul Satar Hussein,
Johan Svensson,
Louie Al-Saffar

## Examination 1 (Eventsidan)
1. Hero — namn, bild/logotyp, datum, plats, kort beskrivning
2. Schema — CSS Grid (se 06-css-grid)
3. Highlights — Flexbox
4. Nav + footer — ankare till sektioner; sidfot med kontakt + fiktiva sponsorer
5. Responsivitet — @media; testa viewport så layouten inte går sönder

## Teori & Reflektion

### 1. Vad innebär semantisk HTML och varför har ni använt det på er eventsida?

Semantisk HTML innebär att man använder HTML-element som beskriver innehållets funktion, till exempel `<header>`, `<nav>`, `<main>`, `<section>` och `<footer>`. Det gör sidan mer strukturerad, lättare att förstå för både webbläsare och skärmläsare, och förbättrar tillgänglighet och SEO.

På vår eventsida har vi använt semantisk HTML för att skapa en tydlig och logisk struktur, göra sidan mer tillgänglig för personer med funktionsnedsättning, hjälpa sökmotorer att tolka innehållet korrekt och göra koden enklare att underhålla och bygga vidare på. Konkret använder vi `<header>` för hero, `<nav>` för menyn, `<main>` för huvudinnehållet, `<section>` för schema och höjdpunkter, `<article>` för varje aktivitetskort och `<footer>` för kontakt och sponsorer.

### 2. Hur fungerar arv i CSS? Ge ett exempel från er egen kod.

Arv i CSS innebär att vissa egenskaper automatiskt förs vidare från ett föräldraelement till dess barn. Det gäller främst textegenskaper som `font-family`, `color` och `line-height`.

På vår eventsida sätter vi `font-family` på `body`. Alla element som inte anger egen font, till exempel rubrikerna `h1`, `h2` och `h3`, ärver den automatiskt. Det gör koden renare, kortare och enklare att underhålla.

### 3. Vad är den största skillnaden mellan Flexbox och CSS Grid, och när ska man använda vilket verktyg? Motivera utifrån hur ni fördelade dem på er sida.

Flexbox är layout i en riktning (rad eller kolumn) — bra för menyer, knapprader, kortrader och centrering. CSS Grid är layout i två riktningar (rader och kolumner) — bra för tabeller, dashboards och sidstrukturer.

På vår eventsida använde vi Flexbox på höjdpunkterna (`.kort-rad`) eftersom korten är likadana bitar i en rad som kan wrappa. Schemat layoutade vi med CSS Grid (`.schedule-item`) eftersom raderna dessutom har kolumner för titel, tid och plats.

## GitHub & inlämning
- Gemensamt repo med synliga commits från alla i gruppen.
- Inlämning fredag 11 september: länk till repot i Moodle.
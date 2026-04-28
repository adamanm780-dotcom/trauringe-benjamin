# Inspo — Trauringe Benjamin (Branche: Juwelier / Trauringe)

## Übergeordnete Richtung
Editorial Luxury mit warmem, einladendem Touch — kein eisiger Hochpreis-Look, sondern Familienatelier. Trauringe leben von Emotion → Hero mit weichem cinematic Licht, viel Raum, ein Trauringpaar als zentrales Motiv, Champagner-/Roségold-Akzente. Section-Treatments lehnen sich an Magazinlayouts an: Serifen-Headlines mit großzügigen Whitespaces, asymmetrische Bento-Grids für Kollektionen und ein "atelier"-Block mit dem Hands-At-Work-Storytelling.

## Referenzen

### 1. Style by K — Wedding Jewelry Editorial
- URL: https://dribbble.com/search/wedding-rings-website (Treffer „Style by K Studio")
- Stil: dark editorial · warm gold · cinematic close-up
- Übernehmen:
  - Dunkler Hero mit großem Produkt-Close-up + überlagernder Serif-Wordmark
  - Goldfarbene Hairlines unter Section-Headlines („gold-line" Element)
- Screenshot: inspo/grid.jpeg

### 2. Penn Lab — Luxury Jewelry Brand
- URL: https://dribbble.com/search/wedding-rings-website (Treffer „Penn Lab — Pearl & Craft")
- Stil: cream editorial · serif display · grid with portraits
- Übernehmen:
  - Beige/cream-Sektion zwischen dunklen Blöcken als "Atelier"-Break (visueller Atemzug)
  - Italiana-ähnliche Display-Schrift für die ganz großen Statements
- Screenshot: inspo/grid.jpeg

### 3. Bailey S — Wedding Editorial
- URL: https://dribbble.com/search/wedding-rings-website (Treffer „Bailey Sullivan")
- Stil: editorial · two-column · serif + handwritten accent
- Übernehmen:
  - Asymmetrischer Hero: Bild rechts, große Headline links mit Inset-Border
  - Section-Übergänge mit kleinen Roman-Numerals als Kapitel-Marker
- Screenshot: inspo/grid.jpeg

### 4. Editorial Beauty Site Grid
- URL: https://dribbble.com/search/wedding-rings-website (Treffer Reihe 2, Bild 3)
- Stil: pastel-warm · soft light · circular product shots
- Übernehmen:
  - Detail-Grid für Kollektionen mit weichen Schatten + viel Padding
  - Roundings auf Imagery (16-24px) statt harter Kanten
- Screenshot: inspo/grid.jpeg

### 5. Marquee + Tag-Strip Pattern
- URL: https://dribbble.com/search/wedding-rings-website (mehrere Treffer)
- Stil: editorial typography strip
- Übernehmen:
  - Horizontaler Marquee zwischen Sections mit Material-Tags (750er Gold · Roségold · Platin · Diamantbesatz)
  - Slow-scroll Animation, dezent — nicht aggressiv
- Screenshot: inspo/grid.jpeg

### 6. Atelier Hands Story (Goldsmith Workshop)
- URL: ergänzend aus „luxury-jewelry-website" Suche (selbe Domain)
- Stil: hands-at-work · dark workshop · warm tungsten light
- Übernehmen:
  - Atelier-Section mit Image-Text-Split, Bild leicht aus dem Container heraus (overflow)
  - Sticky Caption ("Seit 2008 · Familie Benjamin") beim Scrollen
- Screenshot: inspo/grid.jpeg

## Konkrete Anpassungen für Phase 6

- **Font-Pair**: `Cormorant Garamond` (Serif Headlines) + `Italiana` (Display Statements) + `Inter` (Body / Mikro-Text). Begründung: Cormorant ist warm und ringnah, Italiana liefert das ehrwürdige "Atelier seit 2008"-Statement-Feeling, Inter hält Microcopy ruhig.
- **Hero-Treatment**: Full-bleed Trauring-Paar-Closeup auf dunklem Marmor, inset Gold-Hairline-Frame (1px rgba(accent,.28), inset:18px), zarte Ken-Burns Animation. Overlay-Bar unten mit Material-Tags links + CTA „Beratung anfragen" rechts.
- **Section-Flourishes**:
  - Marquee zwischen Hero und Intro mit Material-Tags
  - Bento-Grid für „Kollektionen" (Klassik · Roségold · Diamant · Memoire — 4 Karten unterschiedlicher Höhen)
  - Atelier-Section mit Diagonal-Split Image-Text + sticky Mini-Caption
  - Roman-Numerals (I · II · III · IV) als Featured-Trauring-Kapitel-Marker
- **Mikro-Interaktionen-Highlights**:
  - Underline-Reveal Nav (Pflicht)
  - Hover-Scale auf Gallery-Bildern (Pflicht)
  - Magnetic-Button auf Haupt-CTA „Termin vereinbaren" (sanft, max 6px Versatz)
  - Cursor-Spotlight (subtiles 200px Radial-Glow) im Hero, nur Desktop
  - Fade-in-on-scroll via IntersectionObserver
- **Farb-Mood-Hinweis**: Hauptpalette warm und cinematic — Champagner-Gold + Roségold-Akzent. Hintergrund tief-anthrazit (kein reines Schwarz, eher #14110E). Helle Sektionen in cream/ivory für den editorial Atemzug.

> Limited inspo: Dribbble-Cookie-Banner blockierte einzelne Shot-Pages. Synthese basiert auf Grid-Übersicht (siehe `inspo/grid.jpeg`) + Branchen-Konventionen aus früheren !build-Projekten (Juwelier Weidmann → vergleichbare Produkt-Welt).

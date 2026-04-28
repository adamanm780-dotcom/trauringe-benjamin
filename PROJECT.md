# Trauringe Benjamin

**Slug:** trauringe-benjamin
**Branche:** Juwelier (Trauringe / Goldschmiede)
**Build-Datum:** 2026-04-28
**Live-URL:** https://adamanm780-dotcom.github.io/trauringe-benjamin/
**Repo:** https://github.com/adamanm780-dotcom/trauringe-benjamin
**Lokal:** C:/Users/Adria/claude-discord-projects/allgemein/trauringe-benjamin

## Kontakt
- Adresse: Lotharstr. 15, 55116 Mainz
- Telefon: 06131 / 143 82 33
- E-Mail: info@juwelier-benjamin.eu
- Öffnungszeiten: Mo–Fr 10–18 · Sa 10–16 · So geschlossen
- Website (Original): trauringe-benjamin.de · juwelier-benjamin.eu
- Instagram: @juwelierbenjamin (Wiesbaden-Hauptaccount, Familie Benjamin)
- Familie: Aydin, Binno, Daniyel Benjamin (2. Generation, gegründet 2008 von Martin Benjamin)

## Design
- Palette: #0F0B07 #14110E #1F1A14 #C49A5F #D9B581 #F4ECDC #7A6E5D
- Fonts: Cormorant Garamond + Italiana + Inter
- Style-Richtung: Editorial Luxury · warm cinematic · Champagner-Gold + Roségold-Akzente · Familienatelier (kein kalter Hochpreis-Look)

## Assets
- Hero: assets/hero.webp (Nano Banana 21:9 → Real-ESRGAN 4K, Trauringpaar Roségold/Platin auf Carrara-Marmor)
- Maps-Fotos: n/a (Maps-Panel im 720p-Mode zu klein für sauberes Cropping; visuelle Welt komplett aus Nano Banana)
- Insta-Posts: n/a (skip — Konsistenz besser mit generierter Bildwelt)
- Zusatz-Assets: assets/about.webp (Goldschmied-Hände mit Pinzette+Diamant), assets/detail-01.webp (Roségold Memoire auf Cream-Seide), assets/detail-02.webp (Trauringpaar dunkler Marmor), assets/texture.webp (warmer Marmor-Overlay)
- Scroll-Frames: 50 × WebP (assets/scroll/frames-clean/, ~1.5MB total), Source-Video assets/scroll/source.mp4 (Seedance 2.0, 5s, 720p, Roségold-Trauring rotiert + Kamera-Push-In)

## Build-Stats
- Build-Zeit: ca. 12m
- Sections im HTML: 11 (Topbar, Header, Hero, Marquee, Intro, Kollektionen-Bento, Featured Signature, Atelier, Detail-Grid, Reviews, Visit, Footer)

## Updates
- 2026-04-28: Initial Build
- 2026-04-28: Scroll-Frame-Animation eingebaut (50 Frames, Seedance 2.0 Video + 851-labs Background-Remover; Roségold-Trauring rotiert beim Scrollen)
- 2026-04-28: Sticky-Scroll fix — `body{overflow-x:clip}` + `.scroll-anim{padding:0}`, damit `position:sticky` greift und die Animation den Viewport festhält bis alle 50 Frames durchgelaufen sind
- 2026-04-28: Mobile-Optimierung — Bento (Kollektionen), Featured, Detail-Grid und Reviews werden auf Smartphones (≤768px) zu horizontalen Swipe-Carousels mit Scroll-Snap; 80%-breite Cards mit angeschnittenem Next-Card-Peek + dezenter „Wischen"-Hinweis

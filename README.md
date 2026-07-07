# OSK Start — Szkoła Jazdy

Strona demonstracyjna dla ośrodka szkolenia kierowców OSK Start. Projekt wykonany
jako część portfolio witryn wizytówkowych na [100strona.pl](https://100strona.pl).

## Styl

- **Paleta**: niebieski znaku drogowego (#1d4ed8), żółty „L" (#facc15), czerwony akcent (#ef4444), biel i ciemny granat
- **Fonty**: Outfit (display/nagłówki) + Be Vietnam Pro (body)
- **Klimat**: dynamiczny, energetyczny, motyw znaków i pasów drogowych; reveal na scrollu, mikrointerakcje

## Sekcje

1. Promo bar (link do 100strona.pl)
2. Nawigacja (fixed, mobile menu, efekt scroll)
3. Hero (pełnoekranowy, statystyki zdawalności z animacją liczników)
4. O szkole (przewagi, certyfikaty)
5. Kursy (kat. B, automat, doszkalające, intensywny)
6. Cennik
7. Instruktorzy (4 karty)
8. Zapisy / formularz kontaktowy
9. Opinie kursantów
10. Kontakt + mapa OSM
11. CTA banner
12. Stopka z creditem

## Stack

- **Astro 5** + **Tailwind CSS 4** (przez `@tailwindcss/vite`)
- Zero zewnętrznych zależności JS
- One-page z kotwicami

## Komendy

```bash
npm install
npm run dev      # serwer deweloperski
npm run build    # build produkcyjny → dist/
npm run preview  # podgląd buildu
```

## Hosting

Gotowe do deployu na Vercel — Astro wykrywany automatycznie.

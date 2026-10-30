# Strømpris

Dagens og morgendagens strømpriser i Norge (NO1–NO5), med været for valgt sted.
Én HTML-side, laget for å legges på Hjem-skjermen på iPhone/iPad.

- Priser: [hvakosterstrommen.no](https://www.hvakosterstrommen.no) (spotpris, valgfritt med mva; NO4 er uten mva)
- Vær: [Meteorologisk institutt](https://api.met.no)
- Område, værsted og mva-valg lagres i `localStorage` på enheten.

## Utvikling
    python3 -m http.server -d public 8080     # prøv lokalt: http://localhost:8080/

Ved push til `main` publiserer GitHub Actions `public/` på GitHub Pages.

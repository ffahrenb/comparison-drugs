# comparison-drugs

Interactive overview and comparison of psychoactive substances ("Substanz-Atlas").

Built from `Übersicht_und_Vergleich_Drogen (3).xlsx` (3 sheets: `Tabelle1`, `Quellen`, `Legende`):

- **34 substances × 25 attributes** – class, mechanism, risks, legal status (CH/DE/AT/UN), prevalence, deaths
- every claim linked to its source (**127 sources** with URLs)
- harm ranking after Nutt et al. 2010 (0–100)
- side-by-side comparison of up to 5 substances
- full data table, searchable and filterable by substance class
- dark mode, deep links (`#s=heroin`, `#tab=compare`)

## Usage

Open `index.html` in any browser – it is fully self-contained and works offline. Or serve it:

```sh
python3 -m http.server
```

## Data

- `index.html` – the interactive artifact (data embedded as JSON)
- `Übersicht_und_Vergleich_Drogen (3).xlsx` – source spreadsheet (research date: 28.08.2026)

The overview is intended for information and prevention – it deliberately contains no dosing or consumption instructions.

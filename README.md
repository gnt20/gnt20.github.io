# GNT20 Workshop Website

Static site for the **20th-anniversary workshop of the Group for Neural Theory** (ENS Paris, 29 rue d'Ulm), 11–12 June 2026.

## Pages

| File | Content |
|------|---------|
| `index.html` | Overview, dates, contact |
| `program.html` | Two-day timetable |
| `speakers.html` | Keynotes and contributed talks |
| `abstracts.html` | Full abstracts in program order |
| `venue.html` | Location and transport |

## Local preview

```sh
python3 -m http.server 8000
```

## Content sources

Talk titles and abstracts are sourced from `GNT20-program.xlsx` and `GNT20 Abstracts.xlsx`. There is no build step — update the HTML files manually when the spreadsheets change.

## Deployment

Hosted on GitHub Pages. `.nojekyll` is present so files are served as-is.

# symbols-data4oov

Landelijke coderingen symbolen, met naam, categorie en nummer per symbool.

**Bekijk de catalogus:** https://cogocollect.github.io/symbols-data4oov/

## Inhoud

- `svg/` — de symbolen als SVG, in drie varianten: `_a` (met kader), `_b` (transparant), `_c` (zonder kader)
- `symbols.json` — opzoekbestand met naam, categorie en nummer per symbool, gegenereerd uit de coderingsspreadsheet
- `index.html` — de overzichtspagina die `symbols.json` gebruikt om alle symbolen te tonen, met zoek- en filterfunctie

## Bestandsnaamconventie

Elk symbool heeft een code opgebouwd uit categoriecode + volgnummer, bijvoorbeeld `poi003`. De bijbehorende SVG's heten `poi003_a.svg`, `poi003_b.svg` en `poi003_c.svg`.

## Nieuwe symbolen toevoegen

Zet het SVG-bestand met de juiste naam in de `svg/`-map; de catalogus toont het automatisch zodra de pagina opnieuw laadt. Komt er een heel nieuw symbool bij (met een nieuwe code), dan moeten de spreadsheet en `symbols.json` ook bijgewerkt worden.

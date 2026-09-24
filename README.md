# De Hypotheekaanvraagstraat.nl

Eén-pagina website over het proces van de Hypotheekaanvraagstraat: de zes stappen, waarom het belangrijk is, een contactzoeker voor klantteams, een carrousel met geldverstrekkers en een afsluiting.

## Publiceren via GitHub Pages

1. Maak een nieuwe repository en upload `index.html` (en deze README).
2. Ga naar **Settings → Pages**, kies **Deploy from a branch**, branch `main`, map `/ (root)`.
3. De site staat na een minuut op `https://<gebruikersnaam>.github.io/<repository>/`.

`index.html` is volledig zelfstandig: lettertypen, logo's en de gegevens van alle 39 klantteams (107 kantoren) zitten erin.

## Map `bron/`

De bewerkbare bronbestanden:

- `Hypotheekaanvraagstraat.dc.html` + `support.js` — de pagina
- `data/klantteams.json` / `klantteams.js` — klantteams en vestigingen (uit de ASN-spreadsheet)
- `data/logos.js` + `logos/` — logo's geldverstrekkers
- `_ds/` — Modernist design system (stijlen en componenten)

Open de bronpagina via een lokale webserver (bijv. `npx serve bron`), niet direct als bestand.

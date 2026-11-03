# Doorstuurpagina Lil's Haarsalon

De website van Lil's Haarsalon is verplaatst van `jalvdbroek-ship-it` naar `0xtsotsi`.
Deze repository staat op de oude eigenaar en stuurt bezoekers door naar de nieuwe locatie.

## De live site

- Oude URL: https://jalvdbroek-ship-it.github.io/lils-haarsalon-site/
- Nieuwe URL: https://0xtsotsi.github.io/lils-haarsalon-site/

De oude URL blijft werken: de pagina stuurt meteen door naar de nieuwe locatie.

## De site lokaal openen

Open `index.html` in de browser. Er is geen build-stap en geen installatie nodig.

## Mapstructuur

| Bestand | Doel |
| --- | --- |
| `index.html` | doorstuurpagina voor / |
| `behandelingen/index.html` | doorstuurpagina voor /behandelingen/ |
| `over-ons/index.html` | doorstuurpagina voor /over-ons/ |
| `contact/index.html` | doorstuurpagina voor /contact/ |
| `404.html` | doorstuurpagina voor adressen die niet (meer) bestaan |
| `.github/workflows/pages.yml` | publiceert deze repository op GitHub Pages |
| `README.md` | dit bestand |

## De site online zetten

Elke push naar `main` publiceert de repository opnieuw via de workflow in
`.github/workflows/pages.yml`.

## Controle

- `node tools/forwarding/check-contrast.mjs` meet de kleurcontrasten van de pagina.
- Open de oude URL en controleer dat je op de nieuwe website uitkomt.

## Wat er staat vast

- De bestemming is de GitHub Pages URL van de nieuwe eigenaar, `0xtsotsi`.
- De pagina verandert niets aan de inhoud van de website zelf.

## Wat je nog moet doen voor live gang

- Niets. De pagina staat live zodra de workflow klaar is.

## Techniek

Statische HTML in de root van de repository, zonder frameworks en zonder build-stap.

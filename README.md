# Farozoner AB — Webbsajt

Statisk webbsajt för Farozoner AB, fastighetsförvaltare i Öresundsregionen.

## Filer

- `index.html` — startsida med fastighetsbestånd, lediga objekt och kontakt
- `felanmalan.html` — felanmälningsformulär för hyresgäster (skickar via Web3Forms)
- `admin.html` — adminvy (statisk mockup, fas 2 = riktig backend)

## Driftsättning

Hostas på GitHub Pages. Pushar du till `main`-branchen deployas automatiskt på ~30 sekunder.

## Felanmälan

Formuläret postar till Web3Forms-API:t. Mottagaradress styrs i Web3Forms-dashboarden,
inte i koden. Access keyen finns hårdkodad i `felanmalan.html`.

För att byta mottagare: logga in på web3forms.com och ändra Email i Settings.

## Kontakt

- Albin: 0708-82 87 19
- Filip: 0731-79 46 85

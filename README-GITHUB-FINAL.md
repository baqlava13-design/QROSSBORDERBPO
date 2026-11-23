# Qrossborder — definitieve 3-pagina versie

## Pagina’s
- `/` — Home (met klantformulier en vier stappen)
- `/expertise/` — Expertise & Diensten
- `/werken-bij/` — Werken bij (compact kandidaatformulier)
- `/#contact` — Contact is een anker naar de homepage

## Bestaande functionaliteit
- React/Vite, bestaande assets, bestaande mobiele navigatie en Web3Forms-koppeling blijven behouden.
- Klant- en kandidaatformulier gebruiken dezelfde bestaande Web3Forms-toegangssleutel, maar verschillende onderwerpregels.
- Kandidaten bevestigen verplicht Nederlands spreken én schrijven op moedertaalniveau. Dit is een zelfverklaring; verifieer tijdens screening.
- Geen tarievenpagina of publieke vaste tarieven.

## Installatie / GitHub
1. Maak een back-up of nieuwe branch van de huidige repository.
2. Upload de inhoud van deze projectmap (niet de bovenliggende map) naar de repository.
3. Voer `npm install` en `npm run build` uit.
4. Test mobiel, navigatie en beide Web3Forms-formulieren met echte testinzendingen vóór livegang.
5. Controleer of de host alle routes naar `index.html` doorstuurt (SPA fallback).

Let op: de toegangssleutel is overgenomen uit de bestaande broncode. De ontvangst van berichten is niet live getest. Er zijn geen wijzigingen aan de live site of GitHub gedaan.

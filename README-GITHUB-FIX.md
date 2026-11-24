# Qrossborder – correctie GitHub/Railway

- Dubbele declaratie van `ProfessionalPage` verwijderd (Railway-buildfout).
- `/expertise/` gekoppeld aan de bestaande `ExpertisePage`.
- Ongedefinieerde `TalentLevels`-aanroep op de expertisepagina vervangen door een compacte talentniveausectie.
- Desktop hero-foto's op Home, Expertise en Werken bij lopen door tot de rechter viewport-rand met diagonale uitsnede. Mobiele weergave blijft gestapeld.
- Bestaande formulierlogica en Web3Forms-configuratie niet gewijzigd.

## Installatie
Upload de inhoud van deze ZIP naar de root van de GitHub-repository, met behoud van de mapstructuur. Maak eerst een backup of gebruik een testbranch. Railway kan na commit opnieuw bouwen.

## Controle
In deze omgeving kon `npm install` niet worden voltooid, dus de productiebuild en het daadwerkelijk versturen van formulieren zijn **niet** geverifieerd. Test na de deployment de routes `/`, `/expertise/` en `/werken-bij/` en de twee formulieren. Geen toegangssleutels publiek delen.

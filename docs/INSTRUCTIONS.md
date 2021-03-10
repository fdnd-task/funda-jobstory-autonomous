# Doorzoek de OBA Collectie

Voor de opdracht Doorzoek-de-OBA-Collectie ontwerp je voor de OBA een user-interface met externe data.

## Context
*Bij welke sprint hoort deze leertaak en welk niveau heeft deze leertaak.*

Leertaak: Werk voor een opdrachtgever een interactie uit met externe data.
Deze leertaak hoort bij sprint 8 "Keep Users in Control".
Dit is een zelfstandige opdracht voor een opdrachtgever.

## Briefing
*In de briefing staat wat de opdracht is en wat de opdrachtgever wil.*

De [Openbare Bibliotheek Amsterdam](https://www.oba.nl) (OBA) heeft een enorme collectie aan boeken. Ruim 422.000 titels staan in een database. Naast de titel en de schrijver kun je boeken op verschillende manieren vinden: hoeveel pagina's heeft het boek, is het een moeilijk of makkelijk boek, het genre, onderwerp, je kunt zelfs zoeken op de kleur van de kaft. 
Met de OBA-API kun je alle informatie over boeken opvragen en gebruiken om een website mee te maken.

Ontwerp een user-interface voor het zoeken van een boek bij de OBA, voor jongeren van 12-14 jaar.

## Doel van deze leertaak
*Wat leer je in deze taak.*

Je leert hoe je externe data kunt laden en gebruiken om zoekresulaten te presenteren.

## Werkwijze
*De werkwijze volgt de fasering van de Development Life Cycle.*

Ontwerp en maak een user interface op basis van deze Job Stories.

> "Als ik een boek zoek wil ik op basis van een genre een lijst boeken krijgen die geschikt zijn voor mijn leeftijd."

> "Ik wil in een lijst zoekresultaten de boeken op verschillende manieren kunnen filteren om een geschikt boek te vinden."

> "Ik wil suggesties krijgen als ik na een zoekopracht geen of weinig resultaten krijg."

Deze opdracht gaat over alle fases van de DLC [analyseren](#analyseren), [ontwerpen](#ontwerpen), [bouwen](#bouwen), [integreren](#integreren) en [testen](#testen).

### Analyseren
*In de analysefase inventariseer je wat er moet gebeuren om een taak uit te voeren.*

<details>
<summary>Aanpak</summary>

1. Onderzoek de doelgroep.
2. Onderzoek de functionaliteiten.
3. Onderzoek de OBA-API.
4. Maak een debrief zoals je geleerd hebt.

#### Materiaal

- [OBA-API documentatie](https://zoeken.oba.nl/api/v1/)

</details>

### Ontwerpen
*In de ontwerpfase neem je ontwerpbeslissingen en zorg je dat je precies weet wat je moet gaan bouwen.*

<details>
<summary>Aanpak</summary>

1. Beschrijf de doelgroep in een user scenario.
2. Zoek UI voorbeelden voor het zoekformulier en het tonen van resultaten.
3. Schets per Job Story een wireflow van de interface en werking.
4. Ontwerp de verschillende states.
5. Teken een break-down schets.

#### Materiaal

- [How User Scenarios help To Improve Your UX](https://usabilla.com/blog/how-user-scenarios-help-to-improve-your-ux/)
- [How to fix a bad user interface](https://www.scotthurff.com/posts/why-your-user-interface-is-awkward-youre-ignoring-the-ui-stack/).
- [Schetsvaardigheden](https://www.youtube.com/channel/UCdVXQjEmKQJbEhClP94mX3Q)

</details>

### Bouwen
*In de bouwfase realiseer je de beslissingen uit de ontwerpfase.*
<details>
<summary>Aanpak</summary>

1. Bouw het ontwerp.

#### Materiaal

n.v.t.

</details>


### Integreren
*In de integratiefase voer je de aanpassingen door zodat iedereen ze kan zien.*

<details>
<summary>Aanpak</summary>

1. Zet je code op Github. 

#### Materiaal

- 

</details>

#### Testen
*In de testfase controleer je of jouw aanpassingen werken zoals bedoeld.*

<details>
<summary>Aanpak</summary>

1. Test je ontwerp en verwerk de testresultaten.
2. Presenteer je ontwerp bij de opdrachtgever.

#### Materiaal

- Tips over hoe je je werk presenteert aan een opdrachtgever op basis van Job Stories. 

</details>

## Criteria
*Definitions of done*

1. De data wordt van een externe bron ingeladen met Javascript.
2. De zoekresultaten worden getoond in een webpagina.
3. De UI is duidelijk en prettig te gebruiken met goede feedback en ...
4. Een aantal states van de UI stack worden opgevangen en zijn vormgegeven.
5. Verschillende *HTTP response status codes* zijn opgevangen en vormgegeven.


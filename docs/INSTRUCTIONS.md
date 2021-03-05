# Doorzoek de OBA collectie

Voor de opdracht Doorzoek-de-OBA-collectie leer je met externe data een user-interface ontwerpen en maken. 

## Context
    Wat schrijven we hier?
    Hoe deze opdracht in de sprint past, welke leertaak het is en welk niveau de leertaak heeft?

Leertaak: Werk voor een opdrachtgever een interactie uit met externe data. Deze opdracht hoort bij sprint 8 "Keep Users in Control". Dit is een [zelfstandige opdracht voor een opdrachtgever](#niveau-van-een-leertaak).

## Briefing
*In de briefing staat wat de opdracht is en wat de opdrachtgever wil.*

De [Openbare Bibliotheek Amsterdam](https://www.oba.nl) (OBA) heeft een enorme collectie aan boeken. Ruim 422.000 titels staan in een database. Naast de titel en de schrijver kun je boeken op verschillende manieren vinden: hoeveel pagina's heeft het boek, is het een moeilijk of makkelijk boek, het genre, onderwerp, je kunt zelfs zoeken op de kleur van de kaft. Met de OBA-API kun je alle informatie over boeken opvragen en gebruiken om een website mee te maken.

Ontwerp de user interface voor het zoeken van een boek bij de OBA, voor jongeren van 12-14 jaar.

## Doel van deze opdracht
    Wat schrijven we hier?
    Wat leren de studenten in relatie tot de focus van deze sprint?

Je leert hoe je externe data kunt laden en gebruiken om zoekresulaten te presenteren.

## Werkwijze
*De werkwijze volgt de fasering van de [Development Life Cycle](#werkwijze-volgens-de-development-life-cycle).*

Ontwerp en maak een user interface op basis van deze Job Stories.

> "Als ik een boek zoek wil ik op basis van een genre een lijst boeken krijgen, die geschikt zijn voor mijn leeftijd."

> "Ik wil in een lijst zoekresultaten de boeken op verschillende manieren kunnen filteren om een geschikt boek te vinden."

> "Ik wil suggesties krijgen als ik een zoekopracht geef die geen of weinig resultaten geeft."

Deze opdracht gaat over alle fases van de DLC [analyseren](#analyseren), [ontwerpen](#ontwerpen), [bouwen](#bouwen), [integreren](#integreren) en [testen](#testen).

### Analyseren
*In de analysefase inventariseer je wat er moet gebeuren om een taak uit te voeren.* 

<details>
<summary>Werkwijze</summary>

1. Wie is de doelgroep? 
2. De OBA-API uitpluizen, wat staat er allemaal in de JSON? Hoe kun je hier de  boeken voor een bepaalde leeftijd uit halen?

#### Resources analyseren

- [OBA-API documentatie](https://zoeken.oba.nl/api/v1/)

</details>

### Ontwerpen
*In de ontwerpfase neem je ontwerpbeslissingen en zorg je dat je precies weet wat je moet gaan bouwen.*

<details>
<summary>Werkwijze</summary>

1. [Doelgroep beschrijven in een user scenario](https://usabilla.com/blog/how-user-scenarios-help-to-improve-your-ux/)
2. Zoek UI voorbeelden voor het zoekformulier en tonen van resultaten.
3. Schets per Job Stories de interface en werking.
4. Ontwerp verschillende states.
5. Teken een break-down schets.

#### Resources ontwerpen

- Artikel over states van een zoekformulier [How to fix a bad user interface](https://www.scotthurff.com/posts/why-your-user-interface-is-awkward-youre-ignoring-the-ui-stack/).

</details>

### Bouwen
*In de bouwfase realiseer je de beslissingen uit de ontwerpfase.*
<details>
<summary>Beschrijving</summary>

1. Bouw het ontwerp.

#### Resources bouwen

n.v.t.

</details>


### Integreren
*In de integratiefase voer je de aanpassingen door zodat iedereen ze kan zien.*

<details>
<summary>Beschrijving</summary>

1. Zet je code op Github. 

#### Resources integreren

- 

</details>

#### Testen
*In de testfase controleer je of jouw aanpassingen werken zoals bedoeld.*

<details>
<summary>Beschrijving</summary>

1. Presenteer je ontwerp bij de opdrachtgever.

#### Resources testen

- Tips over hoe je je werk presenteert een opdrachtgever, op basis van Job Stories. 

</details>

## Criteria
*Definitions of done*

1. De data wordt van een externe bron ingeladen met Javascript.
2. De zoekresultaten worden getoond in een webpagina.
3. De UI is duidelijk en prettig te gebruiken met goede feedback en ...
4. Een aantal states van de UI stack worden opgevangen en zijn vormgegeven.
5. Verschillende *HTTP response status codes* zijn opgevangen en vormgegeven.

# Niveau van een leertaak

|   | Scaffolding | Description |
| ---: | :----   | :--- |
| a | Example | Uitgewerkt voorbeeld in het college |
| b | Duplicate | Immitatietaak in een workshop |
| c | Experiment | Taak zonder een specifiek doel |
| d | Extension | Aanvultaak |
| e | Autonomous | Taak zonder ondersteuning |

Meer over [Leertaken, complexiteit en begeleiding in Didactiek en toetsing](hhttps://github.com/fdnd/documents/blob/master/Bijlage%2006%20Didactiek%20en%20toetsing.md#leertaken)

# Werkwijze volgens de Development Life Cycle

Bij FDND gebruiken we voor de werkwijze de fasering van de Development Life Cycle. Leertaken kunnen een of meerdere fases doorlopen.

1. Analyse.
2. Design.
3. Bouwen.  
4. Integreren.
5. Testen.

Meer over de [Development Life Cycle in Didactiek en toetsing](hhttps://github.com/fdnd/documents/blob/master/Bijlage%2006%20Didactiek%20en%20toetsing.md#development-life-cycle)

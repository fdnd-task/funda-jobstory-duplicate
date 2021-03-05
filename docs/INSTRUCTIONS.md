# Zoek een spannend boek in de OBA collectie

In de opdracht Zoek-een-spannend-boek-bij-de-OBA leer je in een workshop hoe je JSON data laden en tonen op een pagina.

## Context
*Bij welke sprint hoort deze leertaak en welk niveau heeft deze leertaak.*

- Leertaak: Werk voor een opdrachtgever een interactie uit met externe data.
- Sprint 8 'keep Users In Control".
- [Immitatietaak](#niveau-van-een-leertaak) in een workshop.

Leertaak: Werk voor een opdrachtgever een interactie uit met externe data. Deze leertaak hoort bij sprint 8 "Keep Users in Control". Dit is een immitatietaak, hierna kun je een experimenteer opdracht doen.

## Briefing
*In de briefing staat wat de opdracht is en wat de opdrachtgever wil.*

Ontwerp voor de OBA een zoekresultatenpagina met spannende boeken.

## Doel van deze opdracht
*Wat leer je in deze taak.*

Je leert hoe je externe data kunt laden en gebruiken om zoekresulaten te presenteren.

## Werkwijze
*De werkwijze volgt de fasering van de Development Life Cycle.*

Aan de hand van een Job Story ga je met de OBA-API zoekresultaten tonen.

> "Als ik een boek zoek wil ik een lijst spannende boeken te zien krijgen, die geschikt zijn voor mijn leeftijd."

Deze opdracht gaat over alle fases van de DLC [analyseren](#analyseren), [ontwerpen](#ontwerpen), [bouwen](#bouwen), [integreren](#integreren) en [testen](#testen).

### Analyseren
*In de analysefase inventariseer je wat er moet gebeuren om een taak uit te voeren.* 

<details>
<summary>Aanpak</summary>

1. Onderzoek de OBA-API, wat staat er allemaal in de JSON? Hoe kun je hier de spannende boeken voor een bepaalde leeftijd uit halen?

#### Materiaal

- [OBA-API documentatie](https://zoeken.oba.nl/api/v1/)

</details>

### Ontwerpen
*In de ontwerpfase neem je ontwerpbeslissingen en zorg je dat je precies weet wat je moet gaan bouwen.*

<details>
<summary>Aanpak</summary>

1. Zoek UI voorbeelden voor het zoekformulier en het tonen van resultaten.
2. Schets voor de Job Story een wireflow van de interface en werking.
3. Annoteren hoe je spannende boeken voor een bepaalde leeftijd kan ophalen. Wat is de request url?

#### Materiaal

- 

</details>

### Bouwen
*In de bouwfase realiseer je de beslissingen uit de ontwerpfase.*
<details>
<summary>Aanpak</summary>

1. 

#### Materiaal

- Hier staat een [tutorial](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) voor het laden van JSON data en het aanmaken van HTMl elementen.
- Met behulp van [XMLHttpRequest](https://developer.mozilla.org/en-US/docs/Web/API/XMLHttpRequest/Using_XMLHttpRequest) of [Fetch](https://developer.mozilla.org/en-US/docs/Web/API/Fetch_API/Using_Fetch) kan een [JSON](https://developer.mozilla.org/en-US/docs/Learn/JavaScript/Objects/JSON) file worden geladen. Daarna kun je de HTML elementen aanmaken, de juiste content koppelen en aan de DOM toevoegen.
- Bij het laden van externe data kan de server verschillende [HTTP response status codes](https://developer.mozilla.org/en-US/docs/Web/HTTP/Status) doorgeven, die kun je gebruiken om feedback te tonen.

</details>


### Integreren
*In de integratiefase voer je de aanpassingen door zodat iedereen ze kan zien.*
<details>
<summary>Aanpak</summary>

1. 

#### Materiaal

- 

</details>

### Testen
*In de testfase controleer je of jouw aanpassingen werken zoals bedoeld.*
<details>
<summary>Aanpak</summary>

1. 

#### Materiaal

- 

</details>

## Criteria
*Definitions of done*

1. De data wordt van een externe bron ingeladen met JS.
2. De zoekresultaten worden getoond in een webpagina.
3. Een aantal *HTTP response status codes* zijn opgevangen en vormgegeven.

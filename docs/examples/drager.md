# Voorbeelden: Drager

Hieronder staan representatieve voorbeelden van concepten in de codelijst Drager.

## Drager: TSP (Total Suspended Particulates)

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/drager/DR_7>
        rdf:type           skos:Concept , csor:Drager;
        owl:deprecated     false;
        skos:inScheme      <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/drager>;
        skos:prefLabel     "TSP"@nl;
        skos:topConceptOf  <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/drager> .
```

## Drager: Water

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/drager/DR_1>
        rdf:type           skos:Concept , csor:Drager;
        owl:deprecated     false;
        skos:definition    "Water zoals bijv, drinkwater, afvalwater, oppervlaktewater, grondwater, zeewater,..."@nl;
        skos:inScheme      <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/drager>;
        skos:prefLabel     "water"@nl;
        skos:topConceptOf  <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/drager> .
```

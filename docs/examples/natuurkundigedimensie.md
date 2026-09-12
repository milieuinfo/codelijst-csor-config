# Voorbeelden: Natuurkundige Dimensie

Hieronder staan representatieve voorbeelden van concepten in de codelijst Natuurkundige Dimensie.

## Natuurkundige Dimensie: lengte

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_10>
        rdf:type                skos:Concept , csor:NatuurkundigeDimensie;
        owl:deprecated          false;
        skos:inScheme           <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/natuurkundigedimensie>;
        skos:notation           "ND_10";
        skos:prefLabel          "lengte"@nl;
        skos:topConceptOf       <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/natuurkundigedimensie>;
        csor:referentieEenheid  <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_59>;
        csor:symbool            "l" .
```

## Natuurkundige Dimensie: massaverhouding

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_3>
        rdf:type                skos:Concept , csor:NatuurkundigeDimensie;
        owl:deprecated          false;
        skos:inScheme           <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/natuurkundigedimensie>;
        skos:notation           "ND_3";
        skos:prefLabel          "massaverhouding"@nl;
        skos:topConceptOf       <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/natuurkundigedimensie>;
        csor:referentieEenheid  <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_26>;
        csor:symbool            "m.m(-1)" .
```

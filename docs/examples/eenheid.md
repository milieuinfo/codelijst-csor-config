# Voorbeelden: Eenheid

Hieronder staan representatieve voorbeelden van concepten in de codelijst Eenheid.

## Eenheid: gram per jaar

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_17>
        rdf:type           skos:Concept , csor:Eenheid;
        owl:deprecated     false;
        skos:inScheme      <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/eenheid>;
        skos:notation      "E_17";
        skos:prefLabel     "gram per jaar"@nl;
        skos:topConceptOf  <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/eenheid>;
        csor:heeftNatuurkundigeDimensie
                <https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_2>;
        csor:symbool       "g/jr" .
```

## Eenheid: gram equivalenten per liter

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_274>
        rdf:type              skos:Concept , csor:Eenheid;
        owl:deprecated        false;
        skos:inScheme         <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/eenheid>;
        skos:notation         "E_274";
        skos:prefLabel        "gram equivalenten per liter"@nl;
        skos:topConceptOf     <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/eenheid>;
        csor:conversiefactor  1000000000000.0;
        csor:heeftNatuurkundigeDimensie
                <https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_1> .
```

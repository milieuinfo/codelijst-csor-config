# Voorbeelden: Variabele

Hieronder staan representatieve voorbeelden van concepten in de codelijst Variabele.

## Variabele: Acenaftyleen

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/variabele/V_115>
        rdf:type           csor:Variabele , skos:Concept;
        owl:deprecated     false;
        skos:inScheme      <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/variabele>;
        skos:notation      "V_115";
        skos:prefLabel     "Acenaftyleen"@nl;
        skos:topConceptOf  <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/variabele>;
        csor:cas           "208-96-8";
        csor:inchikey      "HXGDTGSAIMULJN-UHFFFAOYSA-N";
        csor:iupacNaam     "acenaphthylene";
        csor:symbool       "Acenaftyl" .
```

## Variabele: Doorzichtigheid

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/variabele/V_296>
        rdf:type           skos:Concept , csor:Variabele;
        owl:deprecated     false;
        skos:inScheme      <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/variabele>;
        skos:notation      "V_296";
        skos:prefLabel     "Doorzichtigheid"@nl;
        skos:topConceptOf  <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/variabele>;
        csor:eea           "3111-01-1";
        csor:symbool       "Secchi" .
```

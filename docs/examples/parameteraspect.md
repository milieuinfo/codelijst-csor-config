# Voorbeelden: Parameter Aspect

Hieronder staan representatieve voorbeelden van concepten in de codelijst Parameter Aspect.

## Parameter Aspect: suc (standaard in water): massaconcentratie

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/parameteraspect/PAS_6487>
        rdf:type             skos:Concept , csor:ParameterAspect;
        owl:deprecated       false;
        skos:inScheme        <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/parameteraspect>;
        skos:prefLabel       "suc (standaard in water): massaconcentratie"@nl;
        skos:topConceptOf    <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/parameteraspect>;
        csor:heeftAspect     <https://data.omgeving.vlaanderen.be/id/concept/csor/kwantificeerbaaraspect/KWA_1>;
        csor:heeftParameter  <https://data.omgeving.vlaanderen.be/id/concept/csor/parameter/P_4570> .
```

## Relatie tussen Parameter en Parameter Aspect

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/parameter/P_3593>
        csor:heeftParameterAspect  <https://data.omgeving.vlaanderen.be/id/concept/csor/parameteraspect/PAS_7710> .
```

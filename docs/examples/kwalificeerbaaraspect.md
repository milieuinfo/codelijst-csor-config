# Voorbeelden: Kwalificeerbaar Aspect

Hieronder staan representatieve voorbeelden van concepten in de codelijst Kwalificeerbaar Aspect.

## Kwalificeerbaar Aspect: Aantoonbaarheid

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/kwalificeerbaaraspect/KWL_1>
        rdf:type                 skos:Concept , csor:KwalificeerbaarAspect;
        owl:deprecated           false;
        skos:definition          "Migratie Handhaving - Te bevestigen | Niet aangetoond | Aangetoond"@nl;
        skos:inScheme            <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwalificeerbaaraspect>;
        skos:notation            "KWL_1";
        skos:prefLabel           "Aantoonbaarheid"@nl;
        skos:topConceptOf        <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwalificeerbaaraspect>;
        csor:heeftResultaattype  <https://data.omgeving.vlaanderen.be/id/concept/csor/resultaattype/RT_2>;
        csor:symbool             "AANTOONBAARHEID" .
```

## Kwalificeerbaar Aspect: Aanwezigheid

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlageving.vlaanderen.be/id/concept/csor/kwalificeerbaaraspect/KWL_2>
        rdf:type                 csor:KwalificeerbaarAspect , skos:Concept;
        owl:deprecated           false;
        skos:definition          "Migratie Handhaving - Niet bepaalbaar | Aanwezig | Afwezig"@nl;
        skos:inScheme            <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwalificeerbaaraspect>;
        skos:notation            "KWL_2";
        skos:prefLabel           "Aanwezigheid"@nl;
        skos:topConceptOf        <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwalificeerbaaraspect>;
        csor:heeftResultaattype  <https://data.omgeving.vlaanderen.be/id/concept/csor/resultaattype/RT_2> .
```

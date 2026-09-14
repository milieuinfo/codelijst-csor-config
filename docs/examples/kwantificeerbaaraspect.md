# Voorbeelden: Kwantificeerbaar Aspect

Hieronder staan representatieve voorbeelden van concepten in de codelijst Kwantificeerbaar Aspect.

## Vracht

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/kwantificeerbaaraspect/KWA_8>
    rdf:type                 skos:Concept , csor:KwantificeerbaarAspect;
    owl:deprecated           false;
    skos:inScheme            <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
    skos:notation            "KWA_8";
    skos:prefLabel           "massa"@nl;
    skos:topConceptOf        <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
    csor:heeftNatuurkundigeDimensie
        <https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_5>;
    csor:heeftResultaattype  <https://data.omgeving.vlaanderen.be/id/concept/csor/resultaattype/RT_1>;
    csor:kwantificeerbaarAspectType "INDIVIDUELE_OBSERVATIE";
    csor:symbool             "MASSA";
    csor:toepasbareEenheid   <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_218> ,
        <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_40> ,
        <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_37> ,
        <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_36> ,
        <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_39> ,
        <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_41> ,
        <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_38> .
```

## Vracht

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/kwantificeerbaaraspect/KWA_5>
        rdf:type                 csor:KwantificeerbaarAspect , skos:Concept;
        owl:deprecated           false;
        skos:inScheme            <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
        skos:notation            "KWA_5";
        skos:prefLabel           "vracht"@nl;
        skos:topConceptOf        <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
        csor:heeftNatuurkundigeDimensie
        <https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_5>;
        csor:heeftResultaattype  <https://data.omgeving.vlaanderen.be/id/concept/csor/resultaattype/RT_1>;
        csor:kwantificeerbaarAspectType "VRACHT";
        csor:symbool             "VRACHT";
        csor:toepasbareEenheid   <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_36> ,
            <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_39> ,
            <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_41> ,
            <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_38> ,
            <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_218> ,
            <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_40> ,
            <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_37> .
```

## Vracht stikstof

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/kwantificeerbaaraspect/KWA_37>
        rdf:type                 skos:Concept , csor:KwantificeerbaarAspect;
        owl:deprecated           false;
        skos:inScheme            <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
        skos:notation            "KWA_37";
        skos:prefLabel           "vracht stikstof"@nl;
        skos:topConceptOf        <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
        csor:heeftNatuurkundigeDimensie
            <https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_5>;
        csor:heeftResultaattype  <https://data.omgeving.vlaanderen.be/id/concept/csor/resultaattype/RT_1>;
        csor:kwantificeerbaarAspectType "VRACHT";
        csor:symbool             "VRACHT_N";
        csor:toepasbareEenheid   <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_113> , <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_111> , <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_112>;
        csor:uitgedruktIn        <https://data.omgeving.vlaanderen.be/id/concept/csor/variabele/V_231> .
```

## Kwantificeerbaar Aspect: vracht fosfor per tijd

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/kwantificeerbaaraspect/KWA_54>
        rdf:type                 csor:KwantificeerbaarAspect , skos:Concept;
        owl:deprecated           false;
        skos:inScheme            <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
        skos:notation            "KWA_54";
        skos:prefLabel           "vracht fosfor per tijd"@nl;
        skos:topConceptOf        <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
        csor:heeftNatuurkundigeDimensie
                <https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_2>;
        csor:heeftResultaattype  <https://data.omgeving.vlaanderen.be/id/concept/csor/resultaattype/RT_1>;
        csor:kwantificeerbaarAspectType
                "VRACHT";
        csor:symbool             "VRACHT_P_PER_TIJD";
        csor:toepasbareEenheid   <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_143> , <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_171>;
        csor:uitgedruktIn        <https://data.omgeving.vlaanderen.be/id/concept/csor/variabele/V_46> .
```

## Kwantificeerbaar Aspect: massaconcentratie sulfaat

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/kwantificeerbaaraspect/KWA_124>
        rdf:type                 skos:Concept , csor:KwantificeerbaarAspect;
        owl:deprecated           false;
        skos:inScheme            <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
        skos:notation            "KWA_124";
        skos:prefLabel           "massaconcentratie sulfaat"@nl;
        skos:topConceptOf        <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/kwantificeerbaaraspect>;
        csor:heeftNatuurkundigeDimensie
                <https://data.omgeving.vlaanderen.be/id/concept/csor/natuurkundigedimensie/ND_1>;
        csor:heeftResultaattype  <https://data.omgeving.vlaanderen.be/id/concept/csor/resultaattype/RT_1>;
        csor:kwantificeerbaarAspectType
                "INDIVIDUELE_OBSERVATIE";
        csor:symbool             "MASSACONC_SO4";
        csor:toepasbareEenheid   <https://data.omgeving.vlaanderen.be/id/concept/csor/eenheid/E_298> .
```

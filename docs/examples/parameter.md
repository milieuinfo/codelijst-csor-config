# Voorbeelden: Parameter

Hieronder staan representatieve voorbeelden van concepten en gerelateerde klassen in de codelijst Parameter.

## Parameter: Butylacetaat in vaste deel van de aarde

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix owl: <http://www.w3.org/2002/07/owl#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/parameter/P_3593>
        rdf:type                       csor:Parameter , skos:Concept;
        owl:deprecated                 false;
        skos:altLabel                  "Butylacetaat"@nl;
        skos:inScheme                  <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/parameter>;
        skos:notation                  "P_3593";
        skos:prefLabel                 "Butylacetaat in vaste deel van de aarde"@nl;
        skos:topConceptOf              <https://data.omgeving.vlaanderen.be/id/conceptscheme/csor/parameter>;
        csor:heeftDrager               <https://data.omgeving.vlaanderen.be/id/concept/csor/drager/DR_2>;
        csor:heeftSoortWaardebepaling  <https://data.omgeving.vlaanderen.be/id/concept/csor/soortwaardebepaling/SWB_1>;
        csor:heeftVariabele            <https://data.omgeving.vlaanderen.be/id/concept/csor/variabele/V_815>;
        csor:symbool                   "ByAc";
        csor:verkorteNotatie           "Butylacetaat"@nl .
```

## ParameterAfleidingVeelterm: Som van de dimethylfenolen

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/parameterafleidingveelterm/som_van_de_dimethylfenolen>
        rdf:type                 csor:ParameterAfleidingVeelterm;
        skos:definition          "som van de dimethylfenolen"@nl;
        skos:prefLabel           "som van de dimethylfenolen"@nl;
        csor:heeftDoelParameter  <https://data.omgeving.vlaanderen.be/id/concept/csor/parameter/P_1669>;
        csor:heeftTerm           [ rdf:type                 csor:VeeltermParameterTerm;
                                   csor:factor              1.0;
                                   csor:heeftBronParameter  <https://data.omgeving.vlaanderen.be/id/concept/csor/parameter/P_1023>;
                                   csor:verplicht           false
                                 ];
        csor:heeftTerm           [ rdf:type                 csor:VeeltermParameterTerm;
                                   csor:factor              1.0;
                                   csor:heeftBronParameter  <https://data.omgeving.vlaanderen.be/id/concept/csor/parameter/P_489>;
                                   csor:verplicht           false
                                 ] .
```

## OrganisatieSpecifiekeReferentie

```turtle
@prefix csor: <https://data.omgeving.vlaanderen.be/ns/csor#> .
@prefix dc: <http://purl.org/dc/elements/1.1/> .
@prefix dct: <http://purl.org/dc/terms/> .
@prefix prov: <http://www.w3.org/ns/prov#> .
@prefix rdf: <http://www.w3.org/1999/02/22-rdf-syntax-ns#> .
@prefix skos: <http://www.w3.org/2004/02/skos/core#> .

<https://data.omgeving.vlaanderen.be/id/concept/csor/organisatiespecifiekereferentie/OSR_273>
        rdf:type        csor:OrganisatieSpecifiekeReferentie;
        dc:creator      "OVO000092";
        dc:subject      "ID";
        dc:type         "VMM_LEGACY_ID";
        dct:creator     <https://data.vlaanderen.be/id/organisatie/OVO000092>;
        dct:references  <https://data.omgeving.vlaanderen.be/id/concept/csor/parameter/P_273>;
        skos:prefLabel  "OSR_273"@nl;
        prov:value      "214" .
```

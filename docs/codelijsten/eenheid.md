# Eenheid

Een maat waarin een natuurkundige dimensie of een kwantificeerbaar aspect numeriek kan worden uitgedrukt.

## Overzicht diagram

```mermaid
classDiagram
    class Eenheid {
        +skos:prefLabel prefLabel [1..1]
        +skos:definition definition [0..1]
        +skos:notation notation [1..1]
        +csor:symbool symbool [1..1]
        +csor:heeftNatuurkundigeDimensie natuurkundigeDimensie [1..1]
        +csor:conversiefactor conversiefactor [0..1]
        +skos:broader broader [0..1]
        +skos:inScheme inScheme [1..1]
        +skos:topConceptOf topConceptOf [0..1]
        +owl:deprecated deprecated [0..1]
        +csor:geldigTot geldigTot [0..1]
    }
    Eenheid "0..*" --> "0..1" NatuurkundigeDimensie : behoortTotNatuurkundigeDimensie
    Eenheid "0..*" --> "0..1" Eenheid : broader
```

## Eigenschappen

De klasse `csor:Eenheid` heeft de volgende eigenschappen:

| Eigenschap | URI | Type | Cardinaliteit | Beschrijving |
| :--- | :--- | :--- | :--- | :--- |
| **prefLabel** | `skos:prefLabel` | `xsd:string` | 1..1 | De voorkeursnaam van de eenheid. |
| **definition** | `skos:definition` | `xsd:string` | 0..1 | Een tekstuele definitie. |
| **notation** | `skos:notation` | `xsd:string` | 0..1 | Een unieke notatie. |
| **symbool** | `csor:symbool` | `xsd:string` | 0..1 | Symbool dat gebruikt wordt om het concept weer te geven. |
| **natuurkundigeDimensie** | `csor:heeftNatuurkundigeDimensie` | `csor:NatuurkundigeDimensie` | 0..1 | De natuurkundige dimensie waartoe de eenheid behoort. |
| **conversiefactor** | `csor:conversiefactor` | `xsd:decimal` | 0..1 | Factor voor omzetting naar de referentie-eenheid. |
| **broader** | `skos:broader` | `csor:Eenheid` | 0..1 | Een meer algemene eenheid. |
| **inScheme** | `skos:inScheme` | `skos:ConceptScheme` | 1..1 | Het conceptschema waartoe dit concept behoort. |
| **topConceptOf** | `skos:topConceptOf` | `skos:ConceptScheme` | 0..1 | Geeft aan of dit een topconcept is. |
| **deprecated** | `owl:deprecated` | `xsd:boolean` | 0..1 | Geeft aan of het concept verouderd is. |
| **geldigTot** | `csor:geldigTot` | `xsd:date` | 0..1 | De datum tot wanneer het concept geldig is. |

## Voorbeelden

Een overzicht van voorbeelden voor deze codelijst is te vinden op de [voorbeelden pagina](../examples/eenheid.md).

## RDF Data

De brondata is beschikbaar in verschillende formaten:
- [Turtle](../../codelijst-project/output/be/vlaanderen/omgeving/data/id/conceptscheme/csor/eenheid/eenheid.ttl)

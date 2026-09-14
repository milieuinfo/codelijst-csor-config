# Natuurkundige Dimensie

Een natuurkundige dimensie duidt aan welke grootheid gebruikt wordt om de observatie te doen.

## Overzicht diagram

```mermaid
classDiagram
    class NatuurkundigeDimensie {
        +skos:prefLabel prefLabel [1..1]
        +skos:definition definition [0..1]
        +skos:notation notation [1..1]
        +csor:symbool symbool [1..1]
        +csor:referentieEenheid referentieEenheid [0..1]
        +skos:inScheme inScheme [1..1]
        +skos:topConceptOf topConceptOf [1..1]
        +owl:deprecated deprecated [0..1]
        +csor:geldigTot geldigTot [0..1]
    }
    NatuurkundigeDimensie "0..*" --> "0..1" Eenheid : referentieEenheid
```

## Eigenschappen

De klasse `csor:NatuurkundigeDimensie` heeft de volgende eigenschappen:

| Eigenschap | URI | Type | Cardinaliteit | Beschrijving |
| :--- | :--- | :--- | :--- | :--- |
| **prefLabel** | `skos:prefLabel` | `xsd:string` | 1..1 | De voorkeursnaam van de natuurkundige dimensie. |
| **definition** | `skos:definition` | `xsd:string` | 0..1 | Een tekstuele definitie. |
| **notation** | `skos:notation` | `xsd:string` | 0..1 | Een unieke notatie. |
| **symbool** | `csor:symbool` | `xsd:string` | 0..1 | Symbool dat gebruikt wordt om het concept weer te geven. |
| **referentieEenheid** | `csor:referentieEenheid` | `csor:Eenheid` | 0..1 | De referentie-eenheid van de natuurkundige dimensie. |
| **inScheme** | `skos:inScheme` | `skos:ConceptScheme` | 1..1 | Het conceptschema waartoe dit concept behoort. |
| **topConceptOf** | `skos:topConceptOf` | `skos:ConceptScheme` | 0..1 | Geeft aan of dit een topconcept is. |
| **deprecated** | `owl:deprecated` | `xsd:boolean` | 0..1 | Geeft aan of het concept verouderd is. |
| **geldigTot** | `csor:geldigTot` | `xsd:date` | 0..1 | De datum tot wanneer het concept geldig is. |

## Voorbeelden

Een overzicht van voorbeelden voor deze codelijst is te vinden op de [voorbeelden pagina](../examples/natuurkundigedimensie.md).

## RDF Data

De brondata is beschikbaar in verschillende formaten:
- [Turtle](../../codelijst-project/output/be/vlaanderen/omgeving/data/id/conceptscheme/csor/natuurkundigedimensie/natuurkundigedimensie.ttl)

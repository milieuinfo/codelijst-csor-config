# Drager

Een drager beschrijft een medium waarin een variabele geobserveerd kan worden.

## Overzicht diagram

```mermaid
classDiagram
    class Drager {
        +skos:prefLabel prefLabel [1..1]
        +skos:definition definition [0..1]
        +skos:inScheme inScheme [1..1]
        +skos:topConceptOf topConceptOf [1..1]
        +owl:deprecated deprecated [0..1]
        +csor:geldigTot geldigTot [0..1]
    }
```

## Eigenschappen

De klasse `csor:Drager` heeft de volgende eigenschappen:

| Eigenschap | URI | Type | Cardinaliteit | Beschrijving |
| :--- | :--- | :--- | :--- | :--- |
| **prefLabel** | `skos:prefLabel` | `xsd:string` | 1..1 | De voorkeursnaam van de drager. |
| **definition** | `skos:definition` | `xsd:string` | 0..1 | Een tekstuele definitie van de drager. |
| **inScheme** | `skos:inScheme` | `skos:ConceptScheme` | 1..1 | Het conceptschema waartoe de drager behoort. |
| **topConceptOf** | `skos:topConceptOf` | `skos:ConceptScheme` | 0..1 | Geeft aan of dit een topconcept is. |
| **deprecated** | `owl:deprecated` | `xsd:boolean` | 0..1 | Geeft aan of de drager verouderd is. |
| **geldigTot** | `csor:geldigTot` | `xsd:date` | 0..1 | De datum tot wanneer de drager geldig is. |

## Voorbeelden

Een overzicht van voorbeelden voor deze codelijst is te vinden op de [voorbeelden pagina](../examples/drager.md).

## RDF Data

De brondata is beschikbaar in verschillende formaten:
- [Turtle](../../codelijst-project/output/be/vlaanderen/omgeving/data/id/conceptscheme/csor/drager/drager.ttl)
- [JSON-LD](../../codelijst-project/output/be/vlaanderen/omgeving/data/id/conceptscheme/csor/drager/drager.jsonld)

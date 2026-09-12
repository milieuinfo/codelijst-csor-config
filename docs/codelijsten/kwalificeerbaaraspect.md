# Kwalificeerbaar Aspect

Een kwalificeerbaar aspect drukt uit dat de waarde die aan een observatie kan worden toegekend, beperkt is tot classificaties opgenomen in een elders gepubliceerde lijst.

## Overzicht diagram

```mermaid
classDiagram
    class KwalificeerbaarAspect {
        +skos:prefLabel prefLabel [1..1]
        +skos:definition definition [0..1]
        +skos:notation notation [0..1]
        +csor:symbool symbool [0..1]
        +csor:heeftResultaattype resultaattype [0..1]
        +csor:classificatielijst classificatielijst [0..1]
        +skos:inScheme inScheme [1..1]
        +skos:topConceptOf topConceptOf [0..1]
        +owl:deprecated deprecated [0..1]
        +csor:geldigTot geldigTot [0..1]
    }
```

## Eigenschappen

De klasse `csor:KwalificeerbaarAspect` heeft de volgende eigenschappen:

| Eigenschap | URI | Type | Cardinaliteit | Beschrijving |
| :--- | :--- | :--- | :--- | :--- |
| **prefLabel** | `skos:prefLabel` | `xsd:string` | 1..1 | De voorkeursnaam van het kwalificeerbaar aspect. |
| **definition** | `skos:definition` | `xsd:string` | 0..1 | Een tekstuele definitie. |
| **notation** | `skos:notation` | `xsd:string` | 0..1 | Een unieke notatie. |
| **symbool** | `csor:symbool` | `xsd:string` | 0..1 | Symbool dat gebruikt wordt om het concept weer te geven. |
| **resultaattype** | `csor:heeftResultaattype` | `csor:ResultaatType` | 0..1 | De link met het resultaattype. |
| **classificatielijst** | `csor:classificatielijst` | `rdfs:Resource` | 0..1 | De referentie naar een codelijst met geldige classificatiewaarden. |
| **inScheme** | `skos:inScheme` | `skos:ConceptScheme` | 1..1 | Het conceptschema waartoe dit concept behoort. |
| **topConceptOf** | `skos:topConceptOf` | `skos:ConceptScheme` | 0..1 | Geeft aan of dit een topconcept is. |
| **deprecated** | `owl:deprecated` | `xsd:boolean` | 0..1 | Geeft aan of het concept verouderd is. |
| **geldigTot** | `csor:geldigTot` | `xsd:date` | 0..1 | De datum tot wanneer het concept geldig is. |

## Voorbeelden

Een overzicht van voorbeelden voor deze codelijst is te vinden op de [voorbeelden pagina](../examples/kwalificeerbaaraspect.md).

## RDF Data

De brondata is beschikbaar in verschillende formaten:
- [Turtle](../../codelijst-project/output/be/vlaanderen/omgeving/data/id/conceptscheme/csor/kwalificeerbaaraspect/kwalificeerbaaraspect.ttl)

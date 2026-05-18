# codelijst-csor-config

Configuratiebestanden voor de transformatiepipelines van het **Chemische Stoffen en Omgevingsparameters-Register (CSOR)**.

## Doel

Deze repository bevat de bronbestanden en configuratie die worden gebruikt om CSOR-codelijsten en conceptschema's te publiceren als linked data. De bestanden vormen de invoer voor transformatiepipelines die de gegevens omzetten naar RDF/SKOS en publiceren onder de Vlaamse datanaamruimte.

## Structuur

```
src/main/resources/
└── be/vlaanderen/omgeving/data/id/conceptscheme/csor/
    └── ...   ← configuratie- en bronbestanden per conceptschema
```

De padstructuur weerspiegelt de linked-data URI-basis:
`https://data.vlaanderen.be/id/conceptscheme/csor/...`

## Build

Het project gebruikt Maven als bouwsysteem.

```bash
mvn package
```

## Context

CSOR is een register van de Vlaamse overheid (Departement Omgeving) dat chemische stoffen en omgevingsparameters standaardiseert voor gebruik in milieu-rapportering en -regelgeving.

## Licentie

Zie [LICENSE](LICENSE).

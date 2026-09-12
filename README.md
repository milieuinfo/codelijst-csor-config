# CSO Register: Documentatie & Configuratie

CSOR is een register van de Vlaamse overheid (Departement Omgeving) dat chemische stoffen en omgevingsparameters standaardiseert voor gebruik in milieu-rapportering en -regelgeving.
Dit project bevat zowel de inhoudelijke documentatie als de technische configuratie voor het **Chemische Stoffen en Omgevingsparameters-Register (CSOR)**.

## 1. Documentatie

Een gedetailleerd overzicht van de codelijsten, hun onderlinge relaties en de gebruikte ontologie is te vinden in de [documentatie](docs/index.md).

## 3. Overzicht repositories

Alle repositories van dit project bevinden zich in de milieuinfo organisatie op GitHub:

| Codelijst / Onderdeel | GitHub Repository |
| :--- | :--- |
| **CSOR Config** (deze repo) | [codelijst-csor-config](https://github.com/milieuinfo/codelijst-csor-config) |
| **Variabele** | [codelijst-variabele](https://github.com/milieuinfo/codelijst-variabele) |
| **Drager** | [codelijst-drager](https://github.com/milieuinfo/codelijst-drager) |
| **Soortwaardebepaling** | [codelijst-soortwaardebepaling](https://github.com/milieuinfo/codelijst-soortwaardebepaling) |
| **Parameter** | [codelijst-parameter](https://github.com/milieuinfo/codelijst-parameter) |
| **Parameter Aspect** | [codelijst-parameteraspect](https://github.com/milieuinfo/codelijst-parameteraspect) |
| **Kwantificeerbaar Aspect** | [codelijst-kwantificeerbaaraspect](https://github.com/milieuinfo/codelijst-kwantificeerbaaraspect) |
| **Kwalificeerbaar Aspect** | [codelijst-kwalificeerbaaraspect](https://github.com/milieuinfo/codelijst-kwalificeerbaaraspect) |
| **Natuurkundige Dimensie** | [codelijst-natuurkundigedimensie](https://github.com/milieuinfo/codelijst-natuurkundigedimensie) |
| **Eenheid** | [codelijst-eenheid](https://github.com/milieuinfo/codelijst-eenheid) |


## 2. Configuratie

De bronbestanden en configuratie die worden gebruikt om CSOR-codelijsten en conceptschema's te publiceren als linked data. De bestanden vormen de invoer voor transformatiepipelines die de gegevens omzetten naar RDF/SKOS en publiceren onder de Vlaamse datanaamruimte.

### Structuur
De padstructuur weerspiegelt de linked-data URI-basis: `https://data.vlaanderen.be/id/conceptscheme/csor/...`

```
src/main/resources/
└── be/vlaanderen/omgeving/data/id/conceptscheme/csor/
    └── ...   ← configuratie- en bronbestanden per conceptschema
```

### Build
Het project gebruikt Maven als bouwsysteem.

```bash
mvn package
```

## Licentie

Zie [LICENSE](LICENSE).

## Notities

- model wijzigingen = major
- config bestanden = minor
- editoriale doc wijzigingen = patch



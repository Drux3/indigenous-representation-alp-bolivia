# Indigenous Representation in the Bolivian Plurinational Legislative Assembly (2010–2020)

**Author:** Andrés Huanca Rodrigues

## Overview

This repository provides open datasets and descriptive tables on Indigenous representation in the Bolivian Plurinational Legislative Assembly (Asamblea Legislativa Plurinacional, ALP) during the first two legislative periods of the Plurinational State of Bolivia (2010–2015 and 2015–2020).

The datasets document the political, social, gender, and ethnic characteristics of members of the Legislative Assembly. They are intended to support research, comparative analysis, and further investigation into Indigenous political representation in Bolivia.

## Descriptive Tables

The supplementary descriptive tables accompanying this research are available as an HTML document that can be viewed directly in a web browser.

[**View Descriptive Tables (HTML)**](https://drux3.github.io/indigenous-representation-alp-bolivia/)

The document presents tables on:

- Indigenous representation by legislative chamber.
- Indigenous representation by political party.
- Indigenous representation by electoral constituency.
- Indigenous representation by social organization and gender.
- Representation by Indigenous nation and people.
- Indigenous representation in positions of legislative power.

## Repository Structure

```text
indigenous-representation-alp-bolivia/
│
├── data/
│   ├── ALP_2010_2015.csv
│   └── ALP_2015_2020.csv
│
├── tables/
│   ├── Indigenous Representation: Descriptive Tables by Political, Social and Ethnic Characteristics (2010–2020).Rmd
│   └── index.html
│
├── documentation/
│   └── codebook.md
│
├── docs/
│   └── index.html
│
├── README.md
└── .gitignore
```

## Data

The repository contains two CSV datasets:

| File | Legislative period |
|---|---|
| `ALP_2010_2015.csv` | 2010–2015 |
| `ALP_2015_2020.csv` | 2015–2020 |

Both datasets contain information on legislators and their political, social, and demographic characteristics.

### Variables

| Variable | Description |
|---|---|
| `NOMBRE` | Legislator's name |
| `CAMARA` | Legislative chamber |
| `DEPARTAMENTO` | Department represented |
| `PARTIDO` | Political party |
| `ORG_SOC` | Social organization |
| `PROFESION` | Profession or occupation |
| `INDIGENA` | Indigenous identification (1 = Yes; 0 = No) |
| `GENERO` | Gender |
| `NACIMIENTO` | Place of birth |
| `CIRCUNS` | Type of electoral constituency |
| `ETNICIDAD` | Specific ethnic identification |

For further information about the variables, consult the [Codebook](documentation/codebook.md).

## Documentation and Tables

The `documentation/` directory contains the codebook describing the variables included in the datasets.

The `tables/` directory contains the R Markdown source document used to generate the descriptive tables and its HTML version.

The `docs/` directory contains the HTML document published through GitHub Pages, allowing users to consult the tables directly online.

## Research Context

This repository is associated with the research project:

*¿Presentes? Representación descriptiva de los pueblos indígenas en la Asamblea Legislativa Plurinacional de Bolivia (2010–2020)* (**Manuscript Under Review**).

The research examines descriptive Indigenous representation in the Bolivian Plurinational Legislative Assembly during its first ten years, combining quantitative descriptive analysis with a broader discussion of political representation.

## Author

**Andrés Huanca Rodrigues**

Social Scientist.

Research interests include Indigenous political representation, political anthropology, Bolivian politics, and quantitative and qualitative methods in social research.

## Contact and Citation

If you use these datasets or descriptive tables in academic research, please acknowledge this repository and its author.

A formal citation and DOI will be added when a permanent archival version of the repository is available.

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.24089514.svg)](https://doi.org/10.5281/zenodo.24089514)

# Data for "UAV mission planning for large-scale scanning of GNSS-degraded environments: a systematic review"

This repository contains the search, screening, eligibility and coding data of the systematic review *UAV mission planning for large-scale scanning of GNSS-degraded environments: a systematic review* (Terol, Gomez-Gasquet and Boza; manuscript submitted to *Robotics and Autonomous Systems*). The review follows the PRISMA 2020 statement.

## Contents

All tables are provided as UTF-8 CSV files in `data/` and combined in `data/supplementary_material.xlsx`.

| File | Content |
|---|---|
| `S1_search_strings.csv` | Scopus query chains (F1–F10, G1–G2, U1–U2), the pilot search F7 (not counted in the flow diagram) and the citation-chasing queries (G3, B1), with number of results and date. All database chains use the filters `DOCTYPE(ar OR re) AND SRCTYPE(j) AND PUBYEAR > 2014 AND LANGUAGE(english)`. |
| `S2_title_abstract_screening.csv` | The 751 unique records screened on title and abstract, with decision and exclusion reason. |
| `S2b_pilot_search_F7.csv` | The 65 records of the pilot search F7 and their screening. |
| `S3_full_text_eligibility.csv` | The 288 records pre-selected for eligibility assessment: whether they were assessed on full text or on title/abstract, decision, eligibility criterion (E1–E6, location-routing rule, positioning rule), reason and a short supporting quotation with page. |
| `S4_coding_final_set.csv` | Coding of the 111 articles of the final set along the dimensions of the review codebook (thematic block, problem, formulation, method, fleet, reported scale, validation, environment, GNSS, energy or bases, integrated location-routing, contribution). |

## Notes

- Bibliographic metadata and citation counts were taken from Scopus on 6 November 2026. Abstracts are not redistributed.
- Short quotations in `S3` are reproduced for the sole purpose of documenting eligibility decisions; copyright remains with the original publishers.
- The eligibility criteria E1–E6 are defined in Section 3 of the article.

## Licence

The data are released under the [Creative Commons Attribution 4.0 International licence](LICENSE) (CC BY 4.0).

## How to cite

Please cite the article and this dataset. Citation metadata are given in `CITATION.cff`; the concept DOI [10.5281/zenodo.24089514](https://doi.org/10.5281/zenodo.24089514) always resolves to the latest version (v1.0: [10.5281/zenodo.24089515](https://doi.org/10.5281/zenodo.24089515)).

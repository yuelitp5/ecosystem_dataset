# Digital Educational Ecosystem Assessment — Raw Input Dataset

This repository publishes the **raw input tables** used in the paper on assessing the maturity / development priorities of a university digital educational ecosystem.

The goal is to make the study reproducible: the data here correspond to the original tabular inputs (indicator catalog, indicator scores, intermediate aggregated tables, and overall outputs that are computed from those inputs).

> **Important:** This repository contains **only source data** (CSV). No code or derived analytics are included.

---

## Maintainer

I am **Alex Petrov**, a research software engineer working on reproducible data pipelines for higher‑education digital transformation studies.  
My role in this project was to standardize the study’s input tables, export them into portable formats, and document the dataset structure for public release.

Contact: `alex.petrov.dataset@proton.me`

---

## Repository structure

```
data/
  raw/
    indicator_catalog.csv
    indicator_scores.csv
    table_5_1_mi_ci.csv
    table_5_2_questionnaire_summary.csv
    table_5_3_priorities.csv
    overall_results_and_stability.csv
DATA_DICTIONARY.md
CITATION.cff
LICENSE
```

All CSV files are **UTF‑8** encoded and use a comma `,` as separator.

---

## Files overview

- **`indicator_catalog.csv`** — master list of indicators (IDs, grouping, textual descriptions, metadata).
- **`indicator_scores.csv`** — indicator-level scores used as the primary assessment input.
- **`table_5_1_mi_ci.csv`** — aggregated values used in Table 5.1 of the paper (Mi / Ci-type summaries).
- **`table_5_2_questionnaire_summary.csv`** — questionnaire / expert survey summary used in Table 5.2.
- **`table_5_3_priorities.csv`** — priorities / weights / ordering used in Table 5.3.
- **`overall_results_and_stability.csv`** — final summary values and stability/robustness flags (as reported).

A full column-level description (as-is) and checksums are provided in **`DATA_DICTIONARY.md`**.

---

## Data provenance and privacy

The dataset is released as a **research artifact**. It contains **no personal data** (no names, emails, phone numbers, or identifiers of individual respondents).  
If you plan to combine this dataset with other sources, ensure that you comply with your institution’s privacy and research ethics requirements.

---

## Recommended citation

See **`CITATION.cff`** for the preferred citation format.

---

## License

This dataset is provided under the license specified in **`LICENSE`**.

---

## Versioning

- Dataset release: **v1.0**
- Release date: **2026-02-28**

# Digital Educational Ecosystem Assessment — Raw Input Dataset

Raw CSV data for a study on university digital educational ecosystem maturity and development priorities.

The repository is published as a reproducible research artifact and contains only source tables (no analysis code, no derived visualizations).

## At a glance

- **Type:** research dataset
- **Format:** CSV (UTF-8, comma-separated)
- **Release:** v1.0 (2026-02-28)
- **License:** CC BY 4.0

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

CHECKSUMS.sha256
DATA_DICTIONARY.md
CITATION.cff
LICENSE
README.md
```

## Dataset files

- **`indicator_catalog.csv`** — indicator registry (IDs, domains, names, evidence source, weight).
- **`indicator_scores.csv`** — indicator-level scoring input used in the assessment.
- **`table_5_1_mi_ci.csv`** — aggregated domain metrics used in Table 5.1.
- **`table_5_2_questionnaire_summary.csv`** — questionnaire summary statistics used in Table 5.2.
- **`table_5_3_priorities.csv`** — ranked priorities and gap-to-target values used in Table 5.3.
- **`overall_results_and_stability.csv`** — final summarized outputs and stability-related values.

Column-level details are documented in **`DATA_DICTIONARY.md`**.

## Integrity check

To verify file integrity against published checksums:

```powershell
cd ecosystem_dataset
Get-FileHash .\data\raw\*.csv -Algorithm SHA256
```

Reference hashes are stored in **`CHECKSUMS.sha256`**.

## Data use and reproducibility

- The dataset contains no direct personal identifiers.
- Reuse is allowed under the project license.
- For reproducible workflows, keep raw files unchanged and version derived outputs separately.

## Citation

Use the citation metadata from **`CITATION.cff`**.

## Maintainer

**Alex Petrov**  
Contact: `alex.petrov.dataset@proton.me`

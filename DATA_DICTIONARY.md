# Data dictionary
This repository contains **raw input data** used in the accompanying research paper on digital educational ecosystem assessment.
All files are provided in CSV format (UTF‑8, comma-separated).
## `indicator_catalog.csv`
- Rows: 48
- Columns: 6
| Column | Type (pandas) | Description |
|---|---|---|
| domain_code | object | See column name (as provided in the original instrument). |
| domain_name | object | See column name (as provided in the original instrument). |
| indicator_id | object | See column name (as provided in the original instrument). |
| indicator_name | object | See column name (as provided in the original instrument). |
| evidence_source | object | See column name (as provided in the original instrument). |
| weight | int64 | See column name (as provided in the original instrument). |

## `indicator_scores.csv`
- Rows: 48
- Columns: 7
| Column | Type (pandas) | Description |
|---|---|---|
| domain_code | object | See column name (as provided in the original instrument). |
| domain_name | object | See column name (as provided in the original instrument). |
| indicator_id | object | See column name (as provided in the original instrument). |
| indicator_name | object | See column name (as provided in the original instrument). |
| score_0_4 | float64 | See column name (as provided in the original instrument). |
| weight | int64 | See column name (as provided in the original instrument). |
| evidence_source | object | See column name (as provided in the original instrument). |

## `table_5_1_mi_ci.csv`
- Rows: 6
- Columns: 4
| Column | Type (pandas) | Description |
|---|---|---|
| Домен | object | See column name (as provided in the original instrument). |
| Наименование домена | object | See column name (as provided in the original instrument). |
| M_i (0..1) | float64 | See column name (as provided in the original instrument). |
| C_i (полнота) | float64 | See column name (as provided in the original instrument). |

## `table_5_2_questionnaire_summary.csv`
- Rows: 6
- Columns: 4
| Column | Type (pandas) | Description |
|---|---|---|
| Домен | object | See column name (as provided in the original instrument). |
| Анкета: среднее (1..5) | float64 | See column name (as provided in the original instrument). |
| Анкета: медиана | int64 | See column name (as provided in the original instrument). |
| n (валидных ответов) | int64 | See column name (as provided in the original instrument). |

## `table_5_3_priorities.csv`
- Rows: 12
- Columns: 6
| Column | Type (pandas) | Description |
|---|---|---|
| domain_code | object | See column name (as provided in the original instrument). |
| indicator_id | object | See column name (as provided in the original instrument). |
| indicator_name | object | See column name (as provided in the original instrument). |
| score_0_4 | int64 | See column name (as provided in the original instrument). |
| gap_to_target | float64 | See column name (as provided in the original instrument). |
| evidence_source | object | See column name (as provided in the original instrument). |

## `overall_results_and_stability.csv`
- Rows: 12
- Columns: 2
| Column | Type (pandas) | Description |
|---|---|---|
| Показатель | object | See column name (as provided in the original instrument). |
| Значение | object | See column name (as provided in the original instrument). |

## Checksums (SHA‑256)

| File | SHA‑256 |
|---|---|
| `data/raw/indicator_catalog.csv` | `e5e19cdc1a28bb758cae8d6ec3d2a9fcef22949ccd23d3f59aeaf3e31afb4fb8` |
| `data/raw/indicator_scores.csv` | `bca174d7dfe80ec6bf6a7980d75f38a83b0b2e37fc5c6885c8c22f036b3e0574` |
| `data/raw/table_5_1_mi_ci.csv` | `cd6c6abd65de020c634c34f856686300a73f9d51e86681205b931698e0444580` |
| `data/raw/table_5_2_questionnaire_summary.csv` | `f02554d19afcac4ab6852f0c6d4c78adb34421bbc886b96dbe81c4532eee1a18` |
| `data/raw/table_5_3_priorities.csv` | `098ee33b196a69e8e7662db9153c4547c84cff81af7fa91df41aef5ad113330d` |
| `data/raw/overall_results_and_stability.csv` | `11b75ca5197d57b883632cdca8a5cca188d790c68cd097aa4a0a24dabee74b13` |

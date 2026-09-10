# Machine Learning for Cybersecurity

A three-part academic sequence from preprocessing/visualization to classical ML and deep-learning malware classification.

> **Academic context:** Completed as part of Computer Science / Cybersecurity engineering coursework at Amar Telidji University, Laghouat (2025-2026). This repository is intended as a technical portfolio of controlled university lab work.

## What this repository demonstrates

- Prepared and visualized an SMS spam dataset with cleaning, encoding, feature engineering, scaling, and class-distribution analysis.
- Compared KNN and RBF-SVM for malware/goodware classification using API-call sequence features.
- Identified severe class imbalance and analyzed why headline accuracy can be misleading.
- Compared multiple MLP architectures, including deeper and regularized networks, against classical ML baselines.

## Tools & technologies

`Python` · `pandas` · `scikit-learn` · `KNN` · `SVM` · `MLP` · `StandardScaler` · `Kaggle datasets` · `Data visualization`

## Included lab reports

| # | Lab | Report |
|---:|---|---|
| 1 | 01 Data Preprocessing And Visualization | [`docs/01-data-preprocessing-and-visualization.md`](docs/01-data-preprocessing-and-visualization.md) |
| 2 | 02 Malware Classification Knn Svm | [`docs/02-malware-classification-knn-svm.md`](docs/02-malware-classification-knn-svm.md) |
| 3 | 03 Malware Classification Mlp | [`docs/03-malware-classification-mlp.md`](docs/03-malware-classification-mlp.md) |

## Repository structure

```text
.
├── README.md
├── docs/        # GitHub text editions of the academic lab reports
└── src/         # Add original code/configs/scripts here when available
```

## Notes

The reports document the work actually completed in the university labs. For GitHub portability, the reports are included as searchable Markdown text editions; the original PDF screenshots and figures are not embedded in these conversions. The `src/` directory is intentionally left as a place to add original source code, configuration files, packet captures, notebooks, or scripts where those artifacts are available. No source code has been fabricated from the reports.

## Responsible use

Security techniques in this repository were performed in controlled academic environments. Use attack and exploitation techniques only on systems you own or have explicit authorization to test.

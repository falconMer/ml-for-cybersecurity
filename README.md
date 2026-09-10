# Machine Learning for Cybersecurity

A three-part academic sequence from data preprocessing and visualization to classical ML and deep-learning malware classification.

> **Academic context:** Computer Science / Cybersecurity engineering coursework at Amar Telidji University, Laghouat (2025-2026).

## What this repository demonstrates

- Prepared and visualized an SMS spam dataset with cleaning, label encoding, feature engineering, outlier handling, scaling, and class-distribution analysis.
- Compared KNN and RBF-SVM for malware/goodware classification using API-call sequence features.
- Identified severe class imbalance and explained why >98% headline accuracy was misleading without minority-class metrics.
- Compared multiple MLP architectures, including a deeper network and a Dropout/SGD regularized model, against the classical ML baselines.

## Tools & technologies

`Python` · `pandas` · `scikit-learn` · `KNN` · `SVM` · `MLP` · `StandardScaler` · `Kaggle datasets`

## Included academic work

| # | Assignment | Portfolio write-up |
|---:|---|---|
| 1 | Data Preprocessing & Visualization | [`docs/01-data-preprocessing-and-visualization.md`](docs/01-data-preprocessing-and-visualization.md) |
| 2 | Malware Classification with KNN & SVM | [`docs/02-malware-classification-knn-svm.md`](docs/02-malware-classification-knn-svm.md) |
| 3 | Malware Classification with MLP | [`docs/03-malware-classification-mlp.md`](docs/03-malware-classification-mlp.md) |

## Evidence policy

This repository uses only the supplied academic reports and their documented experiments/results. No notebooks, datasets, charts, source files, or additional model runs are claimed unless they were present in those reports. The write-ups keep the class-imbalance limitations visible rather than presenting accuracy numbers without context.

## Key result

The strongest reported MLP configuration reached 99.10% accuracy and 99.95% malware recall, but the project explicitly treats class imbalance and false positives as the more important production concern and identifies class weighting/oversampling as future work.

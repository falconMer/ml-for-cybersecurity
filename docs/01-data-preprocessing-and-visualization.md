# 01 Data Preprocessing And Visualization

[← Repository overview](../README.md) · [Original PDF report](01-data-preprocessing-and-visualization.pdf)

> Portfolio text edition derived from the original university lab report provided by Smail Mersad. The original report contains screenshots/figures; this Markdown edition preserves the written technical record without inventing additional evidence or assets.

**Academic context:** Amar Telidji University, Computer Science / Cybersecurity Engineering, 2025-2026.

---

## Report page 2

```text
HEAD: First 5–10 rows of the raw dataset

3. Preprocessing Steps:

Steps performed:

1. Column Cleaning
Removed unused “Unnamed: X” columns and kept only v1 and v2.

2. Renaming Columns
v1 → label
v2 → text

3. Handling Missing Values
Dropped rows with missing text.

4. Removing Duplicates
Removed exact duplicate messages to avoid bias in modeling.

5. Label Encoding
ham → 0
spam → 1
```

---

## Report page 3

```text
6. Feature Engineering
Created text_len = number of characters in the message.

7. Outlier Removal
Removed extremely long messages (>1000 characters).

8. Scaling
Applied StandardScaler to numerical features.

Several visualizations were produced to assess dataset readiness and understand distribution.
```

---

## Report pages 4-5

```text
Class balance: the dataset is imbalanced, with ham messages dominating.
Text length: most messages are short, with a long tail after cleaning.
A numerical-feature heatmap showed a mild relationship between text length and spam label.
The top-10 token visualization was used to inspect vocabulary and token-cleaning needs.
```

---

## Report page 6

```text
Summary:
The SMS Spam dataset was loaded, inspected, and cleaned. Unnecessary columns were removed,
missing entries and duplicates were handled, labels were encoded numerically, and a basic
text-length feature was engineered. Outliers were removed and numeric features were scaled.

The visualizations confirmed strong class imbalance, short-message distribution typical of
SMS, clean feature correlations, and clear vocabulary patterns. The dataset was considered
ready for baseline machine-learning models, with class imbalance identified as the main
modeling consideration.
```

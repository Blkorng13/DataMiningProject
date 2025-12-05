# README.md  
## Mushroom Overload — Code & Project File Overview

This directory contains all notebooks, reports, and presentation materials used for the Mushroom Overload data-mining project. Each notebook corresponds to a specific analysis method described in the final report.

---

## Notebooks

| File | Description |
|------|-------------|
| **EDA_LR_NB_code.ipynb** | Exploratory Data Analysis (EDA), logistic regression baseline + tuned model, and Naive Bayes classification. Includes preprocessing, correlation checks, and model evaluation. |
| **decisiontreecode.ipynb** | Builds and evaluates a Decision Tree classifier using OrdinalEncoder preprocessing. Includes accuracy, classification report, and interpretation. |
| **randomforestcode.ipynb** | Trains a Random Forest classifier, generates feature importance plots, confusion matrix, and ROC/AUC metrics. |
| **chisquarecode.ipynb** | Computes Chi-square statistics on categorical features and produces a ranked list of strongest predictors. |
| **cramerheatmapcode.ipynb** | Computes Cramér’s V correlation matrix and creates the categorical heatmap. |
| **FPGrowthcode.ipynb** | Runs FP-Growth association rule mining on a stratified sample. Generates frequent itemsets and high-confidence rules. |
| **kmodeclustercode.ipynb** | Performs K-Modes clustering, interprets centroids, and evaluates cluster purity relative to toxicity labels. |

---

## 📄 Reports

| File | Description |
|------|-------------|
| **finalreport.pdf** | Full ACM-style final report (LaTeX formatted). |
| **final report_regularwordversion.pdf** | Standard Word-style version of the report for readability. |

---

## 🎤 Presentation Materials

| File | Description |
|------|-------------|
| **presentation_slides.pdf** *(or .pptx — depending on upload)* | Slide deck summarizing project workflow, methods, and results. |
| **presentation_video.mp4** | Recorded project presentation video. |

---

## ▶️ How to Run the Notebooks

1. Ensure **mushroom_compact.parquet** is available.  
2. Install required packages:
   ```bash
   pip install pandas numpy scikit-learn kmodes mlxtend matplotlib seaborn fastparquet

# Genetic Variant Classification

## Project Overview

This project focuses on the classification of genetic variants using machine learning techniques. The dataset, sourced from the ClinVar database, contains genomic data with conflicting interpretations of pathogenicity. By preprocessing and modeling this data, the aim is to predict a discretized version of the BLOSUM62 score, which is widely used in bioinformatics to assess the impact of amino acid substitutions.

## Technical Highlights

* **Dataset Source**: [Kaggle - ClinVar Conflicting Variants](https://www.kaggle.com/datasets/kevinarvai/clinvar-conflicting)
* **EDA**: Summary statistics, missing value analysis, distribution plots, boxplots, and correlation heatmaps
* **Preprocessing**:

  * Null value imputation
  * Label encoding for categorical variables
  * Feature selection by dropping low-impact or highly sparse columns
* **Modeling**:

  * Algorithms used: Logistic Regression, Ridge Classifier, Random Forest, XGBoost, AdaBoost, Gradient Boosting, Bagging, Decision Tree, and SVC
  * Binning of continuous BLOSUM62 scores into three discrete classes
  * Evaluation using classification report and confusion matrix

## Purpose and Applications

* **Biomedical Research**: Assist researchers in interpreting uncertain genetic variants.
* **Clinical Genetics**: Support geneticists in assessing the pathogenic potential of mutations.
* **AI in Genomics**: Demonstrates the power of machine learning in classifying complex biological data.

## Installation

 **Clone the repository**:

   ```bash
   git clone https://github.com/BhaveshBhakta/Genetic-Variant-Classification-Using-ML.git
   cd Genetic-Variant-Classification-Using-ML
   ```
y
   ```

## Collaboration

Contributions are welcome. If you'd like to improve model performance, enhance preprocessing, or add new visualizations, feel free to:

* Fork the repository
* Create a new branch
* Submit a pull request with detailed description

# Gene Expression Cancer Classification

A machine learning project exploring how gene expression data can be used to classify five types of cancer.

## Overview

This project investigates the use of gene expression data to distinguish between five cancer types using Logistic Regression. It also explores how reducing the number of genes affects classification accuracy, helping identify how much predictive information is retained when fewer genes are used.

## Dataset

The project uses the Gene Expression Cancer RNA-Seq dataset from the UCI Machine Learning Repository.

The dataset contains gene expression measurements from cancer samples across five cancer types.

The dataset is not included in this repository. Please refer to the original source for access and usage conditions.

## Methodology

- Process and prepare the gene expression data.
- Train a Logistic Regression classifier.
- Evaluate classification performance using a stratified train-test split and cross-validation.
- Rank genes by their importance to the model.
- Compare classification accuracy using different numbers of the highest-ranked genes.

## Technologies

- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Matplotlib

## Results

The project examines how classification accuracy changes as the number of genes used by the model decreases.

The final graph visualizes this relationship, while the notebook contains the experiments, evaluation results, and analysis.

![Final classification results](results/final_graph.png)

## Repository Contents

- `cancer_classification.ipynb` — Main notebook containing the code, experiments, and analysis.
- `research_log.md` — Research notes documenting the experimental process and findings.
- `results/final_graph.png` — Final results graph.

## Running the Project

1. Download or clone this repository.
2. Install the required Python libraries.
3. Obtain the dataset from its original source.
4. Open the notebook in Jupyter Notebook or JupyterLab.
5. Update the dataset path if necessary and run the cells.

Install the main dependencies with:

```bash
pip install pandas numpy scikit-learn matplotlib jupyter
```

## Purpose

This project explores the relationship between gene expression, machine learning, and cancer classification, with a particular focus on how feature selection influences predictive performance.

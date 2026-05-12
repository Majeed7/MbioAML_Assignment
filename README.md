# MbioAML_Assignment

Assignment repository for **Advanced Machine Learning for the Life Sciences (MBioAML)** focused on explainable AI for extracellular vesicle (EV) protein sorting.

## Overview

This repository contains:

- `Assignment1_LIME_SHAP_EV_Proteins.ipynb`: the main assignment notebook
- `train:test/training_remaining.csv`: training dataset
- `train:test/test_Dhondt2021.csv`: held-out external test set used in the notebook
- `train:test/test_Karimi2018.csv`: additional external test set
- `train:test/test_MartinezGreene2020.csv`: additional external test set
- `J of Extracellular Bio - 2024 - Waury - Proteome encoded determinants of protein sorting into extracellular vesicles.pdf`: reference paper

## Assignment Focus

The notebook walks through:

1. Loading and inspecting EV protein data
2. Training baseline classifiers
3. Exploring global explanation methods
4. Comparing local explanation methods with LIME and SHAP
5. Interpreting model behavior in a biological context

## Running the Notebook

The notebook is written for **Google Colab**.

1. Open `Assignment1_LIME_SHAP_EV_Proteins.ipynb` in Colab.
2. Run the setup cells to install dependencies.
3. Run the data-loading cell in Section 1.

Section 1 is configured to load the main CSV files directly from this GitHub repository.

## Repository Structure

```text
MbioAML_Assignment/
├── Assignment1_LIME_SHAP_EV_Proteins.ipynb
├── J of Extracellular Bio - 2024 - Waury - Proteome encoded determinants of protein sorting into extracellular vesicles.pdf
├── README.md
└── train:test/
    ├── test_Dhondt2021.csv
    ├── test_Karimi2018.csv
    ├── test_MartinezGreene2020.csv
    └── training_remaining.csv
```

## Notes

- The notebook currently loads the training set and the `Dhondt2021` test set directly from GitHub.
- The folder name `train:test` is preserved from the source files. Git supports it, but it may be inconvenient on some systems, especially Windows.

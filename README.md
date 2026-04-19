# Data Exploration Project: Used Cars Dataset

**Dataset Source:** [Kaggle - Craigslist Cars and Trucks Data](https://www.kaggle.com/datasets/austinreese/craigslist-carstrucks-data)

## Core Objective
Perform a complete data science pipeline—including data acquisition, Exploratory Data Analysis (EDA), baseline modeling, and model optimization—on the Used Cars dataset.

## Project Structure & Deliverables
All project outputs must be organized strictly into the following structure:

- **Source Code & Notebooks (`src/`)**:
  - `src/download.ipynb`: Data downloand and acquisition.
  - `src/eda.ipynb`: Detailed Exploratory Data Analysis, data cleaning, and feature engineering.
  - *Modeling Notebooks*: Must properly execute an appropriate dummy baseline, a simple `scikit-learn` baseline, and trained/optimized models (e.g., utilizing `optuna`).
- **Final Report (`doc/`)**:
  - `doc/main.typ`: The final project report, written exclusively in Typst.
  - `doc/refs.bib`: Citations and references for the report.

## Guidelines
Do not use `pip`, use `uv` instead.

The report should NOT "describe" the code. It should instead mention the methods and strategies applied and why they were chosen.

## Additional Notes

- use sklearn pipeline
- use optuna
- use isolation forest

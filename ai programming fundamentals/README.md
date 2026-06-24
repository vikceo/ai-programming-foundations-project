# Wine Quality Data Workflow

## Project Description

A complete, reproducible data workflow built on the UCI Wine Quality dataset. The notebook loads and combines the red and white wine data, cleans and de-duplicates it, explores it with reusable functions, and visualizes the relationships between chemical properties and expert quality scores. It establishes a clean analytical foundation for future machine learning work.

## What I Built

- `data_workflow.ipynb` — a Jupyter Notebook with the full workflow: load, clean, EDA, visualizations, and a summary.
- Reusable, documented functions for data cleaning and exploratory analysis.
- Four labeled visualizations created with Matplotlib and Seaborn.

## Dataset

Wine Quality (red + white) — UCI Machine Learning Repository: https://archive.ics.uci.edu/dataset/186/wine+quality

## How to Run the Project

1. Install dependencies:

   ```
   pip install -r requirements.txt
   ```

   (To regenerate the dependency list after adding packages, run `pip freeze > requirements.txt`.)

2. Open and run the notebook:

   ```
   jupyter notebook data_workflow.ipynb
   ```

   Then run all cells from top to bottom (Cell → Run All). The data files are in the `data/` folder, so the notebook runs without any extra setup.

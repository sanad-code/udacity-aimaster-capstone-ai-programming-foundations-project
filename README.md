# Steel Production Data Analysis — Udacity AI Master Capstone

This project analyzes steel production data to identify key factors affecting energy consumption, quality indicators, and production efficiency. It covers data cleaning, exploratory data analysis (EDA), and visualization of relationships between variables such as DRI Carbon and Silica (SiO2). The insights support data-driven decisions to optimize the steelmaking process.

## What Was Built

A Jupyter Notebook (`data-workflow/data_workflow.ipynb`) that loads, cleans, and analyzes internal steel production heat data, producing visualizations and statistical summaries saved under `outputs/`.

## Dataset

**Name:** Internal Steel Production Heat Dataset (company proprietary)  
Raw files are located in `data/raw/` and processed outputs in `data/processed/`.

## How to Run the Project

### 1. Install Dependencies

```bash
pip install -r requirements.txt
```

To regenerate `requirements.txt` from your current environment:

```bash
pip freeze > requirements.txt
```

### 2. Open and Run the Notebook

```bash
jupyter notebook data-workflow/data_workflow.ipynb
```

Then run all cells from top to bottom (**Kernel → Restart & Run All**).

The file was created and run using Python 3.14.5.


# Template GitHub Repository for EpiPandit Lab
## Quantitative veterinary epidemiology and disease ecology lab
==============================

This code was used to analyze hummingbird data that has been pooled from more than 25 years of intake records from 3 rehabilitation centers to determine the factors that affect the survival of the patients. The main features include summaries of patients by rehabilitation center, summaries of patient survival by whether they received first aid, reason of admission, and age, calculations of proportions of patients released vs. died by center, and summaries of admissions by year and month. Outputs of this code include figures of number of patients by center, died vs. released by factor, proportions of released vs. died by center, and number of admissions by year and month. 

## Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make setup` or `make conda-create`
    ├── README.md          <- The top-level README for developers using this project.
    ├── data
    │   ├── external       <- Data from third-party sources.
    │   ├── interim        <- Intermediate data that has been transformed.
    │   ├── processed      <- The final, canonical data sets for modeling.
    │   └── raw            <- The original, immutable data dump.
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks. The naming convention is a date (for ordering),
    │                         the creator's initials, and a short `-` delimited description, e.g.
    │                         `03132024-pranav-data-exploration`.
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials.
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc.
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── environment.yml   <- The environment file for reproducing the analysis environment, e.g.
    │                         generated with `conda create -f environment.yml`
    │
    ├── src                <- Source code for use in this project.
    │   ├── __init__.py    <- Makes src a Python module
    │   │
    │   ├── data           <- Scripts to process data
    │   │
    │   ├── models         <- Scripts to train models and then use trained models to make
    │   │   │                 predictions
    │   │
    │   └── visualization  <- Scripts to create exploratory and results-oriented visualizations

--------


## Setup Instructions
------------
1. Clone the repo
2. Create a virtual environment
3. Install the requirements
4. Run the notebooks

```bash
git clone
cd EpiPandit_Template
make conda-create
conda activate EpiPandit_Template
make setup
jupyter notebook
```
<p><small>Project based on the <a target="_blank" href="https://drivendata.github.io/cookiecutter-data-science/">cookiecutter data science project template</a>.</small></p>

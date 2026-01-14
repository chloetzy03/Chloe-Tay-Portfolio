## Programming with Data

This repository contains a data analysis project investigating how climate variables (temperature and rainfall) relate to dengue incidence in Singapore, using a full data workflow in a Jupyter Notebook report.

### Project overview
- Collected and combined dengue case records with climate datasets (temperature and precipitation), then cleaned and transformed them for analysis. 
- Performed exploratory data analysis (EDA) and built visualisations (trend plots and correlation-style comparisons) to interpret how dengue incidence changes alongside temperature/rainfall over time. 
- Investigated the 2020 dengue spike during COVID-19 by extracting NEA quarterly "breeding habitats" tables and summarising common patterns with a word cloud. 

#### What’s inside
- `*.ipynb` : Jupyter Notebook report (code + explanations + charts)
- `data/` (or CSV files) : datasets used by the notebook
- `requirements.txt` : Python dependencies to reproduce the notebook

#### How to run
1. Create a virtual environment (optional)
2. Install dependencies:
   - `pip install -r requirements.txt`
3. Open the notebook:
   - `jupyter notebook` (or `jupyter lab`)
4. Run cells top-to-bottom to reproduce outputs and visualisations.

### Notes (about the ZIP upload)
This GitHub upload is provided as a ZIP for convenience (notebook + data + resources + requirements).
To view everything locally, download the ZIP and open the notebook file (`.ipynb`) in Jupyter.

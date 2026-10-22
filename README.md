# MSCS & MSDS OOP with Python — Assignment 2, Advent 2026

This is a complete GitHub-ready repository for the five mini-projects in the lecturer's brief. Each project has a notebook, reusable OOP module, tests, visualisation code, assumptions and Findings & Limitations.

## Projects
1. `notebooks/project1_population.ipynb` — UBOS District Population Forecaster
2. `notebooks/project2_microgrid.ipynb` — Solar Micro-Grid Dispatch Planner
3. `notebooks/project3_fish_stock.ipynb` — Lake Victoria Fish Stock & Export Risk Model
4. `notebooks/project4_rainfall.ipynb` — Rainfall Pattern & Crop Suitability Analyser
5. `notebooks/project5_taxi.ipynb` — Taxi Route Revenue, Pricing & Fleet Planner

## Setup
```bash
python -m venv .venv
.venv\Scripts\activate
pip install -r requirements.txt
pytest -q
jupyter notebook
```

Run each notebook with **Restart & Run All**.

## Data and assumptions
The assignment marks the Project 1, 4 and 5 input series as illustrative, so those exact arrays are retained. Project 1 adds Mbarara and Mbale as additional illustrative districts. Project 2 generates a reproducible 30-day demand CSV with weekly pattern and noise. Project 3 uses the required seeded bounded random-walk price process.

The population notebook also discusses current UBOS census/projection context, but it does not falsely replace the assignment's illustrative training series with official projections.

## AI-use declaration
AI assistance was used to help structure code, tests, notebook scaffolding and documentation. The lecturer's supplied data, equations and required methods were followed. The student should review and understand the code before the viva.

## Public references
- UBOS NPHC 2024: https://statistics.ubos.org/nphc/
- UBOS population projections 2025–2050: https://statistics.ubos.org/nphc/projections
- ICPAC CHIRPS: https://www.icpac.net/data-center/chirps/
- FAO crop water needs: https://www.fao.org/4/S2022E/s2022e07.htm
- Uganda Climate Research decision-support tools: https://climateresearch.go.ug/tool

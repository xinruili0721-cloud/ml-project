# Startup Exit Outcome Prediction
Advanced Machine Learning — Individual Project
Rhea Li | Imperial College London | April 2026

## Project summary
A supervised ML pipeline to predict whether a VC-backed startup achieves
a successful exit (IPO or acquisition) using funding history and company features.

## Data
Download the following files from justinas/startup-investments on Kaggle
and place them in data/raw/:
- objects.csv
- funding_rounds.csv
- acquisitions.csv
- ipos.csv

## Setup
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt

## Run
Execute notebooks in order:
1. notebooks/01_data_exploration.ipynb
2. notebooks/02_features.ipynb
3. notebooks/03_models.ipynb
4. notebooks/04_results.ipynb

⚽ Premier League Match Winner Prediction
🧩 Project Overview

This project predicts the outcome of English Premier League (EPL) football matches using machine learning. It combines web scraping, data processing, and predictive modeling to forecast which team is most likely to win based on past match data.

🚀 Project Steps

Data Collection – Scrape historical EPL match data from FBref
 using requests, BeautifulSoup, and pandas.

Data Cleaning & Preparation – Process and structure the scraped data into a clean, machine-learning-ready format.

Model Training – Build and train a prediction model with scikit-learn to estimate match winners.

Evaluation & Optimization – Measure model accuracy, analyze prediction errors, and refine model parameters.

📁 File Overview
File	Description
scraping.ipynb	Jupyter Notebook for scraping and cleaning EPL data.
predictions.ipynb	Jupyter Notebook for training models and generating predictions.
⚙️ Local Setup
Prerequisites

Make sure you have Python 3.8+ and JupyterLab installed.

Installation

Clone the repository and install the required dependencies:

git clone (https://github.com/alejandrorosales07/Premier-League-Machine-Learning)
cd epl-match-predictor
pip install pandas requests beautifulsoup4 scikit-learn


Then open JupyterLab and run the notebooks:

jupyter lab

📊 Data

All data used in this project is scraped directly from FBref.com
, which provides detailed match statistics, team performance metrics, and results for the English Premier League.

🧠 Tech Stack

Python

pandas – Data manipulation and cleaning

requests / BeautifulSoup – Web scraping

scikit-learn – Machine learning modeling

JupyterLab – Interactive development environment

📈 Future Improvements

Add expected goals (xG), possession, and passing stats

Experiment with advanced models (e.g., XGBoost, CatBoost)

Build a simple web app for live match predictions

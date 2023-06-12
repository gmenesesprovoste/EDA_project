This repository contains an EDA housing marketing analysis tailored for a client who is a potential buyer with a tight budget, a large family and interested in finding a nice/social neighborhood.

Following a description of the files of this repository:

## 1_Fetching_the_data_eda.ipynb

Retrieving data from the database with psycopg2 (prefered method). Additionally, the file includes the steps to retrieve data using SQLAlchemy.

## column_names.md

Information about features of the dataset.

## EDA.ipynb

Jupyter notebook with my EDA analysis of King County (USA) housing prices.

## KingCounty_housing_market_analysis.pdf

A presentation in pdf format reviewing the most important findings. 


### Setting the environment

This repo contains a requirements.txt file with a list of all the packages and dependencies you will need. Before you install the virtual environment, make sure to install postgresql if you haven't done it before.

```bash
brew update
brew install postgresql
```

In order to install the environment you can use the following commands:

```
pyenv local 3.11.3
python -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
pip install -r requirements.txt
```

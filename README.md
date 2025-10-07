# Inflation analysis of Central-Eastern European countries between 2015-2025
Date: 07.10.2025.

## Description of the project: 
This is a README template describing the inflation analysis for Central-Eastern European (CEE) countries project. The goal is to creat a reproducible project analysing inflation data. This project visualizes and compares the evolution of inflation and core inflation in CEE countries between 2015 and 2025. 

## Data: 
Eusostat collects and assembles monthly inflation rates for all members of the European Union. This is the Harmonizes Index of Consumer Prices (HICP), which is a standardized measure of inflation across all member states.  It is an economic indicator that measures the change over time of the prices of consumer goods and services acquired by households.

The datasets contain annual rates of change in HICP indeces from 4 countries: Czechia, Hungary, Poland and Slovakia.

![Description of image](images/eurostat_image.png)
Data source: [Eurostat Database - HICP data](https://ec.europa.eu/eurostat/databrowser/view/prc_hicp_manr/default/table?lang=en&category=prc.prc_hicp)

There are 4 files provided in the data/raw folder: 
* CZ_.csv
* HUN_.csv
* PL_.csv
* SK_.csv

Variables in each country file:
* All-items HICP inflation
* Core HICP inflation (overall index excluding energy, food, alcohol and tobacco)

Combined data file in data folder: 
* combined_inflation_data.csv

## Folder structure
inflation_in_V4/
├── code/
│   ├── analysis.ipynb
│   └── main.ipynb
├── data/
│   ├── combined_inflation_data.csv
│   └── raw/
│       ├── CZ_.csv
│       ├── HUN_.csv
│       ├── PL_.csv
│       └── SK_.csv 
├── doc/
│   ├── readme.txt
│   └── submission_sample.csv
├── images/
│   └── eurostat_image.png
├── output/
│   ├── core_inflation_plot.png
│   └── inflation_plot.png
├── environment.yml
├── LICENSE
├── requirements.txt
└── README.md

## Getting Started
The entire analysis can be run by code/main.ipynb, which sets the working directory, saves the requirements.txt and runs the code for analysis.

## Requirements

A step by step series of examples that tell you how to get a development/analysis env running:

In conda:
```
conda env create -f environment.yml
conda activate mini_project_env
```


## Main Dependencies

- **Python** 3.12
- **jupyter / ipykernel** – running notebooks
- **pandas** – data manipulation and analysis
- **numpy** – numerical computations
- **matplotlib** – plotting and visualization

## Author

* **Borbala Kovacs**
 [https://github.com/borikovacs1-dev](https://github.com/borikovacs1-dev); Kovacs_Borbala@student.ceu.edu 
# Evaluating Public Health Responses: A Comparative Study of Ebola Management in Sierra Leone, Guinea, and Liberia
This is the code file to run our comparative study of Ebola Management in 3 sub-Saharan countries. This project analyzes the 2014-2016 Ebola epidemic in West Africa using time series analysis, survival analysis, and intervention analysis to understand the patterns of reported cases and deaths and evaluate the effectiveness of public health measures. The purpose of this project is to use the findings to inform public health policies and intervention startegies for similar, future outbreaks.

## Installation
Download the zipfile and decompress it in the folder you'd like to run the project in.

## Code Features
### Time Series Analysis
Anaylzes trends and seasonal patterns in cases and deaths and uses previous data to predict future trends.
### Survival Analysis
Estimates survival probabilities given the number of cases and deaths per week.
### Intervention Analysis
Assesses the impact of public health measures on epidemic progression.

## Folder Structure
```bash
project-root/
|
|-- src/                                 # contains the code files
|   |--- Intervention_Analysis.ipynb     # Intervention analysis code
|   |--- Time_Series.ipynb               # Time Series analysis code
|   └── Survival_Analysis.ipynb          # Survival analysis code
|   |-- data/                            # contains processed data files
|   |   |--- SierraLeone.csv             # cases and deaths for Sierra Leone
|   |   |--- liberia.csv                 # cases and deaths for Liberia
|   |   |--- Guinea.csv                  # cases and deaths for Guinea
|   └── Intervention Analysis Tables.csv # event data for all countries
|-- results/                             # output plots
|-- doc/                                 # writen results of the project
|   |--- poster.pdf                      # pressentation poster
|   |--- report.pdf                      # written report
└── README.md                            # this README file
```
## Usage
To run a demo, run the following commands to open the notebooks for each analysis. Run all the cells in each notebook to replicate the results obtained in the project.

- Time Series Anaylsis
```bash
jupyter notebook src/notebooks/Time_Series.ipynb
```
- Survival Anaylsis
```bash
jupyter notebook src/notebooks/Survival_Analysis.ipynb
```
- Intervention Anaylsis
```bash
jupyter notebook src/notebooks/Time_Series.ipynb
```
## Authors and Acknowledgements
This project was created by Devanshi Shah, Navya Gautam, and Moe Kyaw Thu.


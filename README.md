# DSCI_522_Group313 - AirBnb Price Predictor
Milestone 2 Repository
- Authors: Suvarna Moharir, Jaekeun Lee, Chimaobi Amadi

A data analysis project for DSCI 522 (Data Science Workflows), a course as part of the Master of Data Science program at the University of British Columbia.

## File Structure

```
.
├── README.md
├── data
├── docs
│   ├── CODE_OF_CONDUCT.md
│   ├── CONTRIBUTING.md
│   ├── LICENSE
│   ├── citations.bib
│   ├── final_report.Rmd
│   ├── final_report.md
│   └── proposal.md
├── eda
│   └── README.md
├── results
│   ├── README.md
│   └── score_plot.png
└── src
    ├── README.md
    ├── eda_summary.py
    ├── exploratory_analysis.ipynb
    ├── load_data.R
    ├── model.py
    ├── preprocessing.ipynb
    └── preprocessing.py
```

<br>

## About

In our project, we attempt to build a regression model using multiple linear regression, generalized linear regression, and random forest regression to find the best predictors for the price per night of an Airbnb in Quebec city. Airbnbs are often a popular option for those who are looking for low-cost, short-term rentals, and can often be a source of secondary income for hosts. 

For the Random Forest Regressor, the 5 most important features were:

1.  `calculated_host_listings_count_entire_homes`, which were the number
    of houses each host had up.
2.  `bathrooms`, the number of bathrooms in the unit.
3.  `calculated_host_listings_count`, which were the number of listings
    each host had up.
4.  `longitude`, the longitude of the rental unit.
5.  `latitude`, the latitude of the rental unit.

This analysis could prove useful for 2 major groups of individuals: (1) individuals who are looking to rent out one of their properties as an Airbnb, and are looking for a potential price to charge, and (2) individuals who currently rent out their properties as an Airbnb ('hosts'), and are trying to determine how best to increase the valuation of the rental property. 

<br>

## Usage

Please refer to the [README.md file in the src folder of this repo](https://github.com/UBC-MDS/DSCI_522_Group313/tree/master/src). 

<br>

## Report
The final report can be found [here](https://github.com/UBC-MDS/DSCI_522_Group313/blob/master/docs/final_report.md) 

<br>

## Dependencies
- R version 3.6.1 and R packages:
    - docopt == 0.6.1
    - tidyverse == 1.2.1
    - testthat == 2.2.1
- Python version 3.7.3 and Python packages: 
    - pandas == 0.24.2
    - numpy == 1.16.4
    - sklearn == 0.22.1 
    - docopt == 0.6.2
    - altair == 4.0.0

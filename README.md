# ADA Final Project

## Project Description
This repository includes the Americans' Changing Lives Study complete dataset from all 6 waves and R markdown used to analyze a subset of data from Wave 5 (2011). This project is a final project for the Advanced Data Analysis class at Washington University in St. Louis in the Fall 2025 semester. The dataset used in this study contains only public use data. More information about the dataset can be found here: https://doi.org/10.3886/ICPSR04690.v10

## Files Included
- '04690-0001-Data.rda': Complete data file. Also can be found here: https://doi.org/10.3886/ICPSR04690.v10
- 'Code.Rmd': R script used to summarize, visualize, and analysis data.
- 'README.md': This file

## What the Code Does
- Reads in the dataset
- Performs basic data cleaning (collapsing categories, droping NAs, etc.)
- Creates summary statistics
- Runs unadjusted and adjusted logistic regressions
- Checks for influential cases
- Checks model fit
- Explores the use of V16612 (interviewer perception of depression in respondent) and addition of V16612 to unadjusted and adjusted logistic regressions
- Provides brief interpretations of each model and output, when necessary
- Creates Tables and Figures that may be relevant

## How to Run the Code
1. Download or clone this repository to your computer
2. Open 'Code.Rmd in RStudio
3. Make sure your working directory is set to the folder where the files are saved
4. Run the script

## Author
- Name: Jaedra Hopkins
- Course: Advanced Data Analysis
- Date: December 2025
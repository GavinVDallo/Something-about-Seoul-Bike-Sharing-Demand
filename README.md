# APM1205 - Linear Models: Summative Assessment 1

## Student Information
* **Student Name:** [Gavin Manuel V. Dallo]
* **Course and Section:** APM1205 - [Sec 3]
* **Assessment Title:** Summative Assessment 1: Comprehensive Linear Modeling Analysis

## Project Overview
This analysis investigates hourly bicycle rental demand using the **Seoul Bike Sharing Demand Dataset** from the UCI Machine Learning Repository. The project systematically builds, estimates, and evaluates linear regression models to understand how environmental weather conditions (temperature, humidity, wind speed) and social calendar structures (seasons, holidays) drive municipal bike usage.

* **Dataset Source:** [UCI Machine Learning Repository](https://uci.edu)
* **Software Used:** R (RStudio)

## Core Research Question
Does ambient outdoor temperature significantly predict hourly bike-sharing demand when accounting for seasonal shifts and calendar day types?

## Required Packages/Libraries
To run the analysis script, you must have R installed along with the following packages:
* `tidyverse` (Data cleaning and visualization)
* `car` (ANOVA calculations and VIF diagnostics)

## Instructions for Reproducing the Analysis
1. Clone this repository to your local workstation.
2. Download the source dataset `SeoulBikeData.csv` from the UCI repository link provided above.
3. Save the dataset inside your local environment's folder pathway: `~/data/SeoulBikeData.csv`.
4. Open the file `SA1_Linear_Models.Rmd` in RStudio.
5. Click the **Knit** button to execute the code and generate the final PDF report.

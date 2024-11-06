# Fuel-Economy-and-Price-Analysis-for-Toyota-Models
Description
This project provides an in-depth analysis of fuel economy and pricing for various Toyota car models. The main goals are to explore fuel efficiency (measured as Miles Per Gallon or MPG), assess price determinants, and analyze different sampling strategies. Using a dataset of Toyota cars, we perform data visualization, calculate variance and skewness, fit regression models, and apply sampling techniques to gain insights into the relationship between fuel type, transmission, and vehicle price.

Data Source
The dataset includes Toyota car models with details such as:

Miles Per Gallon (MPG): Fuel efficiency metric
Model: Specific Toyota car model names (e.g., Corolla, Prius)
Fuel Type: Types include petrol, diesel, and hybrid
Transmission: Manual or automatic
Price, Mileage, and Year: Used for price prediction analysis
This data was used to explore relationships between vehicle characteristics, fuel economy, and price.

Objectives
This project addresses several specific questions:

MPG Analysis:
Visualize the distribution of MPG for Toyota models and analyze skewness and variance.
Compare MPG across fuel types (petrol, diesel, and hybrid) and suggest the best measure of center.
Price Prediction:
Assess correlations between price, year, and mileage.
Fit a regression model to predict car price based on mileage and analyze the fit.
Sampling Strategy:
Explore sampling techniques such as cluster, stratified, and random sampling.
Assess potential biases and improvements for a hypothetical experiment.
Installation Guide
To replicate the analysis, install the following packages in R:

R
Copy code
install.packages(c("ggplot2", "dplyr", "readr"))
These packages enable data manipulation, visualization, and statistical calculations. This project was created in R version 4.x.x, which is recommended to ensure compatibility.

Usage
Each analysis is broken down into separate R scripts and RMarkdown notebooks. Follow these steps:

Run Analysis Scripts:

scripts/mpg_analysis.R: Performs MPG analysis, including histograms, barplots, and skewness.
scripts/price_analysis.R: Runs price analysis using correlation, regression, and residual plots.
scripts/sampling_analysis.R: Conducts sampling method exploration and discusses bias.
Use Notebooks for Detailed Steps:

notebooks/Q1_EDA_MPG.Rmd: Exploratory Data Analysis on MPG.
notebooks/Q2_Price_Prediction.Rmd: Price analysis and regression model for price prediction.
notebooks/Q3_Sampling_Methods.Rmd: Documented analysis of sampling methods and experiment design.
The RMarkdown notebooks provide a step-by-step guide to each question’s analysis with code and explanations.

Results Summary
Key insights from the analysis include:

Fuel Economy (MPG): Hybrid cars exhibit the highest MPG, with consistent performance across models. Diesel models show the most variability in fuel economy.
Price and Mileage Correlation: Newer cars with lower mileage generally have higher prices. A regression model suggests that price decreases with higher mileage.
Sampling Bias: The analysis of sampling techniques highlights potential biases. For instance, stratified sampling by product category provides better representation compared to cluster sampling by shelves.
Contributing
Contributions are welcome! If you would like to suggest improvements or add to this analysis:

Fork the repository.
Create a branch for your changes.
Submit a pull request with a description of the improvements.

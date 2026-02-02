# Taiwan-Air-Quality-Index Analysis
Project investigates relationship between the Air Quality Index (AQI) and various pollutant levels.

# Modeling Taiwan Air Quality Index (AQI) using Simple Linear Regression

## About Me
Hi I'm Karthik, I work as a Data Analyst + AI Engineer concentrating on using statistical modeling to address environmental and societal issues. I focus on R, machine learning, and predictive analysis. Don't hesitate to reach out to me on [LinkedIn](https://www.linkedin.com/in/karthikkuppala/) or check out my additional projects


## Project Overview
This project examines the correlation between the Air Quality Index (AQI) and different pollutant concentrations in Taiwan. Utilizing a dataset of 280 observations, I determined PM2.5 to be the main factor affecting air quality and developed a Simple Linear Regression (SLR) model to forecast AQI levels

## Key Findings

**Predictor Identification:** Employed Pearson correlation to identify which prevalent pollutants (PM 2.5, PM 10, and CO) significantly affect air quality ratings.

**Regression Modeling:** Created a simple linear regression model to measure the effect of PM 2.5 on the index.

**Diagnostic Testing:** Performed an extensive assessment of model assumptions, such as linearity, independence, normal distribution of errors, and homoscedasticity.

**Hypothesis Testing:** Conducted slope parameter analysis to furnish statistical support for the association between the pollutant and AQI

## Analytical Insights + Results

* **Strongest Predictor:** PM2.5 showed a Pearson correlation of 0.85 with AQI.
  
* **Model Performance:** The SLR model achieved an R² of 0.72, explaining 72% of the variance in AQI.
  
* **Statistical Significance:** A hypothesis test confirmed a statistically significant association (p-value < 0.05).
  
* **Mean Absolute Error (MAE):** 12.56, indicating the model is typically off by 12.56 units within an AQI range of 102.
  
* **Health Impact:** For every one-unit increase in PM 2.5, the AQI rises by approximately 1.85 units, indicating a significant degradation in air quality.

## Technical Stack

* **Language:** R

* **Libraries:** Built-in R statistical functions (lm, cor, predict, rstandard) and visualization tools (plot, qqnorm, qqline).

## How to Run

**Clone the Repository:** git clone https://github.com/YourUsername/Taiwan-AQI-Analysis.git

**Ensure Data Availability:** Place the airQuality.csv file (if available) in the /data directory. (Download from [Kaggle dataset](https://www.kaggle.com/datasets/taweilo/taiwan-air-quality-data-20162024))

**Execute Analysis:** Open AQI_Analysis.R in RStudio and run the script.

## Repository Contents

* `AQI_Analysis.R`: Full R code including synthetic data generation and regression modeling.
* `Taiwan_AQI_Analysis.pdf`: A formal research paper documenting the full methodology and results.
* airQuality.csv: Original file unavailable due to copyright + GitHub repo upload limit issues and Git. Use this [Kaggle dataset](https://www.kaggle.com/datasets/taweilo/taiwan-air-quality-data-20162024) instead to fill the gap.

## Results from orginal data

As the data file which I orginally used as a source is not available I figured I'd display my visualizations and results to help understand my observations.

Result 1:
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/1ae1b874-3ad1-4af4-b2d4-b70471d26cd4" />

Result 2:
<img width="500" height="300" alt="image" src="https://github.com/user-attachments/assets/462ce20b-7f9c-425c-9145-dd811e3d612f" />

Result 3:
<img width="500" height="600" alt="image" src="https://github.com/user-attachments/assets/49dc8c33-8d47-4451-8ae0-ae44cd838b2e" />

Result 4:
<img width="367" height="288" alt="image" src="https://github.com/user-attachments/assets/66fb5ada-a3ce-4cd1-82ca-bdb068497036" />

~

Thank you for taking the time to have a look at my work <3




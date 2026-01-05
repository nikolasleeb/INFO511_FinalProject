# Final Project for INFO 511 - Intro to Data Science

## (Fall '25 MS of DS @ University of Arizona)

---

### Project Description

  This project explores the relationship between U.S. Gasoline consumption and prices using datasets from the U.S. Energy Information Administration (EIA). The primary point was to investigate whether gasolines prices were meaningfully consumption patterns between 1994 and 2024.

  The project is meant to demonstrate my data science knowledge learned throughout the semester. The structure of the project includes data cleaning, Exploratory Data Analysis (EDA), visualization, and basic modeling. Each dataset was cleaned and analyzed individually to understand the stats, distribution, and outliers. Then interactive visualizations were created using plotly to explore temporal patterns. The Federal Reserves CPI index was used to account for inflation over time.

  After EDA for both datasets, they were merged on the Date column using an inner join. Once imported into the Analysis notebook, additional feature cleaning and transformation was performed. A simple linear regression model was then fit that could only explain 14% of the variance in gasoline consumption. Given that gasoline has an inelastic demand, the result was considered to be expected. To explore a non-linear relationship, a LOESS model was implemented that was able to explain about 38% of the data.

---

### Project Requirements

[Project Requirements Document in Google Drive](https://drive.google.com/file/d/13CWS9x0oeh7JDBJHq_ZlC9wZggIYATyT/view?usp=sharing)

* Milestone 1 is project proposal
* Milestone 2 is EDA checkpoint
* Milestone 3 is first draft turned in for peer review
* Milestone 4 is Final project due

---

### Project Breakdown

```text
|---Analysis Folder
|   |---Charts Folder
|   |---Merged Data Folder
|   |   |---merged_gasoline_data.csv
|   |---Analysis.ipynb (all analysis work in this notebook)
|
|---EDA Folder
|   |---Charts Folder
|   |---ConsumptionData Folder
|   |---PricesData Folder
|   |   |---merged_gasoline_data.csv
|   |---EDA.ipynb (all data cleaning and visualizations in this notebook)
|
|---FinalWrittenReport
|   |---Final Written Report.docx
|
|---Milestones
|   |---Milestone1.docx
|   |---Milestone2.docx
|
|---INFO 511 Final Presentation.pptx
|---README.md (this document)
```

---

### Ideas for Improvement

* use autoregressive modeling (no extra data)
  * use panel regression (no extra data)
  * use extra data
    * vehicle registration
    * fuel efficiency
    * vehicle production
  * multivariate regression
  * random forest regressor
  * XGBoost
  * Forecasting and scenario modeling
  * Time-Series CV
  * use imputation to make up for missing data

I had another project in INFO 523 in this same semester that I started after I had finished most of this project. The INFO 523 project had a larger scope and was not asked to be a simplified project as this was. Using this INFO 511 project, I applied my ideas for improvement including new data and experimenting with new models to complete the INFO 523 project. That project is viewable [in Github, here.](https://github.com/nikolasleeb/INFO523_FinalProject)

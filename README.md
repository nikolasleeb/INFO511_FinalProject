# Final Project for INFO 511 - Intro to Data Science 
## (Fall '25 MS of DS @ University of Arizona)

---

### Project Requirements:
Project Requirements Document: https://drive.google.com/file/d/13CWS9x0oeh7JDBJHq_ZlC9wZggIYATyT/view?usp=sharing 

* Milestone 1 is project proposal
* Milestone 2 is EDA checkpoint
* Milestone 3 is first draft turned in for peer review
* Milestone 4 is Final project due

---

### Project Description:
  Using datasets from the U.S. Energy Infrastructure Administration, I wanted to explore Gasoline Consumption and Prices interact. After selecting the datasets, removing unneeded columns and renaming the others, I began to explore the data. For each dataset I explored the summary statistics, skew, kurtosis, and checked for outliers. Following that each dataset was individually visually explored through plotly charts such as line and bar charts, heatmaps and annotations. Once I had understood each dataset on its own, I merged the two datasets together on the Date columns using an Inner Join. After further renaming, removing of, and converting columns, I visualized the merged datasets. I then exported the dataset to a new notebook. Once the data was imported into that notebook, I double checked the shape and features of my data before attempting to fit a simple linear regression model. The model was only able to explain 14% of the data which was actually a good outcome for this project since gasoline is an elastic good and has no replacements. I then asked ChatGPT to implement me a LOESS model which was able to explain 38% of the data.

  Through out the project I used ChatGPT to help better understand a data pipeline and how to code one, convert matplotlib charts to plotly charts, implement models, and debug my code.

----

### Ideas for Improvement:
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

I had another project in INFO 523 in this same semester that I started after I had finished most of this project. The INFO 523 project had a larger scope and was not asked to be a simplified project as this was. Using this INFO 511 project, I applied my ideas for improvement including new data and experimenting with new models to complete the INFO 523 project. That project is viewable in my GitHub. 
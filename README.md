# Datasets Analysis in R

## Description:

This project aims to analyze various datasets from Kaggle or other places for the purpose of gaining insights into different aspects of the data, as well as 
honing my R coding skills through the process of data analysis. The project will continuously be updated by adding new and interesting datasets from Kaggle or 
other sources, and analyzing them using R.  

## Table of contents:  
- [Portfolio Projects](#portfolio-projects)
	+ [Netflix movies and TV shows exploratory data analysis](#netflix-movies-and-tv-shows-exploratory-data-analysis)
	+ [Insurance Cost Regression Analysis](#insurance-cost-regression-analysis)
  + More to come 

## Portfolio Projects:

### Netflix movies and TV shows exploratory data analysis:  
**Dataset:**[Netflix movies and TV shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows) This dataset comprises a comprehensive list of movies and 
TV shows that are currently or have been previously available on Netflix, including details such as cast, directors, ratings, release year, and duration, etc.  
**Code:**[insurance-cost-regression.rmd](https://github.com/Zhiwei2799/Data-analysis-in-R/blob/main/insurance-cost-regression.rmd).  
**Goal:**  
1. Visualize the number of movies and TV shows available on Netflix.  
2. Visualize the number of movies and TV shows for each rating.  
3. Visualize the number of movies produced by each country using a world map plot in ggplot2.  

**Skill:** Data Cleaning, Univariate Analysis, Bivariate Analysis, Descriptive Statistics.  
**Requirements:** The following R packages and versions:  
1. tidyverse version: 1.3.2.  
2. skimr version: 2.1.5.  
3. ggplot2 version: 3.4.0.  

**Code Output:**[Netflix Content output.pdf](https://github.com/Zhiwei2799/Data-analysis-in-R/blob/main/Netflix%20Content%20output.pdf).  
**Result:** Netflix has twice as many movies as TV shows, and most are produced in the United States, followed by India.  

### Insurance Cost Regression Analysis:  
**Dataset:** [Insurance Cost Datasets](https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv) this dataset comprises 1,338 rows and 7. variables such as age, sex, bmi, number of children, smoker status, region and charges for insurance. The target variable is the cost of insurance claims.   
**Code:** [insurance-cost-regression.rmd](https://github.com/Zhiwei2799/Data-analysis-in-R/blob/main/insurance-cost-regression.rmd).  
**Goal:** 
1. Conduct Exploratory Data Analysis on Insurance Dataset.  
2. Forcast insurance costs   

**Skill:** Data Cleaning, Univariate Analysis, Bivariate Analysis, Descriptive Statistics, Multiple Linear regression, Box-Cox Transformation, RandomForest   
**Requirement:** The following R packages and versions:  
1. tidyverse version: 1.3.2  
2. skimr version: 2.1.5  
3. ggplot2 version:	3.4.0  
4. car  version: 3.1-1  
5. MASS version: 7.3-58.2  
6. GGally version: 2.1.2  
7. RandomForest version: 4.7-1.1  
8. Caret version: 6.0-93  

**Code Output:** [Insurance cost regression output.pdf] (https://github.com/Zhiwei2799/Data-analysis-in-R/blob/main/Insurance%20cost%20regression%20output.pdf)  
**Result:** The variable smoker is the most significant variable in determining insurance charges, followed by Body Mass Index (BMI) and age. Other factors such as the number of children, region, and sex have minor or no impact on the charges.  






**Acknowledgements:**

[Netflix movies and TV shows dataset](https://www.kaggle.com/datasets/shivamb/netflix-shows)

[Medical Cost Personal Datasets](https://github.com/stedy/Machine-Learning-with-R-datasets/blob/master/insurance.csv)

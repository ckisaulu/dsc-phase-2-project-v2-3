# House Price Prediction in King County

Author: Group 12


## Project Overview

Multiple linear regression modelling to predict house prices in King County. The project aims to derive data driven recommendations on features that best predict house prices to developers seeking to increase affordable housing units in King County.

## Business Problem
There is limited availability of residential units in King County, causing increased costs across different grades. Disparities in the housing market, especially in desirable areas, are leading to unsually high property values. There is need to come up with a model that can accurately predict house prices in King County based on the features of a house to guide developers on what features they ought to focus on to develop affordable housing units. 


### The Data

This project uses the King County House Sales dataset from Kaggle. The data has 20 variables describing the size, condition, grade, location and other features of a house that influence its sale price. The description of the variable names(column names) can be found in the `column_names.md` folder. 

### Methods

The data was cleaned and prepared for analysis. Exploratory data analysis was conducted to give insight into the features. Predictor variables were then selected based on the strength of their correlation with the outcome variable(house sale price), while minimizing multicollinearity between predictor variables. The selected variables were used to create a multiple linear regression model to predict house prices. 


## Results

Our multiple linear regression model consisted 6 predictor variables and an intercept that were all statistically significant with p-values of 0.00. The R-squared value of the model was 0.582, meaning the variables were accounting for 58.2% of the variance in the outcome variable. 

![Multipleregression](/images/multipleregression.png)



## Recommendations

To ensure availability of affordable housing in King County, developers should:

- Prioritize the construction of houses with a an average grade rating. These will be comfortable without experiencing the price inflation associated with higher grade rating.

- Focus more on properties away from the waterfront where price tends to be very high.

- Limit the number of bedrooms and bathrooms to the requirements of an average home buyer in King County. Many bathrooms will increase house prices while many bedrooms will decrease prices as many people do not seem to be searching for luxurious housing.



## Further Analysis

- Investigate the impact of year renovated in relation to year built

- Investigate the cause of the price decrease with increase in the number of bedrooms

- Expand the dataset size to enhance model robustness.



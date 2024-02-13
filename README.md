# TangoPricePredictor
## Predict apartment prices in the bustling streets of Barcelona. ##

By adeptly building a linear regression model using scikit-learn, establish a robust data pipeline proficient in handling missing values and categorical features, implementing strategies to reduce overfitting, and creating a dynamic dashboard for seamless interaction with a predictive model.

## Preparing Data
 Automate the data importing and cleaning process by writing a function `wrangle`, that reads data from the specified file path and returns a DataFrame.
 The aim of this project is to build a model for apartments in Barcelona ("Capital Federal") that cost less than $400,000.
 
 ## Explore
 Create a histogram of `"surface_covered_in_m2"` in order to see the distribution of apartment sizes.
 Remove outliers in the `"surface_covered_in_m2"`

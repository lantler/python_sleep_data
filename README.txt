This project analyses factors that affected the sleep time of 946 Americans between 2003-2017. 

*Dependencies*
Pandas
Seaborn
Matplotlib, Pyplot
Numpy
Sklearn, LinearRegression
Sklearn, mean_squared_error

*Variables*
YEAR
AVG_HOURS_SLEPT
STANDARD_ERROR
TYPE_OF_DAYS
AGE_GROUP
SEX

*Data cleaning*
steps taken to clean the data: 
- columns aggregated for sex and gender are dropped from the dataset
- time slept is converted to minutes for future tasks

*Calculations & plots*
- visualizes average sleep hours by SEX, AGE_GROUP
- calculates correlation matrix between SEX, AGE_GROUP and AVG_HOURS_SLEPT
- visualizes scatter plot for AVG_HOURS_SLEPT grouped by YEAR
- calculates correlation matrix between AVG_HOURS_SLEPT and TYPE_OF_DAYS

*Predictive models*
- Dataset is split into training (80%) and test (20%) sets
- linear regression predictive model is applied to predict the relationship between YEAR and AVG_HOURS_SLEPT
- vizualises the predicted line


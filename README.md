# Project One
## Using different regression models to predict item sales at grocery stores 

**Joseph Cobbs**: 

### Question:

Which features lead to higher item sales in grocery stores?


### Data:
The data contains approximately 8,500 records of grocery stores or supermarkets. It includes features such as their average item sales, item weight, store type, and other descriptive variables. 


## Methods
- There were no duplicates in the data
- there were errors in categories. 

## Results

#### Heatmap of correlated features
![Heatmap](https://user-images.githubusercontent.com/49537432/216462392-5dd0b02e-cef4-4528-b323-90b2d88eb4c6.png)

There is a strong correlation between 

#### Boxplot of Average Outlet Sales grouped by Outlet Size

![Boxplor](https://user-images.githubusercontent.com/49537432/216632493-5cb60616-3b6f-4cda-a619-32b4b8641d96.png)

## Regression Tree Model 

The model had extremely low variance, but had slightly better bias than the regression analysis model. At 60% the perdictive power of the model is still relatively low, but can be useful. 

Model Training RMSE is: 1172122.7729098853
Model Testing RMSE is: 1118185.973077762

Model Training r2 is: 0.6039397477322956
Model Testing r2 is: 0.5947099753159972


## Recommendations:

The variance is excellent and does not need to be improved. The bias, however, needs to be reduced. At a 60% predictive ability trusting this model is little better than a coin flip. The two recommended ways to improve bias, predictive capacity, is to increase the quantity of the data and to perhaps increase variance. The variance is high enough that it is worth to reduce it in order to improve bias. 


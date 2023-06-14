![alt text](https://learn.g2.com/hubfs/shopper%20marketing.jpg)

# Data Science and Grocery Sales
## Analyzing Outlet Sales 
** Archived**
**Eli Spreng**: 

### Business problem:

In looking at grocery sales, interested parties want to know what will will increase sales. This project analyzes what factors have the greatest impact on 
grocery outlet sales.


### Data:
Big Market Sales Prediction: https://datahack.analyticsvidhya.com/contest/practice-problem-big-mart-sales-iii/#About


## Methods
- To perform this analysis the data was cleaned and then exploratory and explanatory visuals offer insights
- Machine learning using regresstion metrics provides another way to understand grocery sales. 

## Results

#### Visual 1: Bar Graph Showing Outlet Year and Sales
![alt text](https://github.com/Elispreng/Project-1-Food-Sales-and-Store-Cultures/blob/main/Spreng%20Outlet%20Year%20and%20Sales.png)

The graph addresses answers the question "What year has the highest item  sales?" The highest item sales were in 2004.

#### Visual 2 Bar  Graph Showing Outlet Year and MRP

![alt text](https://github.com/Elispreng/Project-1-Food-Sales-and-Store-Cultures/blob/main/Spreng%20Outlet%20Year%20and%20MRP.png)


This bar graph answers the question "What  year has the tighest MRP?" The highest MRP was in 2004

## Machine learning and metrics
- Linear Regression Model
- Regression Tree Model
- Bagged Trees Model

### Linear Regression Metrics:

- Model Training R2: 0.6714424977432687
- Model Testing R2: 2.0994337117833997e-05

### Decision Tree Model Train Scores
 - MAE: 0.0 
 - MSE: 0.0
 - RMSE: 0.0 
 - R2: 1.0

### Decision Tree Model Test Scores
 - MAE: 992.5956 
 - MSE: 2103175.480
 - RMSE: 1450.2329
 - R2: 0.2376974

### Bagged Trees Model Train Scores
 -  MAE: 316.5676
 -  MSE: 240010.0091
 -  RMSE: 489.9082
 -  R2: 0.9189006

### Bagged Trees Model Test Scores
 - MAE: 785.6302
 - MSE: 1279423.2806
 - RMSE: 1131.1159
 - R2: 0.536269

## Recommendations:

From these metrics, the bagged tree model is the best model with the lowest error and highest R2. However, there is still some variance in this model. 

## Limitations & Next Steps

This project will include more graphics. Another limitation is the regression metrics still need tuning in the models. 

### For further information


For any additional questions, please contact **doctor.eemail@gmail.com**

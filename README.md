# Powerlifting-meets-analysis
Powerlifting US tested  project

## Data Exploration :
After loading the dataset, i did a little data cleaning then plotted the correlation between the age and the totalKg lifted by tested lifters in meets in the US :
We see a pattern emerge :  Less totalKg lifted for older lifters

![alt text](https://github.com/AmineDiro/Powerlifting-meets-analysis/blob/master/ageXtotalkg.png?raw=true)

This is the base of the hypothesis testing between two population means we will be conducting

You can look at the steps of the 'Powerlifting US tested  project' jupyter file to see the full analysis but this is a the boxplot we have after removing all outliers and comparing between -30 years to 30+ : 

![alt text](https://github.com/AmineDiro/Powerlifting-meets-analysis/blob/master/Powerlifting%20US%20tested%20%20project.png?raw=true)

## T-TEST Result : 
```
values_u30 mean value: 0.14312392346528213
values_p30 mean value: 0.10563437997303354
values_u30 std value: 0.08231050243478406
values_p30 std value: 0.07861348963943036
```
> p-value 1.0514056404451937e-262
We reject  the null hypothesis : there is a statisticaly difference between the two means
I added few data exploration graphs in the other jupyter notebook 

**Link to the dataset :** [Powerlifting Dataset Kaggle](https://www.kaggle.com/open-powerlifting/powerlifting-database)

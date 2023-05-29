# Classification-of-Raisin-Grain-Varieties-Using-Statistical-Modelling-and-Data-Mining (In R programming)
*************************
# Project Summary
The goal of this project is to apply statistical analysis and modelling techniques to address the problem of raisin classification. 
Two raisin grain varieties (Besni and Kecimen) were classified in this project using raisin morphological measurements which were obtained through 
image processing techniques. Statistical modelling is conducted using Logistic regression model to measure the statistical significance of combined raisin features in determining the two (2) raisin varieties

**************
# I. Dataset Description
The dataset has a dimension of 900 observations and 8 features. The first 7 columns of the dataset are the morphological independent variables listed as ‘Area’, ‘MajorAxisLength’, ‘MinorAxisLength’ ‘Eccentricity’, ‘ConvexArea’, ‘Extent’, and ‘Perimeter’. The last column labelled ‘Class’ is the dependent variable and at the same time target class

****************************

# II. Methods
The methodology will be implemented with R programming language. Also, R is well built to perform a huge variety of run arithmetic calculations and scientific implementation of machine learning algorithms. Methods used for this projects are outlined below
1.  Descriptive statistical summary (mean, skewness, kurtosis, boxplot)
2.  Collinearity Analysis using Spearman correlation rank
3.  Feature selection using Random Forest
4.  Statistical Modelling using Logistic regression (univariate & multi variate model)

***********************

# III. Results from Statistical Modelling (Logistic Regression Analysis) 
1.  Results from the statistical modelling technique show that raisin “Perimeter” and “MajorAxisLength” predictors are statistically significant in 95% CI, and p-values for any bivariate or multivariate model, however, both predictors produce lower odds in determining a kecimen raisin for every 1 unit increase in their measurements. 
2.  The “Extent” predictor was observed to be statistically significant in 95% CI, and p-values at α = 0.05, producing 18.9 times higher odds in predicting a kecimen variety when combined with “perimeter” predictor
*************
![image](https://github.com/oawonuga92/Classification-of-Raisin-Grain-Varieties-Using-Statistical-Modelling-and-Data-Mining/assets/61459286/1d3634aa-981c-4b9d-9245-0dc51634265a)

***
![image](https://github.com/oawonuga92/Classification-of-Raisin-Grain-Varieties-Using-Statistical-Modelling-and-Data-Mining/assets/61459286/74a1fc8e-7376-43cd-b82e-ac951355ded7)






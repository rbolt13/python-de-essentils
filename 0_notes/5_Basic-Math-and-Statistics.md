# Basic Math and Statistics

# Simple Arithmetic

## Definitions

Array: a one-dimensional container for elements that are all of the same data type. 

Matrix: a two-dimenstional container for elements that are stored in an array. 

## Arithmetic Operators in Python

![image](https://user-images.githubusercontent.com/76530973/192800019-e0582ba0-c556-4d7c-a9d9-6a4aa3b99129.png)

# Basic Linear Algebra 

![image](https://user-images.githubusercontent.com/76530973/192805410-5d59d8e7-a9dd-4b60-ad6b-b2230999447b.png)

![image](https://user-images.githubusercontent.com/76530973/192805519-2a9f58a9-5dc9-491b-956a-0ba00fb9bd7d.png)

![image](https://user-images.githubusercontent.com/76530973/192805583-cae81ec5-fb78-4d11-aea4-666d137f93bb.png)

![image](https://user-images.githubusercontent.com/76530973/192807704-e1c8b90e-5675-422d-8380-eed331095ef7.png)

# Generating Summary Statistics

## Two Categories of Descriptive Statistics

1. Descriptive statistics that describe the values of observations in a variable.
2. Descriptive statistics that describe variable spread. 

(1) Observations: sum, median, mean, max

(2) Spread: Standard deviation, variabce, counts, quartiles

## Uses for Descriptive Statistics

* Detecting outliers
* Planning data preparation requirements for machine learning
* Selecting feature for use in machine learning

# Summarizing Categorical Data

## Categorical Variable 

* Accepts only a limited and fixed number of values. 
* Each observation is assigned to a specific subgroup.

## Creating a Categorical Variable 

![image](https://user-images.githubusercontent.com/76530973/192876576-28b4093b-f56d-4fc5-921a-169ea47b3275.png)

## Basic Ways to Describe Categorical Variables

1. Counts
2. Variable Description
3. Grouping 

## Creating a Crosstab

* A cross-tabulation of two (or more) features
* By default, a crosstab table shows frequency counts for features

![image](https://user-images.githubusercontent.com/76530973/194355972-89410deb-25e5-4c6d-8881-87825426cf00.png)

Cars with a manual transmission are more likely to have 3 gears, while cars with an automatic transmission are more likely to have 4 or 5. 

# Parametric Correlation Analysis

* A method you can use to find correlation between linearly related continuous numeric variables. 

**Correlation does not imply causeation**

## Pearson Correlation Coefficient 

* R = 1 --> Strong positive relationship
* R = 0 --> Not linearly correlated 
* R= -1 --> Strong negative relationship 

## The Pearson Correlation Assumes

* Your data isnormally distributed
* You have continuous, numeric variables 
* Your variables are linearly related

## Use Pearson Correlation 

* To unconver (linear) relationships between variables
* Not to rule out possible (nonlinear) relationships between variables

## Consider the Model Assumptions 

Satisfies Assumptions

* Normally distributed 
* Linearly related 
* Continuous, numeric variable 

![image](https://user-images.githubusercontent.com/76530973/194360288-7b0f07d0-9792-4a1b-866f-668e1d7ab3ed.png)

These are NOT continuous variables. 

# Non-parametric Correlation Analysis

* You can use nonparametric correlation analysis to find correlation between cateforical, nonlinearly related, non-normally distributed variables

1. Spearman's rank correlation
2. Chi-square tables

## Spearman's Rank Correlation 

* Finds the R correlation between variable-pairs of ordinal data type
* Variable-pairs are then able to be ranked according to the strength of the correlation between them 

## Spearman's Rank COrrelation Coefficient

* R = 1 --> Strong positive relationship
* R = 0 --> Not linearly correlated 
* R = -1 --> Strong negative relationship 

## Spearman's Correlation Assumption

* Your variables are ordinal; numeric, but able to be ranked like a categorical variable
* Your variables are related nonlinearly
* Your data is non-normally distributed

## Chi-Square Test for Independence 

* p < 0.05 --> Reject null hypothesis and conclude that the variables are correlated
* p > 0.05 --> Accept null hypothesis and conclude that the variables are independent 

# Use Chi-Square Tables If

* Your variables are categorical or numeric 
* You have binned the numeric variables

![image](https://user-images.githubusercontent.com/76530973/194365098-36692012-c075-4960-801c-d3bce3a67d70.png)

# Transforming Dataset Distributions

## Why It's Important to Scale Your Data

* So that differing magnitude among variables do not produce erroneous or misleading statistics
* To prepare your data for machine learning

## Two Ways to Scale Your Data

1. Normalization: putting each observation on a relative scale between the values of 0 and 1. 

![image](https://user-images.githubusercontent.com/76530973/194369303-79c2952e-2b66-4801-8300-41e1457da7d4.png)

2. Standardization: rescaling data so that it has a zero mean and a unit variance

## Use scikit-learn Preprocessing For

* Scaling your data
* Centering your data
* Normalizing your data
* Binning your data
* Imputing your data

# Extreme Value Analysis for Outliers

## Outlier Detection 

* Most machine learning methods assume that your data has been treated for outliers
* Detecting outliers can be a data preprocessing task or an analytical method of its own merit

## Outlier Analysis Use Cases 

Use outlier detection to uncover anomalies that represent: 

* Equipment Failure
* Fraud
* Cyersecurity Event

## Univariate Method: Tukey Boxplots

![image](https://user-images.githubusercontent.com/76530973/194373699-036b3acd-d625-456a-a4d8-25db9de02263.png)

* Boxplot whiskers are set at 1.5(1QR)
* If you see data points past these whiskers, they're outliers

**Inter-quartile range (IQR)**

Inter-quartile range (IQR) = (or speed) the distance between the first quartile (at 25%) and the third quartile (at 75%). 

## Univariate Method" Tukey Outlier Labeling 

a = Q1 - 1.5(IQR)

b = Q3 + 1.5(IQR)

If... 

* min. value < a, or 
* max. value > b, then...

**The variable is suspect for outliers**

## Univariate Method: Tukey Boxplots

![image](https://user-images.githubusercontent.com/76530973/194378008-4edffb52-562b-4505-92bc-3e6030caa253.png)

![image](https://user-images.githubusercontent.com/76530973/194378458-abc1bbe4-7fdc-4f4b-adf8-9e6878d56780.png)

![image](https://user-images.githubusercontent.com/76530973/194378809-ff9263b5-91f1-48f6-9fd5-769cffd189a2.png)

# Multivariate Analysis for Outliers

Use multivariate methods to find the outliers that only show up within combinations of observations from two or more different variables.

## Scatterplot Matrix 

![image](https://user-images.githubusercontent.com/76530973/194383829-40a82858-2d4a-4743-9912-6d0d2c0ef981.png)

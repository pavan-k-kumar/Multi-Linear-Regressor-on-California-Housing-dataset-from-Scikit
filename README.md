
![Logo](file:///C:/Users/admin/Downloads/California%20Housing%20Project.jpg)


# Multi-Linear Regressor on California Housing dataset.

Implementation of a Multi Linear Regressor on California Housing dataset obtained from Scikit.


##  Dataset and Implementation Details:

Dataset: California Housing dataset.

Source: https://scikit-learn.org/stable/modules/generated/sklearn.datasets.fetch_california_housing.html

Model: Linear Regressor

Input: 20640 samples with 8 features.

Output: Median House Price.

#### Data Set Characteristics:

Number of Instances: 20640

Number of Attributes: 8 numeric, predictive attributes and the target

Attribute Information:
- MedInc median income in block group
- HouseAge median house age in block group
- AveRooms average number of rooms per household
- AveBedrms average number of bedrooms per household
- Population block group population
- AveOccup average number of household members
- Latitude block group latitude
- Longitude block group longitude

Missing Attribute Values: NONE

This dataset was obtained from the StatLib repository. https://www.dcc.fc.up.pt/~ltorgo/Regression/cal_housing.html

The target variable is the median house value for California districts, expressed in hundreds of thousands of dollars ($100,000).

This dataset was derived from the 1990 U.S. census, using one row per census block group. A block group is the smallest geographical unit for which the U.S. Census Bureau publishes sample data (a block group typically has a population of 600 to 3,000 people).

A household is a group of people residing within a home. Since the average number of rooms and bedrooms in this dataset are provided per household, these columns may take surprisingly large values for block groups with few households and many empty houses, such as vacation resorts.

It can be downloaded/loaded using the sklearn.datasets.fetch_california_housing function.


## Model Evaluation and Results

R2 score: 0.5911695436410476

MSE: 0.5404128061709095


## Key Takeaway/s:

The accuracy of a model is more reliable and relevant with:
- large sets of sample data. The larger the volume of sample data, more accurate will be the predictability.
- The more the number of features, the more the predictability and accuracy of the model. 


## Execution (How to run):

The code is developed in Python using iPython Notebook on Google Colab. The file can be simply downloaded from this repository and run on any Python IDE.


## Raodmap

The regressor will be tested on more exhaustive models in the future.


## Packages & Libraries

Coding Language: Python

Packages: Sklearn, Matplotlib, Pandas


## Contact Me:

EMail: pavan.k.krishnappa@gmail.com

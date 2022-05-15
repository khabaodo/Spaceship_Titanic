# Spaceship_Titanic
In this project, I am going to implement what I learned along my journey to become a data scientist. The purpose of this project is to predict who will be transported to a new planet in the collision with a spacetime anomaly hidden within a dust cloud using machine learning models. I performed the cleaning and EDA process using Python on the Spaceship Titanic dataset, which can be found here: https://www.kaggle.com/competitions/spaceship-titanic. In the future, I will update this repository with the additional section of building machine learning models to predict the target variable.

## Skills used to clean the dataset:
### Cleaning
#### Completing: 
-  Filled in null values using median for countinuous features and mode for categorical features.
-  Dropped columns that might not be useful for training as there are too many unique values for feature engineering or reaching any significant conlusions
#### Creating - Feature Engineering:
- Splitted the 'Cabin' feature into two seperate columns that might contains useful patterns for the analysis process
- Created bins using `pd.cut` from the 'Age' feature.
#### Converting
- Used `LabelEncoder` to encode categorical features to numeric data that is more suitable for machine learning models.
- Utilized Pandas's `pd.get_dummies` to create dummy variables for machine learning models.

### EDA
- Implemented `groupby` and aggregate functions to discover any patterns that might related to the Transported feature
- Created barplot, boxplot, pairplot, and heatmap using `matplotlib` and `seaborn` libraries to discover features that have the strongest correlation with the Transported feature.

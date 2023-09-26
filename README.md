# Predicting Income with US Census DB

## Business Understanding

The objective of this exercise is to predict the income of a citizen (below or above $50k) based on various factors. This prediction can be useful for understanding income disparities and making informed decisions related to financial planning, resource allocation, and policy-making.

## Data Understanding

The data provided for this prediction task is in a CSV file containing 32,561 records from a census. The dataset includes several features such as age, education level, occupation, workclass, marital status, and more. It is important to note that there are unknown values present in some columns, such as occupation and workclass.

## Data Preparation

To handle the unknown records, they were labeled as 'unknown' and assigned a numerical value. This allows us to include these records in the analysis and modeling process without losing valuable information.

## Exploratory Analysis

Exploratory analysis was carried out on the dataset to gain insights into the relationships between different features and the target variable (income). The following insights were obtained:

- The dataset contains more males than females.
- The majority of individuals in the dataset are between the ages of 20 and 50.
- The majority of individuals have completed high school or some college education.
- The most common occupation categories are 'Exec-managerial', 'Prof-specialty', and 'Craft-repair'.
- The most common workclass categories are 'Private' and 'Self-emp-not-inc'.
- The majority of individuals in the dataset are married.
- Individuals with higher levels of education tend to have higher incomes.
- Individuals in certain occupation categories, such as 'Exec-managerial' and 'Prof-specialty', tend to have higher incomes.
- Individuals who work in certain workclass categories, such as 'Federal-gov' and 'Self-emp-inc', tend to have higher incomes.

## Modelling

Four different models were evaluated for this classification task: logistic regression, random forest, k-nearest neighbors, and decision tree. The logistic regression model performed the best with an accuracy of 82.5% on the test data.

## Training and Testing

The dataset was split into training and testing data in a 60:40 ratio. The training data was used to train the models, while the testing data was used to evaluate their performance and generalization ability.

## Evaluation

Each of the four models was compared and evaluated based on their performance metrics such as accuracy, precision, recall, and F1-score. The logistic regression model performed the best with an accuracy of 82.5% on the test data.

## Deployment

Deployment of the model was not within the scope of this exercise. However, the trained model can be further optimized and deployed in a production environment to make real-time predictions on new data.

By predicting income based on the US Census DB, we can gain valuable insights into income disparities and make informed decisions that can contribute to financial planning, resource allocation, and policy-making.
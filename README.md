# Machine Learning-Based GRE College Prediction
This project aims to predict college admission based on GRE scores using machine learning techniques. It utilizes a dataset that contains the GRE scores and college admission status of various applicants. The dataset is preprocessed to remove missing values and normalize the data, and then various machine learning models are trained on this data to predict college admission.

## Dataset
The dataset used for this project is the GRE College Admission dataset, which is available on Kaggle. It contains the following columns:

GRE Scores (out of 340) <br />
TOEFL Scores (out of 120) <br />
University Rating (out of 5) <br />
Statement of Purpose and Letter of Recommendation Strength (out of 5) <br />
Undergraduate GPA (out of 10) <br />
Research Experience (either 0 or 1) <br />
Chance of Admission (ranging from 0 to 1) <br />

## Preprocessing
Before training the machine learning models, the dataset is preprocessed to remove missing values and normalize the data. The missing values are replaced with the mean value of the corresponding column, and the data is normalized using the standard score normalization technique.

## Machine Learning Models
Several machine learning models are trained on the preprocessed dataset to predict college admission. These include:

Logistic Regression
K-Nearest Neighbors
Decision Tree
Random Forest
Gradient Boosting
The performance of these models is evaluated using various metrics such as accuracy, precision, recall, and F1-score.


# Overview:
This code conducts sentiment analysis on the Amazon Alexa dataset, aiming to predict whether a given input sentence has a positive or negative sentiment. It involves importing necessary libraries, performing exploratory data analysis (EDA), preprocessing the data, and building classification models.


## 1. Importing Required Libraries:

Imports essential libraries such as NumPy, pandas, matplotlib, seaborn, nltk, scikit-learn, WordCloud, etc.

## 2. Exploratory Data Analysis (EDA):

Loads the dataset and displays its shape and first few rows.
Checks for null values and removes any records with null values.
Creates a new column to store the length of the 'verified_reviews'.
Analyzes the data types of features.
Analyzes the 'rating' column, including visualizations like bar plots and pie charts.
Analyzes the 'feedback' column, including visualizations and identifying positive and negative reviews.
Analyzes the 'variation' column and visualizes the distribution of variations.
Analyzes the 'verified_reviews' column, including length analysis, word clouds for positive and negative reviews, and unique words in each feedback category.

## 3. Preprocessing and Modeling:

Preprocesses the 'verified_reviews' column by replacing non-alphabet characters, converting to lowercase, and stemming.
Uses Count Vectorizer to create bag-of-words.
Splits the data into training and testing sets.
Scales the features using MinMaxScaler.
Builds classification models including Random Forest, XGBoost, and Decision Tree Classifier.
Evaluates model performance using accuracy scores, confusion matrices, and cross-validation.
Applies grid search to find optimal parameters for Random Forest.
Saves the models and preprocessing objects for future use.

## 4. Results and Evaluation:

The Random Forest model achieved a training accuracy of 99.41% and testing accuracy of 94.18%.
The XGBoost model achieved a training accuracy of 97.05% and testing accuracy of 94.07%.
The Decision Tree Classifier achieved a training accuracy of 99.41% and testing accuracy of 91.01%.
The models were evaluated using confusion matrices to visualize true positive, true negative, false positive, and false negative predictions.
5. Conclusion:
This code provides a comprehensive analysis of sentiment in Amazon Alexa reviews, showcasing the effectiveness of machine learning models in predicting sentiment based on textual data.

Note: Ensure to update file paths and directory structures as needed before running the code.







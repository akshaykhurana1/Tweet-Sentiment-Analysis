# Tweet-Sentiment-Analysis
# Dataset
The dataset consists of text data from various tweets, with the target variable being the sentiment category, which includes neutral, positive, and negative sentiments.

# Problem Statement
This project focuses on sentiment analysis, a classification problem where the goal is to predict the sentiment of tweets based on the provided text data. The objective is to build an accurate model that can classify tweets into neutral, positive, and negative sentiment categories.

# Methodology
To address this problem, the following steps will be followed:<br>

**Data Preprocessing:** Clean the text data, handle any missing values, and perform text preprocessing techniques.<br>
**Model Selection:** Experiment with various machine learning algorithms such as Decision Tree, MLP Classifier, AdaBoost, Random Forest etc., to determine the best model for sentiment classification.<br>
**Model Evaluation:** Evaluate the performance of each model using appropriate metrics such as accuracy, precision, recall, and F1-score.<br>

# Repository Contents

**README.md:** Provides an overview of the project, including the dataset, problem statement, methodology, and repository contents.<br>
**Jupyter Notebook:** Contains the Python code for data preprocessing, model training, evaluation, and selection, specifically tailored for sentiment analysis of tweets.<br>
**Dataset:** Includes the dataset containing text data from tweets, categorized into neutral, positive, and negative sentiments.<br>

# Usage

• Clone the repository to your local machine.<br>
• Open the Jupyter Notebook and follow the instructions to execute the code cells.<br>
• Explore different models, evaluate their performance, and select the best model for sentiment analysis of tweets.
# Results
| S.No | Model                      | Root Mean Squared Error | Accuracy on Training Set | Accuracy on Testing Set |
|------|----------------------------|--------------------------|--------------------------|-------------------------|
| 1    | AdaBoostClassifier         | 0.802675                 | 69.741630                | 68.977438               |
| 2    | GradientBoostingClassifier | 0.713893                 | 76.232715                | 74.854440               |
| 3    | DecisionTreeClassifier     | 0.623415                 | 99.513282                | 75.491266               |
| 4    | XGBClassifier              | 0.612372                 | 83.833697                | 79.912664               |
| 5    | MLPClassifier              | 0.554524                 | 99.508734                | 79.949054               |
| 6    | RandomForestClassifier     | 0.546425                 | 99.513282                | 81.277293               |
| 7    | ExtraTreesClassifier       | 0.539050                 | 99.513282                | 82.132460               |


# Conclusion

Through the application of machine learning techniques, this project aims to develop a robust model capable of accurately predicting the sentiment of tweets. Understanding the sentiment conveyed in tweets is valuable for various applications, including market analysis, brand monitoring, and customer feedback analysis. Our model can provide valuable insights into the emotional tone of tweets, aiding businesses and organizations in making informed decisions based on public sentiment.

# PRODIGY INFOTECH DATA SCIENCE INTERNSHIP TASK 3
• Build a decision tree classifier to predict whether a customer will purchase a product or service based on their demographic and behavioral data. Use a dataset such as the Bank Marketing dataset from the UCI Machine Learning Repository.

• Here's my submission for Task 3 of the Data Science Internship at Prodigy Infotech. 

For this task, I focused on building a Decision Tree Classifier to predict customer purchase behavior using the Bank Marketing dataset. This involved data preparation, model training, and evaluation to assess the classifier's performance.

## Dataset
The dataset used for this task is [Bank Dataset](bank-additional.csv) which is uploaded in this repository. This dataset contains records of bank marketing campaigns, including demographic and behavioral data of customers, and whether they subscribed to a term deposit.

## Tools and Libraries used

1. Jupyter notebook
2. Pandas
3. Numpy
4. Matplotlip
5. Seaborn for visualization
6. Scikit-learn (for Decision Tree Classifier, train_test_split, metrics)
7. Decision Tree Classifier

# My process for building the Decision Tree Classifier involved several key steps:

• Data Loading and Initial Exploration: Loaded the bank-additional.csv dataset and performed initial checks for its structure and data types.

• Data Preprocessing:

• Handled categorical variables using one-hot encoding (e.g., job, marital, education, default, housing, loan, contact, month, day_of_week, poutcome).

• Identified and addressed any missing values (although the provided info shows no nulls, this would be a general step).

• Converted the target variable ('deposit' or 'y' - which appears to be 'deposit' based on your provided data info) into a numerical format (0 and 1).

• Model Training:

• Split the dataset into training and testing sets.

• Initialized and trained a Decision Tree Classifier on the training data.

• Model Evaluation:

• Made predictions on the test set.

• Evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score, and generated a classification report and confusion matrix.

## Conclusion
This task successfully demonstrated the application of a Decision Tree Classifier to predict customer subscription to a term deposit using the Bank Marketing dataset. Through comprehensive data preprocessing, including handling categorical variables, the dataset was prepared effectively for model training.

The trained Decision Tree Classifier provides insights into the factors influencing customer purchasing decisions. The evaluation metrics (accuracy, precision, recall, F1-score) and the confusion matrix offer a quantitative understanding of the model's performance, indicating its ability to correctly identify both positive and negative cases. While a decision tree model can be prone to overfitting, its interpretability makes it valuable for understanding the key features driving the predictions. This foundational analysis serves as a strong basis for further optimization or the exploration of more complex models.

Thank you for your time and consideration!

## For Contact Me
• Email: jainamkothari2804@gmail.com

• linkedin: [Jainam Kothari](https://www.linkedin.com/in/jainam-kothari-596377245/)

• Website: [Visit to my portfolio](https://jainamkothari-portfolio.netlify.app/)

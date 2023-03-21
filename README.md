# Spam Mail Prediction Model
## Problem Statement
The widespread use of email as a communication channel has led to an increase in unwanted or unsolicited emails, commonly known as spam. Spam emails often contain malicious content or fraudulent schemes, leading to security risks and financial losses for individuals and organizations. Traditional methods of filtering spam, such as rule-based or content-based filtering, are not always effective, as spammers are continually adapting their tactics. Therefore, there is a need for a reliable and accurate spam mail prediction model that can identify spam emails and prevent them from reaching the user's inbox. A reliable and accurate model for predicting spam emails would save time and resources for email users and email providers, leading to a more efficient and secure communication channel.
## Data Information
The dataset can be download using this [link](https://drive.google.com/file/d/1uzbhec5TW_OjFr4UUZkoMm0rpyvYdhZw/view)

The dataset contains the contents of the mail. The target values are either ham or spam.
## Project Pipeline
* Understanding the Data:  We load the data into a dataframe using Pandas and understand the features present in it. This helps in choosing the features that will be needed for the final model.
* Data Preprocessing: Data preprocessing is the essential step of cleaning and transforming raw data to make it suitable for machine learning models. As the current dataset is textual, we vectorize the features from text to numerical data using the TfidfVectorizer available in the sklearn library.
* Train/Test Split: The data is split into two sets: one for training the model and the other for testing its performance. We use the train_test_split function available in the sklearn library to perform the operation.
* Model Training and Evaluation: Here we can try different models until we get the desired level of performance on the given dataset. We use the XGBClassifier as our model available in the xgboost library. We also need to evaluate the models using appropriate evaluation metrics.


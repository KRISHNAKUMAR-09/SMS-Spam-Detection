# SMS-Spam-Detection

  This project aims to predict weather the SMS is Spam or Ham

# _Table of Contents_
       * Introduction
       * Dataset
       * Objectives
       * Model Building
       * Results

# _Introduction_
  The SMS Spam Detection system utilizes machine learning algorithms to analyze the content of text messages and determine whether they are spam or non-spam. The system is trained on a labeled dataset of SMS messages, where each message is labeled as spam or ham. It learns patterns and features from the data to make accurate predictions on new, unseen messages.

# _Dataset_
  The project utilizes a SMS dataset for training and testing the model. The dataset consists of 5570 rows and 5 columns. It does not contain any null values.

Dataset link: https://docs.google.com/spreadsheets/d/18xkLo_w-gQEgIdAbjXH7OaZSjrMGnL8g/edit?usp=sharing&ouid=115893872516422355941&rtpof=true&sd=true

# _Objectives_
The main objectives of this project are as follows:

   1. Explore and preprocess dataset.
   2. Understand the relationships between variables using visualization techniques.
   3. Perform encoding technique and data pre-processing to prepare the dataset for model training.
   4. Apply machine learning techniques to train a fraud detection model.
   5. Evaluate the model's performance using appropriate metrics.
   6. Save the best predicted model for future use.

# _Model Building_
  The dataset was analyzed using four different machine learning models: 
    Logistic Regression, 
    KNeighborsClassifier,
    DecisionTreeClassifier,
    Random Forest Classifier. 
  Among these models, the Random Forest Classifier performed the best in terms of predicting credit card transaction fraud, achieving an accuracy score of 99%.

# Results
  The **Random Forest Classifier** demonstrated its effectiveness in distinguishing between spam and ham messages, achieving an accuracy score of **99%**. This model can serve as a valuable tool for detecting the spam messages.

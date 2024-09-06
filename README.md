# SMS Spam or Ham Message Classification

This project focuses on classifying SMS messages as either spam or ham (not spam) using machine learning techniques. The dataset contains messages and their corresponding labels indicating whether they are spam or ham.

## Project Overview
The SMS Spam or Ham Classification project involves several stages of a data science workflow, including data preprocessing, text vectorization, model training, and performance evaluation.

### Key Components:
1. **Importing Necessary Libraries**  
   Libraries such as `pandas`, `numpy`, `matplotlib`, `seaborn`, and `scikit-learn` are used for data manipulation, visualization, text vectorization, and machine learning.

2. **Data Preprocessing**  
   - Load the dataset and handle missing values if any.
   - Encode the labels (`spam` or `ham`) into numerical values.
   - Split the dataset into training and testing sets.

3. **Text Vectorization**  
   - Convert text messages into numerical features using `TfidfVectorizer` to transform text data into a matrix of TF-IDF features.

4. **Model Selection and Training**  
   Train multiple machine learning models to classify messages, including:
   - **Logistic Regression**
   - **Random Forest Classifier**
   - **K-Nearest Neighbors Classifier**
   - **Naive Bayes Classifier** (MultinomialNB)

5. **Model Evaluation**  
   - Evaluate the performance of each model using metrics such as accuracy, confusion matrix, and classification report.
   - Compare the performance of different models to select the best one.

6. **Visualization**  
   - Visualize the distribution of spam vs. ham messages.
   - Display confusion matrices to show model performance.

## Dataset
The dataset used in this project contains the following columns:
- **label**: Indicates whether the message is `spam` or `ham`.
- **text**: The content of the SMS message.

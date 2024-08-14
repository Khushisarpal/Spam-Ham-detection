
# Spam-Ham Detection using NLP
This repository contains two Jupyter notebooks for detecting spam or ham (not spam) messages using Natural Language Processing (NLP) and machine learning techniques.


## Files in this Repository

###  machine_learning.ipynb

This notebook contains the machine learning pipeline for training and evaluating the spam or ham classifier. It includes data preprocessing, feature extraction, model training, and evaluation.
#### Key sections
1. Data Preprocessing: Cleaning and preparing the dataset for training.
2. Feature Extraction: Extracting features from text using techniques like TF-IDF.
3. Model Training: Training different machine learning models and selecting the best one.
4. Model Evaluation: Evaluating the model's performance using metrics like accuracy, precision, and recall.

### Spam_ham_detection.ipynb
This notebook focuses on the application of the trained model to new messages for spam or ham detection.
#### Key sections

1. Loading the Model: Loading the pre-trained model from the previous notebook.
2. Input Message Processing: Processing and transforming input messages for prediction.
3. Prediction: Classifying the input message as spam or ham.




## How to Use

Run the Notebooks:

1. Open the notebooks in Jupyter Notebook or Jupyter Lab.
2. Run machine_learning.ipynb to train and evaluate the model.
3. Run Spam_ham_detection.ipynb to classify new messages using the trained model.
## Dependencies

Ensure you have the following Python packages installed:

1. scikit-learn
2. pandas
3. numpy
4. nltk
5. jupyter

# ndsc_beginner
https://www.kaggle.com/c/ndsc-beginner/

# Lesson learned
https://medium.com/@steve7an/what-did-i-learn-from-my-first-kaggle-competition-e06060311ea9

## 31st place solution
For feature engineering, removed any long numeric string from the title and separated into three categories for Beauty, Fashion and Mobile for the training and prediction to simplify the prediction problem.

## Model tested
NDSC_CRF - Using Flair for text classification (https://github.com/zalandoresearch/flair/tree/master/resources/docs)
NDSC_CNN - Using Keras CNN to train the images
NDSC_Ensemble_voting - Simple submission csv majority vote, doesn't work well unless you have very diverse models?
NDSC_LOGR - Using Logistic regression, takes a long time to converge
NDSC_PAC - Using Passive Aggresive Classifier
Second_Half_NDSC - Using SGD Classifier - the best result amongst the bunch

## Setup
Clone this repository to your drive or just run it directly from Google Colab

## Running the solution
https://medium.com/@steve7an/how-to-test-jupyter-notebook-from-github-via-google-colab-7dc4b9b11a19

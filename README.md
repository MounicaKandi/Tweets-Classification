# Tweets-Classification

The main aim of this assignment is to perform tweets classification on 500 extracted tweets and create a Flask application to see if the tweets are advertisements or not.

## Process Followed

### Step 1: Extracting data using Twitter API.
Connect to Twitter using Twitter API and extract 500 tweets. The extracted data is stored in the "data-collection.csv" file.

The notebook link has the steps followed for extracting the tweets:
https://colab.research.google.com/drive/1hzr_TWdo6ZcBpcaqmDxtN33zxHiT8rCq?usp=sharing

### Step 2: Data Preprocessing
Preprocessing the data by removing all the unnecessary and unwanted characters. The "data-cleaning.csv" file has all the preprocessed data.

Below is the notebook link for data pre-processing:
https://colab.research.google.com/drive/1YnXxL8B-QIjvfzM8WyV-zekWNZFEtVVC?usp=sharing

### Step 3: Data Labelling
The next step would be labeling the data. I have categorized the data and labeled them as 0’s and 1’s. The tweets that can be considered an advertisement is labeled as 1 and the tweets that are not advertisements are labeled as 0.
All the labeled data is saved in the "data-labelling.csv" file.

### Step 4: Model Training
Once the labeling is done, I trained the model using Logistic Regression and Naïve Bayes classifier.

Notebook link for Model Training:
https://colab.research.google.com/drive/1dvRz_UZfnyfaBNG4IsSp8-_HgeMWGu2x?usp=sharing

### Step 5: Creating a pickle file
After saving the model, we must create a pickle file for the best model.

The model score for Logistic regression is 0.704

<img width="255" alt="image" src="https://user-images.githubusercontent.com/99624135/207203424-87ca548e-a997-4036-9a9e-a92b9f83fb13.png">

The model score for the Naive Bayes Classifier is 0.72

<img width="427" alt="image" src="https://user-images.githubusercontent.com/99624135/207203564-9db6dc83-de15-48b0-aee8-e7151ddf6c4a.png">

As the Naive Bayes Model is the best model, we are creating the pickle file for that model.






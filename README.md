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



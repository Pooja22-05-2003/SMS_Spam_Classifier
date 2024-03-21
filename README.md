# SMS Spam Classifier

This project implements a machine learning model for classifying SMS messages as either spam or not spam (ham). The dataset used in this project is obtained from the UCI Machine Learning (Kaggle).

## Steps

### 1. Data Cleaning
The dataset undergoes cleaning processes to handle missing values, remove duplicates, and address any inconsistencies within the data.

### 2. Exploratory Data Analysis (EDA)
Exploratory Data Analysis is performed to gain insights into the distribution of the data, identify patterns, and understand the characteristics of the dataset.

### 3. Data Preprocessing
Data preprocessing involves converting text data into a format suitable for machine learning algorithms. This step includes tokenization, removing stopwords, and vectorization of text data.

### 4. Model Building
Several machine learning models are built and trained on the preprocessed data to classify SMS messages. These models include but are not limited to Naive Bayes, Logistic Regression, Support Vector Machines, and Random Forest.

### 5. Best Accuracy Achieved after Applying Stacking Classifier
The Stacking Classifier is utilized to combine the predictions of multiple base classifiers, leading to improved performance. The following metrics are achieved with the Stacking Classifier:
- Accuracy: 0.9787234042553191
- Precision: 0.9328358208955224

## Dataset
The dataset used for this project can be found at (https://www.kaggle.com/datasets/uciml/sms-spam-collection-dataset?resource=download).

## Requirements
- Python 3
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Usage
1. Clone this repository.
2. Install the required dependencies using `pip install -r requirements.txt`.
3. Run the Jupyter Notebook or Python script to reproduce the results.

## Contributors
- [Pooja Kumari]

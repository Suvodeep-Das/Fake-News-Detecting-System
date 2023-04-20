# Fake News Detecting System

## Overview
The spread of fake news has recently attracted mass attention. This is a Jupyter Notebook tool for detecting fake news articles using natural language processing techniques. It uses a machine learning model trained on a dataset of labeled articles to classify articles as either "real" or "fake".

### Installation
To use this tool, you will need to have Python 3 installed on your computer. You can download Python from the official website: https://www.python.org/downloads/

You will also need to install the following Python libraries:

pandas
numpy
scikit-learn
nltk
jupyter
You can install these libraries using pip, the Python package manager. Run the following command in your terminal:
`pip install pandas numpy scikit-learn nltk jupyter`

### Usage
To use the fake news detector, open the 'Fake News Detection.ipynb' Jupyter Notebook in your browser. Run the code cells in the notebook to load the necessary libraries and functions, and to load the pre-trained machine learning model.

Then, enter the text of the article you want to classify into the designated cell in the notebook. Run the cell to classify the article as either "real" or "fake".

### Model Training
If you want to train your own machine learning model on a different dataset, you can use the 'Fake News Detection.ipynb' Jupyter Notebook. The dataset should be a CSV file with two columns: "title", "text" and "label". The "text" column should contain the text of each article, and the "label" column should contain either "real" or "fake" to indicate the true label of each article. This notebook takes you through the process of loading a dataset, preprocessing the text data, training a machine learning model, and evaluating the model's performance.

## Comparing Accuracies of Models

| Model                     | Accuracy     |
|:-------------------------:|:------------:|
| Logistic Regression       | 91.96%       |
| Decision Tree             | 80.63%       |
| Gradient Boosting         | 89.81%       |
| Random Forest             | 88.73%       |


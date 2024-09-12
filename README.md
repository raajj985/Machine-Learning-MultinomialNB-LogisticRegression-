
# Dinamalar Dataset ML Project

This repository contains a machine learning project aimed at classifying Tamil news articles from the Dinamalar dataset into various categories. The model leverages natural language processing (NLP) techniques to extract features from text data and train a classification model to predict news categories.

## Table of Contents
- [Project Overview](#project-overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dataset](#dataset)
- [Model Details](#model-details)
- [Evaluation](#evaluation)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)

## Project Overview
This project demonstrates the use of machine learning to classify news articles in Tamil from the **Dinamalar** dataset. The goal is to accurately predict the news category based on the title and content of the article.

## Features
- Natural Language Processing (NLP) with TF-IDF Vectorization
- Classification using Logistic Regression
- Performance evaluation through multiple metrics such as Confusion Matrix, ROC curve, and Precision-Recall curve
- Visualizations for a better understanding of model performance

## Installation
To run the project locally, you need to set up the necessary Python environment.

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/Dinamalar-ML-Project.git
   cd Dinamalar-ML-Project
   ```

2. Install dependencies using `pip`:
   ```bash
   pip install -r requirements.txt
   ```

## Usage
1. Prepare the dataset as shown in the provided sample format.
2. Run the Jupyter notebook (`Dinamalar-ML-Project.ipynb`) to preprocess, train, and evaluate the model.

### Running the Model
Once the environment is ready, follow the steps in the notebook to:
- Preprocess the text data using TF-IDF
- Train a logistic regression model
- Evaluate the performance through visualizations and metrics

### Example Plots:
- **Confusion Matrix**: A visualization to help understand the accuracy of model predictions.
- **ROC Curve**: Shows the trade-off between true positive rate and false positive rate.
- **Precision-Recall Curve**: Evaluates the precision and recall trade-offs for each category.
- **Feature Importance**: Displays the most influential words in predicting the category of a news article.

## Dataset
The dataset consists of Tamil news articles from the **Dinamalar** newspaper, labeled with categories. The data is preprocessed and converted to numerical format using TF-IDF vectorization.

### Sample Dataset Structure:
- `news_id`: Unique identifier for each article
- `news_date`: Date and time of the news article
- `news_category`: Category of the article (e.g., "Tamil", "India")
- `news_title`: Title of the news article
- `news_article`: Full text of the news article

Ensure that the dataset is structured in this format for smooth processing.

## Model Details
- **Text Vectorization**: The text data is transformed into numerical vectors using TF-IDF (Term Frequency-Inverse Document Frequency).
- **Algorithm**: Logistic Regression is applied for classifying news articles.
- **Label Encoding**: Categories are encoded into integer labels using `LabelEncoder` for compatibility with the model.

## Evaluation
The model’s performance is assessed using the following metrics:
- **Confusion Matrix**: Helps visualize the model's classification performance.
- **ROC Curve**: Evaluates the classifier's ability to distinguish between different categories.
- **Precision-Recall Curve**: Useful for understanding the precision and recall balance.

## Results
The model performs well in predicting the categories of news articles in the **Dinamalar** dataset. Detailed evaluation metrics and plots are provided in the notebook for further insights.

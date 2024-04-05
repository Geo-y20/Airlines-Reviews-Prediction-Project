# Airlines Reviews Prediction Project

## Overview

This project aims to predict the ratings of airline reviews using natural language processing (NLP) techniques. The goal is to analyze customer feedback and develop predictive models to estimate the satisfaction ratings associated with each review.

## Dataset

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/kanchana1990/singapore-airlines-reviews/data). It contains the following columns:

- `published_date`: Date and time of review publication.
- `published_platform`: Platform where the review was posted.
- `rating`: Customer satisfaction rating, from 1 (lowest) to 5 (highest).
- `type`: Specifies the content as a review.
- `text`: Detailed customer feedback.
- `title`: Summary of the review.
- `helpful_votes`: Number of users finding the review helpful.

## Project Structure

- `notebooks/`: Jupyter notebooks for data analysis, preprocessing, modeling, and evaluation and containg Dataset.
- `README.md`: This file providing an overview of the project.

## Setup and Installation

To run the project locally, follow these steps:

1. Clone this repository to your local machine:
   ```
   git clone https://github.com/Geo-y20/Airlines-Reviews-Prediction-Project.git
   ```


2. Install the required dependencies:
   ```
   pip install -r requirements.txt
   ```

4. Run the Jupyter notebooks in the `notebooks/` directory to analyze the data, preprocess it, train models, and evaluate their performance.

## Usage

1. Open the Jupyter notebooks in the `notebooks/` directory to run each step of the project pipeline.
2. Follow the instructions and comments within each notebook to understand the analysis, preprocessing, modeling, and evaluation processes.
3. Experiment with different techniques and parameters to improve model performance and gain insights from the data.

## ***Conclusion and Insights of This project :***

* The accuracy, precision, and recall scores suggest that the models perform moderately well in predicting the ratings of airline reviews.

* The similarity in performance between SVM and Random Forest models using both Bag of n-grams and TF-IDF representations indicates that the choice of text representation technique has a limited impact on model performance in this case. So from statsical result show that ***SVM is better***
* SVM and Random Forest models using Bag of n-grams and TF-IDF representations achieved accuracy scores ranging from approximately **0.5725 to 0.6205**.

## ***Further Analysis:***

1. It would be beneficial to compare these performance metrics with a baseline model or other benchmark results to assess whether the models provide significant improvements.


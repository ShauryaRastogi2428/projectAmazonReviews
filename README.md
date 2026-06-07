# TrendCart Sentiment Analysis Project

## Project Overview

This project demonstrates how Machine Learning can be used to automatically classify customer product reviews into Positive, Neutral, and Negative sentiments.

The objective is to help TrendCart Ltd understand customer feedback more efficiently and support data-driven business decisions.

---

## Technologies Used

* Python 3.x
* Pandas
* NumPy
* Scikit-Learn
* Matplotlib

---

## Machine Learning Workflow

1. Load and clean review dataset
2. Create sentiment labels from ratings
3. Perform Exploratory Data Analysis (EDA)
4. Convert text into numerical features using TF-IDF
5. Train Logistic Regression model
6. Evaluate model performance
7. Generate sentiment predictions
8. Visualize sentiment distribution

---

## Dataset

Dataset File:

```text
1429_1.csv
```

Columns Used:

* reviews.text
* reviews.rating

Sentiment Mapping:

* Rating 4–5 → Positive
* Rating 3 → Neutral
* Rating 1–2 → Negative

---

## Installation

Install required packages:

```bash
pip install pandas numpy matplotlib scikit-learn
```

---

## How to Run

1. Place the dataset file (`1429_1.csv`) in the project folder.
2. Open Jupyter Notebook or Google Colab.
3. Run all cells in `TrendCart_Sentiment_Analysis.ipynb`.
4. The model will train automatically.
5. Results and graphs will be displayed.
6. A new file named `predicted_reviews.csv` will be generated.

---

## Output Files

### 1. predicted_reviews.csv

Contains:

* Review Text
* Rating
* Actual Sentiment
* Predicted Sentiment

### 2. Visualizations

* Sentiment Distribution Pie Chart
* Predicted Sentiment Bar Graph

### 3. Model Evaluation

* Accuracy Score
* Classification Report
* Confusion Matrix

---

## Business Benefits

* Faster customer feedback analysis
* Reduced manual effort
* Identification of negative customer experiences
* Better product decision-making
* Foundation for future AI adoption

---

## Author

Machine Learning Intern

TrendCart Sentiment Analysis Proof-of-Concept Project

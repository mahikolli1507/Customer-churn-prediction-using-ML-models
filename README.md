# Customer Churn Prediction in Subscription-Based Services

A Machine Learning-based system for predicting customer churn in telecom subscription services. The project analyzes customer demographics, service usage, and interaction history to identify customers likely to discontinue their subscriptions.

The project compares the performance of:

* `Logistic Regression`
* `Decision Tree`
* `K-Nearest Neighbors (KNN)`
* `Random Forest`
* `Support Vector Machine (RBF)`

The system also includes:

* Data preprocessing and feature engineering
* Feature selection techniques
* Correlation analysis and visualization
* Confusion matrix evaluation
* Model performance comparison

## Project Structure

```text
project/
  data/                   Telecom churn dataset
  preprocessing/          Data cleaning and feature engineering
  models/                 ML model implementations
  visualization/          Pair plots and correlation matrix
  evaluation/             Performance metrics
  main.py                 Main execution script
```

## Features

* Predict customer churn using Machine Learning
* Compare multiple classification algorithms
* Analyze customer behavior patterns
* Generate correlation and feature analysis visualizations
* Evaluate models using Accuracy, Precision, Recall, F1-Score, and ROC-AUC
* Support customer retention decision-making

## Dataset

The project uses the Orange Telecom Churn Dataset containing:

* Customer account information
* Subscription plans
* Call usage statistics
* Customer service interactions
* Churn status

Dataset size:

```text
Training Set: 2666 customers
Testing Set: 667 customers
Total Records: 3333
```

## Requirements

### Python Packages

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## How To Run

1. Place the dataset inside the project directory.
2. Install the required dependencies.
3. Run the project:

```bash
python main.py
```

## Results

Among all models, `Random Forest` achieved the best overall performance with high accuracy, precision, and balanced recall, making it the most suitable model for telecom churn prediction.

## Notes

* Feature selection is used to improve prediction accuracy.
* Correlation analysis helps identify important churn indicators.
* Model performance is evaluated using confusion matrices and classification metrics.
* Results can support proactive customer retention strategies.

## License

No license file is currently included. Add one if you plan to share or publish the project.

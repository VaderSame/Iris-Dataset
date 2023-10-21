# Iris Dataset 
This repository contains a machine learning project to classify different types of iris plants based on their features. The dataset used is the famous Iris dataset, often used in pattern recognition and machine learning literature.

## About the Dataset

The Iris dataset is one of the most well-known datasets in the field of pattern recognition. It was introduced by Ronald A. Fisher and consists of 150 instances, with 3 classes of iris plants, each containing 50 instances. One class is linearly separable from the other two, while the remaining two classes are not linearly separable from each other. This GitHub repository comprehensively analyzes the popular Iris dataset using various machine learning algorithms, including Logistic Regression, Support Vector Machines (SVM), and Random Forest. Additionally, it explores the impact of different data split ratios (80-10-10 vs. 60-20-20) on model performance.

## Task

The primary goal of this project is to predict the class of iris plants based on their features. To achieve this, we perform several steps, as outlined below:

1. **Exploratory Data Analysis (EDA):** We start by exploring the dataset using histograms to gain insights into the distribution of various features.

2. **Target Variable Encoding:** We convert the target variable into a numeric format to prepare it for machine learning algorithms.

3. **Data Splitting:** We experiment with two different ratios of training, validation, and test data: 60-20-20 and 80-10-10. These splits help us evaluate model performance under different data allocation scenarios.

4. **K-Fold Cross-Validation:** We implement K-Fold cross-validation to ensure robust model evaluation and mitigate overfitting.

5. **Hyperparameter Tuning:** For three selected algorithms (Logistic Regression, Support Vector Machine, and Random Forest), we implement Grid Search to find optimal hyperparameters. This step enhances model performance and generalization.

6. **Performance Analysis:** We rigorously analyze model results on the validation and test sets, comparing key metrics like precision, recall, accuracy, and latency. This analysis helps us identify the best-performing model.

7. **Choosing the Best Split Ratio:** Based on the experiments, we determine which data split ratio (60-20-20 or 80-10-10) works best for this dataset and problem.

## Results and Findings

In our experiments, we found that all models—Logistic Regression, Support Vector Machine, and Random Forest—performed exceptionally well, showcasing high accuracy, precision, and recall. Model latencies were consistently low, indicating efficient predictions.

Our analysis suggests that choosing between the two data split ratios depends on specific project objectives and available computational resources:

- The 80-10-10 split offers a more significant portion of data for training but results in smaller validation and test sets.
- The 60-20-20 split provides a more balanced data allocation for validation and testing.

Both splits are valid options, and the choice should align with the project's goals and dataset characteristics.

## Conclusion

This machine-learning project demonstrates the power of classification algorithms in identifying different iris plant species. It underscores the significance of selecting appropriate data split ratios and performing rigorous hyperparameter tuning to achieve optimal model performance.

Feel free to explore the code and data to delve deeper into the project's details.

For a step-by-step guide on how to recreate this project or leverage the code for your own use case, please take a look at the accompanying Jupyter Notebook.

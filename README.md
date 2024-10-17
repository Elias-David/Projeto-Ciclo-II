# Credit Scoring Models - Alpha EdTech Challenge 2

## Project Overview

This repository contains a project developed by Alpha EdTech students as part of the Cycle 2 final challenge. The group members involved in this project are:

- Arthur Malcher
- Guilherme Barcelos
- Miguel Claudino
- Taynara Morais
- Felipe Cruz
- Elias David

The goal of the project is to develop, train, and evaluate two machine learning models for credit scoring prediction: **AdaBoost** and **CatBoost**. The models will be used to predict whether a loan will be repaid (label 1) or forfeited (label 0).

## Objectives

The main objectives of this project are:

1. **Data Understanding and Preparation**: Conduct an initial data exploration, handle missing values, analyze correlations, and determine the need for normalization or standardization.

2. **Model Training**: Train two boosting models, AdaBoost and CatBoost, to predict credit scoring outcomes, with proper hyperparameter optimization.

3. **Evaluation Metrics**: Evaluate the models using various metrics, such as:
   - Accuracy
   - Precision, Recall, and F1-Score
   - Confusion Matrix
   - ROC Curve and AUC
   - Log-loss/Binary Cross-entropy (if applicable)

4. **Hyperparameter Optimization**: Use techniques such as **Grid Search**, **Random Search**, and **Bayesian Optimization** to optimize model hyperparameters and improve performance.

5. **Model Interpretation**: Analyze the most important variables that impact model predictions and check for overfitting using cross-validation.

6. **Documentation and Conclusion**: Document the entire process, record the results obtained, and draw conclusions from the experiments.

## Steps Involved

### 1. Data Understanding and Preparation
- Import and explore the dataset.
- Check for missing values and handle them using appropriate imputation techniques.
- Analyze feature distributions and correlations.
- Perform data normalization or standardization if necessary.

### 2. Model Training and Evaluation
- Train the AdaBoost and CatBoost models using the prepared dataset.
- Optimize hyperparameters using different techniques.
- Evaluate the model performance using metrics like accuracy, precision, recall, F1-score, ROC-AUC, etc.

### 3. Hyperparameter Tuning
- Use **Grid Search**, **Random Search**, and optionally **Bayesian Optimization** for hyperparameter tuning.
- Retrain models using optimized hyperparameters.

### 4. Model Interpretation and Overfitting Analysis
- Extract the importance of features for both AdaBoost and CatBoost models.
- Use K-Fold cross-validation to assess and compare model performance to detect overfitting.

### 5. Results Documentation
- Document all model configurations and training results in a detailed report.
- Include relevant plots and tables for visualization.

### 6. Conclusion
- Summarize the findings of the project.
- Highlight model performance and challenges encountered during development.

## Technologies Used
- **Python**: Programming language for data analysis and modeling.
- **Scikit-Learn**: Used for model training, evaluation, and hyperparameter tuning.
- **Pandas and NumPy**: For data manipulation and analysis.
- **Matplotlib and Seaborn**: For data visualization.
- **CatBoost and AdaBoost**: Boosting algorithms used for model training.

## Contributors
This project was developed by the following Alpha EdTech students:
- Arthur Malcher
- Guilherme Barcelos
- Miguel Claudino
- Taynara Morais
- Felipe Cruz
- Elias David

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
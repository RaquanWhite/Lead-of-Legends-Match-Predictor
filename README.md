# League of Legends Match Predictor

### Machine Learning | PyTorch | Python | Logistic Regression

## Project Overview

This project demonstrates the development of a machine learning classification model using Python and PyTorch to predict League of Legends match outcomes based on gameplay statistics.

Developed as part of the **IBM Introduction to Neural Networks and PyTorch** course, this project explores the complete machine learning workflow, including data preprocessing, model development, training, optimization, evaluation, and model persistence.

The project is part of my growing AI/ML engineering portfolio as I transition from engineering and infrastructure planning into artificial intelligence and software development.

## Technologies Used

- **Python** — Core programming language
- **PyTorch** — Machine learning model development and training
- **Pandas** — Data manipulation and preprocessing
- **Scikit-learn** — Dataset splitting, standardization, and evaluation
- **Matplotlib** — Data visualization
- **Google Colab** — Cloud-based notebook development

## Project Workflow

### 1. Data Preprocessing

- Loaded and explored the League of Legends dataset.
- Separated gameplay features from match outcomes.
- Split the dataset into 80% training and 20% testing.
- Standardized numerical features using StandardScaler.
- Converted the data into PyTorch tensors.

### 2. Model Development

Implemented a binary logistic regression classifier using PyTorch's neural network framework.

The model uses a linear layer and sigmoid activation function to estimate the probability of winning a match.

### 3. Model Training

- Trained the model for 1,000 epochs.
- Used Binary Cross-Entropy Loss.
- Applied stochastic gradient descent (SGD).
- Implemented backpropagation and gradient-based parameter updates.

### 4. Model Optimization

Explored L2 regularization to control model complexity and tested multiple learning rates to compare model performance.

### 5. Model Evaluation

Evaluated performance using:

- Training and testing accuracy
- Confusion matrix
- Classification report
- Precision, recall, and F1-score
- Receiver Operating Characteristic (ROC) curve
- Area Under the Curve (AUC)

### 6. Model Persistence

Saved and reloaded the trained model using PyTorch's state dictionary functionality.

### 7. Feature Importance

Analyzed learned model weights to understand how gameplay statistics influenced predictions.

## Results

| Metric | Result |
|---|---|
| Initial Training Accuracy | 55.37% |
| Initial Test Accuracy | 51.00% |
| Optimized Training Accuracy | 54.62% |
| Optimized Test Accuracy | 51.00% |
| ROC AUC | Approximately 0.502 |
| Best Learning Rate in Tuning Experiment | 0.01 |

The model achieved approximately 51% test accuracy, indicating performance close to random guessing.

Although the model did not demonstrate strong predictive performance, the project successfully implemented and evaluated an end-to-end machine learning workflow.

The results also highlight the importance of data quality, feature engineering, model selection, and robust evaluation.

## Feature Importance

The largest positive model weights were associated with:

1. Gold earned
2. Kills
3. Wards placed

These weights describe the fitted model's behavior, rather than establishing reliable gameplay predictors or causal relationships.

## Future Improvements

Potential improvements include:

- Exploring larger and more representative datasets
- Engineering additional gameplay features
- Experimenting with multilayer neural networks
- Comparing logistic regression with more advanced classifiers
- Using cross-validation and improved hyperparameter selection
- Investigating data quality and class distributions

## Key Skills Demonstrated

Data preprocessing, supervised machine learning, PyTorch model implementation, backpropagation, optimization, binary classification, model evaluation, and feature interpretation.

## About the Developer

I am an engineering and infrastructure planning professional transitioning into AI and machine learning engineering, with a focus on developing practical software solutions for real-world challenges.

My long-term interests include applying artificial intelligence to construction technology, infrastructure planning, automation, and predictive analytics.

**GitHub:** [RaquanWhite](https://github.com/RaquanWhite)

## Acknowledgment

Project completed as part of IBM's *Introduction to Neural Networks and PyTorch* course on Coursera.

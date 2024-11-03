# Mushroom Classification Project 🍄

This project is a machine learning solution for classifying mushrooms as either edible or poisonous based on several distinguishing features. The dataset used is from Kaggle’s mushroom classification dataset, which contains categorical data about mushrooms, such as cap shape, color, and odor. The goal is to use machine learning models to accurately predict mushroom edibility, ensuring consumer safety and aiding mycologists in species identification.

## Table of Contents
1. [Project Overview](#project-overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Dataset Information](#dataset-information)
5. [Model Training and Evaluation](#model-training-and-evaluation)
6. [Contributors](#contributors)

---

### Project Overview

This project explores the use of various machine learning algorithms, including:
- **Logistic Regression**
- **Decision Trees**
- **Random Forest**
- **Neural Networks**
- **Naive Bayes**
- **XgBoost**
- **Support Vector**

The models were tuned with hyperparameter optimization and evaluated using key metrics such as accuracy, precision, recall, and F1 score.

### Installation

To set up the project on your local machine:
1. Clone the repository:
   ```bash
   git clone https://github.com/Priyanshu1303d/Mushroom_Classification.git
   cd mushroom-classification
2. Install the dependencies:
   ```bash
   pip install -r requirements.txt
3. Download the mushroom dataset (if not already included) from Kaggle’s mushroom classification dataset and place it in the root directory.


# Usage
1. Run the Jupyter Notebook or the Python file containing the model pipeline:
   ```bash
   jupyter notebook mushroom_classification.ipynb
2. To train the models, split the dataset as shown in the notebook:
   1. 70% for training
   2. 15% for validation
   3. 15% for testing

3. The models are automatically tuned and evaluated using GridSearchCV, and the best-performing model is saved to the best_model.joblib file.

4. Use the following command to load the saved model for predictions:
   ```bash
   import joblib
   model = joblib.load("./best_model.joblib")

# Dataset Information
The dataset contains various features about mushroom characteristics, such as:

1. Cap shape, color, surface
2. Odor
3. Gill size, spacing, and color
4. Stalk features
5. Each mushroom is labeled as either edible or poisonous.

# Model Training and Evaluation
The models were trained using a pipeline that includes:

1. Data preprocessing with encoding of categorical features
2. Dimensionality reduction through feature selection
3. Model training with cross-validation and hyperparameter tuning
4. Performance evaluation on accuracy, precision, recall, and F1 score metrics


## Contributors

- [Priyanshu Kumar](https://github.com/Priyanshu1303d)
- [Sanskar Modi](https://github.com/sanskarmodi8)

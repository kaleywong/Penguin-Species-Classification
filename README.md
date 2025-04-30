# Penguin Species Classification

## Project Overview

This project involves building a classification model to predict the species of penguins based on various physical features, such as **culmen length**, **culmen depth**, **flipper length**, and **body mass**. The dataset used is from the **Palmer Penguins** dataset, which contains information about penguins from three species: **Adelie**, **Chinstrap**, and **Gentoo**.

The objective of the project is to build a machine learning model that can accurately classify penguin species based on these features. We use a **Random Forest Classifier** for the classification task.

## Dataset

The dataset consists of the following columns:
- **species**: The target variable, representing the species of the penguin (Adelie, Chinstrap, Gentoo).
- **island**: The island where the penguin was observed (Biscoe, Dream, Torgersen).
- **culmen_length_mm**: Length of the penguin's culmen (bill) in millimeters.
- **culmen_depth_mm**: Depth of the penguin's culmen in millimeters.
- **flipper_length_mm**: Length of the penguin's flipper in millimeters.
- **body_mass_g**: The body mass of the penguin in grams.
- **sex**: The gender of the penguin (Male, Female).

### Data Source:
[Palmer Penguins Dataset](https://www.kaggle.com/datasets/planetpoet/palmer-archipelago-penguin-data)

## Project Workflow

1. **Exploratory Data Analysis (EDA)**:
   - The dataset was analyzed to understand feature distributions and relationships.
   - Visualizations, such as **pairplots** and **correlation heatmaps**, were used to explore the data.
   - The distribution of the target variable and the correlation between features were examined to identify potential patterns and relationships.

2. **Model Building**:
   - A **Random Forest Classifier** was trained using the features of the dataset to predict penguin species.
   - Hyperparameters were tuned to achieve optimal performance.
   - Model evaluation metrics such as **accuracy**, **precision**, **recall**, and **F1-score** were used to assess the model's performance.

3. **Model Evaluation**:
   - The model's performance was evaluated using a **confusion matrix** and **classification report**.
   - The model achieved high accuracy (99%), with minor misclassifications observed in one species (Chinstrap).

4. **Next Steps**:
   - Explore other models (e.g., XGBoost, SVM) for potential improvements.
   - Perform cross-validation to ensure model robustness.
   - Tune hyperparameters further to enhance model performance.



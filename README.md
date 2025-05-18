# Mushroom Classification

This project uses a machine learning model to classify mushrooms as **edible** or **poisonous** based on their physical characteristics. The dataset was obtained from [Kaggle: Mushroom Classification](https://www.kaggle.com/datasets/uciml/mushroom-classification).

## Dataset Overview

The dataset contains **8,124** entries with **22 categorical features**. Each row describes one mushroom with features like cap shape, color, gill size, odor, etc., and the target column (`class`) indicates whether the mushroom is edible (`e`) or poisonous (`p`).

### Sample Features:
- `cap-shape`
- `cap-color`
- `gill-size`
- `gill-color`
- `odor`
- `habitat`
- `spore-print-color`

All features are **categorical** and have been encoded using label encoding for machine learning model training.

---

## Project Workflow

1. **Import Libraries**
2. **Load Dataset**
3. **Data Preprocessing**
   - Label Encoding of Categorical Features
   - Null Value Check
4. **Exploratory Data Analysis (EDA)**
   - Count Plots for Class Distribution
   - Feature Correlation
5. **Model Training**
   - Train-Test Split
   - Model used: Random Forest Classifier
   - Evaluation Metrics: Accuracy, Confusion Matrix
6. **Model Evaluation**
   - Accuracy Score
   - Confusion Matrix Visualization
7. **Model Performance**
   - Achieved accuracy: ~**99%**

---


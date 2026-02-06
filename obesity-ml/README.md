# Obesity Level Prediction

This project uses machine learning models to predict obesity levels based on demographic and lifestyle features.

---

## Dataset
The dataset contains information about individuals, including:

- Age
- Height
- Weight
- Eating habits
- Physical activity
- Family history
- Transportation habits
- Other lifestyle-related factors

**Target variable:**
- Obesity level category

---

## Project Workflow

### 1. Data Exploration
- Dataset overview
- Target class distribution
- Key feature visualisations

### 2. Data Preprocessing
- Separation of numerical and categorical features
- Missing value handling
- Feature scaling
- One-hot encoding for categorical variables
- Pipeline using `ColumnTransformer`

### 3. Model Training
Three models were trained and compared:

- Logistic Regression
- Random Forest
- Gradient Boosting

### 4. Model Evaluation
Models were evaluated using:

- Accuracy
- Precision
- Recall
- F1-score
- Confusion matrix

---

## Results

| Model | Accuracy | Macro F1-score |
|------|----------|----------------|
| Logistic Regression | ~0.87 | ~0.87 |
| Random Forest | ~0.93 | ~0.93 |
| Gradient Boosting | **~0.96** | **~0.96** |

**Best model:** Gradient Boosting

---

## Feature Importance
The most influential features included:

- Weight
- Age
- Height
- Frequency of vegetable consumption
- Number of meals per day
- Physical activity frequency

This shows that both **physical measurements** and **lifestyle habits** play a key role in obesity prediction.

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn

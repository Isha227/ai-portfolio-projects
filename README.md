# AI Portfolio Projects

This repository contains two machine learning and optimisation projects developed during my MSc in Artificial Intelligence.  
The projects demonstrate practical skills in supervised learning, optimisation algorithms, model evaluation, and experimental analysis.

---

## Project 1: Obesity Level Prediction (Machine Learning)

A supervised machine learning project that predicts obesity levels using demographic and lifestyle features.

### Workflow
- Exploratory data analysis (EDA)
- Data preprocessing pipeline:
  - Missing value handling
  - Feature scaling
  - Categorical encoding
- Model comparison:
  - Logistic Regression
  - Random Forest
  - Gradient Boosting
- Performance evaluation:
  - Accuracy
  - Precision, Recall, F1-score
  - Confusion matrix
- Feature importance analysis

### Results
- **Best model:** Gradient Boosting
- **Accuracy:** ~0.96
- The model captures both physical and behavioural factors influencing obesity levels.

### Skills Demonstrated
- Supervised machine learning
- Model evaluation and comparison
- Feature engineering
- Data visualisation
- Model interpretation

**Project folder:** `obesity-ml/`

---

## Project 2: Travelling Salesman Problem Optimisation

An optimisation project comparing two metaheuristic algorithms—Simulated Annealing (SA) and Genetic Algorithm (GA)—on a Travelling Salesman Problem instance with 50 cities.

### Problem
Given a set of cities with (X, Y) coordinates, find the shortest route that:
- Visits each city exactly once
- Returns to the starting city

### Algorithms Implemented
- Simulated Annealing
- Genetic Algorithm

### Experiments
- Baseline random route
- SA optimisation
- GA optimisation
- Convergence analysis
- Scalability tests on subsets (10–50 cities)

### Results (50 cities)
- **Random baseline:** ~2766
- **Simulated Annealing:** ~832.6
- **Genetic Algorithm:** ~831.8

The Genetic Algorithm achieved a slightly shorter final route, especially on larger problem sizes.

### Skills Demonstrated
- Combinatorial optimisation
- Metaheuristic algorithms
- Experimental evaluation
- Convergence analysis
- Algorithm comparison

**Project folder:** `tsp-optimisation/`

---

## Tools and Libraries
- Python
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

---

## Repository Structure

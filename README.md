# Part 1 - Neural Network Fundamentals and Training Behavior Analysis

## Project Overview
This project focuses on building and analyzing a simple feed-forward neural network to predict customer churn using a structured dataset with 17 features.

## Dataset
- Total records: 2000
- Highly imbalanced (only ~1.55% churn cases)
- Features include customer usage, payment behavior, satisfaction, etc.

## Approach

**1. Dataset Understanding**  
Explored shape, data types, missing values, and target distribution.

**2. Data Preprocessing**  
- One-hot encoded categorical columns  
- Scaled numerical features using StandardScaler  
- Used stratified train-test split

**3. Neural Network Building**  
Built a feed-forward model using Keras:  
Input → 64 (ReLU) → 32 (ReLU) → 16 (ReLU) → 1 (Sigmoid)

**4. Training & Evaluation**  
Achieved ~98.25% test accuracy. Generated confusion matrix to analyse performance.

**5. Hyperparameter Experimentation**  
Compared 3 different configurations (different layers, learning rates, and class weights).

**6. Final Reflection**  
Learned the importance of activation functions, learning rate tuning, and handling imbalanced data.

## Technologies Used
- Python, Pandas, Scikit-learn  
- TensorFlow / Keras  
- Matplotlib & Seaborn

## Results
Model comparison table and evaluation plots are available in the `results/` folder.

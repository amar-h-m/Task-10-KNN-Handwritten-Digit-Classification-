Task 10 – KNN: Handwritten Digit Classification

# Objective
The objective of this task is to implement the K-Nearest Neighbors (KNN) algorithm to classify handwritten digits using the Scikit-learn Digits dataset. This task demonstrates distance-based learning, preprocessing, and model evaluation.

# Dataset Used
- Scikit-learn Digits Dataset
- Contains 1797 samples of handwritten digits (0–9).
- Each image is 8×8 pixels flattened into 64 numerical features.

# Tools & Libraries
- Python
- NumPy
- Matplotlib
- Scikit-learn
- VS Code (Jupyter Notebook)

# Steps Performed
- Dataset Loading & Inspection
- Loaded the digits dataset using load_digits().
- Data Visualization
- Visualized sample handwritten digit images.
- Train–Test Split
- Split dataset into 80% training and 20% testing sets.
- Feature Scaling
- Applied StandardScaler to normalize pixel values.
- Model Training
- Trained KNN model with K = 3.
- Hyperparameter Tuning
- Tested multiple K values (3, 5, 7, 9).
- Model Evaluation
- Evaluated using accuracy score and confusion matrix.
- Visualization of Results
- Plotted Accuracy vs K.
- Displayed sample predictions.

# Key Insights
KNN performance depends heavily on the choice of K.
Feature scaling is essential for distance-based algorithms.
Higher K values reduce overfitting but may increase bias.
Confusion matrix provides detailed error analysis.

# Final Outcome
A complete KNN classification model was built and evaluated for handwritten digit recognition. The task provided practical understanding of instance-based learning and model tuning.

# Repository Contents
Task10_KNN_Digits.ipynb – Notebook with full workflow
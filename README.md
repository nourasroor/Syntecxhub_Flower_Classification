# Syntecxhub_Flower_Classification

# Objective
To build and compare two classification models — Logistic Regression and Decision Tree —
that predict the type of iris flower based on its physical characteristics

# Dataset
Name: Iris Dataset (from sklearn.datasets)
Samples: 150 flowers
Classes:
        Setosa
        Ver  sicolor
        Virginica
Features:
        Sepal Length
        Sepal Width
        Petal Length
        Petal Width

# Technologies Used
Language: Python
Libraries: NumPy, Pandas, Matplotlib, Seaborn, scikit-learn
Environment: Google Colab

# Project Workflow
Data Loading & Exploration
    Loaded the Iris dataset and visualized samples.
    Plotted scatter plots to show the separation between flower types.
Data Preprocessing
    Split the data into training and testing sets (80%-20%).
    Ensured balanced class distribution using stratified sampling.
Model Training
Trained two models:
    Logistic Regression
    Decision Tree Classifier
Evaluation & Comparison
    Calculated accuracy, precision, recall, and F1-score.
    Plotted and analyzed the confusion matrix.
    Visualized the Decision Tree structure.

# Results
Model	Accuracy
Logistic Regression	100%
Decision Tree	96.7%

# Conclusion:
Both models performed extremely well. Logistic Regression achieved perfect accuracy,
while Decision Tree provided high interpretability with slightly lower accuracy.

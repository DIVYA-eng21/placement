📊  Placement Prediction using Machine Learning:
 
This project involves predicting whether a student will be placed based on features like iq and cgpa using three popular machine learning classification algorithms:

                    Support Vector Machine (SVM)
                    Logistic Regression
                    Naive Bayes

📁 Dataset Description
The dataset used is placement-dataset.csv and contains the following columns:

                    iq – numeric score representing intelligence quotient
                    cgpa – student’s cumulative grade point average
                    placement – target variable (1: Placed, 0: Not Placed)

Note: No preprocessing or feature renaming was done. The dataset was used as-is.

✅ Objectives
                    Apply and compare multiple ML classification algorithms
                    Visualize decision boundaries for better understanding of model performance
                    Understand how different models classify the same data

🧠 Machine Learning Models Used
                    Logistic Regression – Linear model used for binary classification
                    Support Vector Machine (SVM) – Finds the best separating hyperplane between classes
                    Naive Bayes – Probabilistic model based on Bayes’ Theorem

📉 Visualization: The plot_decision_regions() function from mlxtend was used to visualize how each model classifies the data based on iq and cgpa.

🧪 Evaluation Metrics
                    Visual inspection using decision region plots
                    No extensive metric evaluation was performed (e.g., accuracy, precision), but this can be added if needed


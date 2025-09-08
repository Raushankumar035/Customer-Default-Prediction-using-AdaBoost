# Customer-Default-Prediction-using-AdaBoost

Customer Default Prediction is used by many banks and loan lenders to determine whether a person will be able to return the money they lend them or not. For this we be using AdaBoost which is an ensemble learning technique that combines multiple weak classifiers to create a strong classifier. The algorithm works by iteratively training sequence of classifiers each focusing on correcting the errors made by the previous one by assigning weights to the misclassified instances.

Implementing Customer Default Prediction using AdaBoost
We will be implementing it step by step and below are the steps to be considered while making it.

Core Libraries
Pandas: For loading and exploring the dataset.
NumPy: For working with numerical arrays and performing mathematical operations.
Visualization
Seaborn and Matplotlib: For visualizing data, distributions, and model results.
Preprocessing & Data Handling
SimpleImputer: Fills in missing values with a chosen strategy (like mean, median, etc.).
train_test_split: Splits the dataset into training and validation sets.
LabelEncoder: Converts categorical variables into numeric format.

Modeling
AdaBoostClassifier: An ensemble learning method that combines multiple weak learners to form a strong classifier.
Evaluation
accuracy_score and confusion_matrix: Evaluate the model’s accuracy and classification performance.

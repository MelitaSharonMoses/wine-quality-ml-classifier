# wine-quality-ml-classifier
This project showcases an end-to-end machine learning workflow for classifying wine quality. It features data preprocessing, model training with a K-Nearest Neighbors (KNN) classifier, hyperparameter tuning to optimize performance, and comprehensive evaluation using metrics like accuracy and a classification report.
 
The repository documents a standard data science workflow, including data preprocessing, model training, and performance evaluation.
# Methodology
* Data Preprocessing: The dataset is prepared by handling missing values (none found), separating features from the target variable, and using `train_test_split` to create training and testing sets. Features are scaled using `StandardScaler`, a crucial step for distance-based algorithms like KNN.
* Model Training: A `KNeighborsClassifier` is initialized and trained on the scaled training data.
* Hyperparameter Tuning: The optimal number of neighbors (`k`) is determined by plotting the model's accuracy against a range of `k` values, identifying the value that yields the highest performance.
* Model Evaluation: The model's performance on the test set is analyzed using key metrics, including:
* Accuracy Score: A single metric for overall performance.
* Confusion Matrix: Provides a detailed breakdown of correct and incorrect predictions for each class.
* Classification Report: Presents precision, recall, and F1-score, highlighting performance on imbalanced classes.

# OIBSIP_Data-Science_task1
# Objective of the Task
The goal of this task is to build a machine learning model that can accurately classify Iris flowers into one of three species—Setosa, Versicolor, or Virginica—based on their physical measurements (sepal length & width, petal length & width). The project uses the Iris dataset, a well-known classification problem in data science.
# Steps Performed
1. Data Loading & Preprocessing
   Loaded the Iris dataset from a CSV file.
   Dropped the Id column as it's not useful for prediction.
   Encoded the target class (Species) using LabelEncoder.
2, Feature & Target Split
   Split the dataset into features (X) and labels (y).
   Divided the data into training (80%) and testing (20%) sets using train_test_split.
3. Model Building
   Trained a RandomForestClassifier model using the training data.
   Evaluated the model using accuracy score, classification report, and confusion matrix.
4. Model Saving
   Saved the trained model and the label encoder using joblib for future predictions.
5.  User Interaction for Live Prediction
   Implemented a user-friendly CLI-based interface to input flower measurements and predict species in real-time.
# Tools & Technologies Used
1. Language: Python 🐍
2. Libraries:
pandas for data handling
numpy for numerical operations
scikit-learn for ML model, preprocessing, evaluation
joblib for saving the model
2. Model Used: Random Forest Classifier
3. Dataset: Iris Dataset (CSV format)
4. IDE/Platform: Google Colab or any Python IDE
# Outcome / Results
# Model Accuracy: ~96% on the test set
# Classification Report shows high precision and recall across all classes.
# The model can predict the species of a flower based on user input with great accuracy.
# Final model saved as iris_classifier.pkl, ready for deployment or integration into applications.

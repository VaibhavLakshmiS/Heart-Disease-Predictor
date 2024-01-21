
# Setup Instructions for Running the Heart Disease Prediction Model

## Prerequisites
- A Python environment (such as Jupyter Notebook)

## Steps

### 1. Installing Required Libraries
Ensure the following Python libraries are installed:
- pandas
- numpy
- scikit-learn
- SimpleImputer, StandardScaler, OneHotEncoder, ColumnTransformer, Pipeline from sklearn
- KNeighborsClassifier from sklearn.neighbors
- PCA from sklearn.decomposition

You can install these libraries using pip, for example:
```bash
pip install pandas numpy scikit-learn
```

### 2. Loading the Dataset
- Obtain the heart disease dataset (`heart_train.csv` and `heart_test.csv`) and place them in a known directory.
- Update the file paths in the code (`train_data_path` and `test_data_path`) to where you have stored the dataset files.

### 3. Running the Code
- Copy the Python code from the notebook into your Python environment.
- Execute each cell in sequence to train the KNN model and make predictions.

### 4. Model Training and Evaluation
- The code trains a KNN model optimized with cross-validation for parameter tuning (k values and distance metrics).
- The model is evaluated using a validation set for accuracy.

### 5. Generating Predictions
- The trained model is used to make predictions on the test dataset.
- Predictions are saved to a CSV file, with the path specified in the code.

## Notes
- The model's training and prediction time may vary based on your system's performance.

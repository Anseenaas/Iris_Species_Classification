# Iris Species Classification

## Project Overview
This project classifies Iris flower species based on sepal and petal measurements using the K-Nearest Neighbors (KNN) classification algorithm.

## Dataset
The Iris dataset contains the following features:
- Sepal Length
- Sepal Width
- Petal Length
- Petal Width
- Species

The original dataset contained 150 records. After removing 3 duplicate records, 147 records were used for analysis.

## Project Workflow
1. Data Loading
2. Data Exploration
3. Data Cleaning
4. Data Preprocessing
5. Exploratory Data Analysis (EDA)
6. Train-Test Split
7. Feature Scaling
8. KNN Model Training
9. Prediction
10. Model Evaluation

## Exploratory Data Analysis
- The three species classes were approximately balanced.
- Petal length and petal width showed a strong positive correlation of approximately 0.962.
- Some overlap was observed between Species 1 and Species 2 based on petal measurements.

## Machine Learning Model
The K-Nearest Neighbors (KNN) classification algorithm was used with:

- K = 3
- Train-Test Split = 80% training and 20% testing
- Feature Scaling = StandardScaler

## Model Performance
The KNN model achieved:

**Accuracy: 93.33%**

Out of 30 test samples, 28 were classified correctly.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Scikit-learn
- Google Colab

## Conclusion
The KNN model successfully classified Iris flower species with 93.33% accuracy. The analysis also showed that petal measurements are useful features for distinguishing between Iris species.

#  Iris Flower Classification using Machine Learning

##  Project Overview

This project builds a machine learning model to classify Iris flowers into three species—**Iris-setosa**, **Iris-versicolor**, and **Iris-virginica**—using sepal and petal measurements. The project demonstrates the complete machine learning workflow, including data preprocessing, exploratory data analysis (EDA), model training, evaluation, and prediction.

##  Objective

* Classify Iris flower species based on flower measurements.
* Compare the performance of multiple classification algorithms.
* Evaluate model performance using standard classification metrics.

##  Dataset

The Iris dataset contains **150 samples** with the following features:

* Sepal Length (cm)
* Sepal Width (cm)
* Petal Length (cm)
* Petal Width (cm)

**Target Variable:**

* Iris-setosa
* Iris-versicolor
* Iris-virginica

##  Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

##  Exploratory Data Analysis

* Checked dataset structure and summary statistics.
* Verified missing values.
* Visualized feature relationships using pair plots.
* Created correlation heatmaps and feature distribution plots.

##  Machine Learning Models

The following classification algorithms were trained and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Random Forest Classifier

##  Model Evaluation

The models were evaluated using:

* Accuracy Score
* Classification Report
* Confusion Matrix

The Random Forest model achieved **100% accuracy** on the test dataset.

##  Feature Importance

Random Forest feature importance was used to identify which flower measurements contributed most to the classification.

##  Sample Prediction

The trained model can predict the species of a new Iris flower based on its measurements.

##  Project Structure

```text
Iris-Flower-Classification/
│── Iris Flower Classification.ipynb
│── README.md
│── requirements.txt
└── Iris.csv
```

##  How to Run

1. Clone this repository.
2. Install the required libraries:

   ```bash
   pip install -r requirements.txt
   ```
3. Open `Iris Flower Classification.ipynb` in Jupyter Notebook.
4. Run all cells to train the models and view the results.

##  Results

* Successfully classified Iris flower species using machine learning.
* Compared multiple classification models.
* Achieved excellent prediction accuracy.
* Visualized data patterns and model performance.

##  Future Improvements

* Perform hyperparameter tuning.
* Use cross-validation for more robust evaluation.
* Deploy the model as a web application using Flask or Streamlit.


## Screenshots

### correlation heatmap

![Correlation Heatmap](https://github.com/teluguvijayaabhimanya-debug/Iris-Flower-Classification/blob/main/Screenshot%202026-07-06%20084324.png?raw=true)

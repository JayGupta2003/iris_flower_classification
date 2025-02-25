# Iris Flower Classification

## Overview

This repository contains a machine learning project focused on classifying Iris flower species using different classification algorithms. The models were trained and evaluated using the famous **Iris dataset**, which includes features such as sepal length, sepal width, petal length, and petal width to predict the flower species.

## Models Used

The following machine learning models were implemented and trained in a **Jupyter Notebook**:

- **Support Vector Machine (SVM)**
- **Logistic Regression**
- **Random Forest Classifier**
- **K-Nearest Neighbors (KNN)**

Each model was trained using **scikit-learn** and evaluated using various performance metrics.

## Understanding the Models

I have studied the working mechanisms of these models:

- **SVM** finds an optimal hyperplane to separate classes.
- **Logistic Regression** estimates probabilities using a logistic function.
- **Random Forest** combines multiple decision trees for better accuracy and robustness.
- **KNN** classifies data based on the majority of its nearest neighbors.

## Model Comparison

To assess model performance, I compared them using the following metrics:

- **Accuracy**
- **Precision**
- **Recall**
- **F1-Score**

The results were visualized using a **matplotlib line plot** to provide a performance comparison.

## How to Use

1. Clone the repository:
   ```sh
   git clone https://github.com/JayGupta2003/iris_flower_classification.git
   ```
2. Navigate to the directory:
   ```sh
   cd Iris_Flower_Classification
   ```
3. Run the Jupyter Notebook to train models:
   ```sh
   jupyter notebook iris.ipynb
   ```
4. Evaluate and compare models using the scripts provided.

## Dependencies

Install required libraries using:

```sh
pip install -r requirements.txt
```

## Results

The performance comparison is displayed using line plots to visualize differences in accuracy, precision, recall, and F1-score for each model.

## Future Improvements

- Implementing deep learning models for further comparison.
- Deploying the best model using a web framework.

## Contributing

Feel free to submit issues or pull requests to improve the project.

## License

This project is licensed under the MIT License.

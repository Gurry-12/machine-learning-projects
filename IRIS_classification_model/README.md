
# Iris Dataset Classification using Logistic Regression

This project demonstrates the application of logistic regression for classification using the famous Iris dataset. The Iris dataset is a well-known dataset in the field of machine learning and is often used for classification tasks. The goal of this project is to build a logistic regression model to classify iris flowers into one of three species based on their petal and sepal measurements.


# Dataset Description

The Iris dataset consists of 150 samples of iris flowers, each with four features: sepal length, sepal width, petal length, and petal width. The target variable is the class of the iris flower, which can take three possible values: "Iris-setosa," "Iris-versicolor," and "Iris-virginica."

# Prerequisites
Before running the code, ensure you have the following Python libraries installed:

    
    numpy
    seaborn
    matplotlib
    scikit-learn

You can install these libraries using the following command:
  
  `pip install pandas numpy seaborn matplotlib scikit-learn `


Getting Started

    Clone the repository or download the project files to your local machine.
    Make sure you have Python installed on your system.
    Install the required libraries as mentioned in the Prerequisites section.

Running the Code

    Open a terminal or command prompt in the project directory.
    Run the Python script iris_classification.py to execute the logistic regression model on the entire dataset.

python iris_classification.py

# Results

The script will train the logistic regression model on the entire Iris dataset and display the following results:

    Accuracy of the model on the entire dataset.
    Confusion matrix showing the count of correct and incorrect classifications for each class.

# Experimenting with Regularization

To experiment with different regularization strengths, you can modify the C parameter in the LogisticRegression class instantiation. Smaller values of C increase the regularization effect, while larger values reduce it. You can try different values of C to observe its impact on the model's performance.
Notes

    The Iris dataset is relatively small, and regularization may not have a significant impact on the model's performance.
    To obtain a more reliable estimate of the model's performance, consider using train-test splitting or cross-validation.

# References

    The Iris dataset is available at: UCI Machine Learning Repository
    For more information on logistic regression, refer to the scikit-learn documentation

Author

Gurpreet Singh
singhsarpreet234@gmail.com

# Assignment4
# Dataset
The dataset used in this example is the Iris dataset. It contains measurements of iris flowers and their corresponding species. The dataset is available in the file iris.csv.

# Code Explanation
    The code reads the dataset from a CSV file.
    It converts the species column into a numeric label using StringIndexer.
    Features are assembled using VectorAssembler.
    Data is split into train and test sets.
    Logistic Regression and Random Forest models are trained.
    Predictions are made on the test data.
    Model accuracy is evaluated using MulticlassClassificationEvaluator.

# Results
The accuracy of the trained models will be printed in the console.

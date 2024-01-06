# Email Spam Classification using Logistic Regression

This Jupyter Notebook provides a step-by-step guide to creating a machine learning model for classifying emails as spam or ham (non-spam) using logistic regression. The dataset used for this project is assumed to be stored in a CSV file named 'mail_data.csv'.

## Prerequisites

Before running the code in this notebook, you need to make sure you have the following libraries installed:

- numpy
- pandas
- scikit-learn (sklearn)

You can install these libraries using the following command:

```bash
pip install numpy pandas scikit-learn
```

## Notebook Structure

This notebook is divided into several code cells, each performing a specific task in the email spam classification process. Here's a brief overview of each code cell's functionality:

1. Importing Required Libraries: Importing necessary libraries for data processing, feature extraction, model creation, and evaluation.

2. Loading the Dataset: Loading the email dataset from the 'mail_data.csv' CSV file using pandas.

3. Preprocessing the Data: Filling missing values in the dataset and displaying the first few rows of the data.

4. Data Information: Displaying information about the dataset, including the number of rows and columns and data types.

5. Data Shape: Displaying the shape (dimensions) of the dataset.

6. Converting Labels to Numeric: Converting the 'Category' labels ('spam' and 'ham') to numeric values (0 for spam, 1 for ham).

7. Splitting Data into Features and Labels: Separating the email messages (features) and labels (spam/ham) into separate variables.

8. Splitting Data into Training and Test Sets: Splitting the data into training and test sets using the `train_test_split` function from scikit-learn.

9. Feature Extraction: Using TF-IDF vectorization to convert the email text data into numerical features.

10. Creating and Training the Logistic Regression Model: Creating a logistic regression model and training it on the training data.

11. Evaluating Model on Training Data: Making predictions on the training data and calculating the accuracy of the model on the training set.

12. Evaluating Model on Test Data: Making predictions on the test data and calculating the accuracy of the model on the test set.

13. Making Predictions on New Data: Providing an example of how to make predictions on new email data using the trained model.

## Usage

1. Install the required libraries if not already installed using the provided pip command.

2. Ensure that you have the 'mail_data.csv' file containing the email dataset in the same directory as this notebook.

3. Run each code cell sequentially to perform data preprocessing, model training, and evaluation.

4. You can modify the example email text in the cell titled "Making Predictions on New Data" to test the model's classification on new data.

## Conclusion

This notebook demonstrates the process of creating a simple email spam classification model using logistic regression. Keep in mind that this is a basic example, and there are various ways to improve the model's performance, such as using more advanced text preprocessing techniques, exploring different algorithms, and tuning hyperparameters.

Remember that the effectiveness of the model depends on the quality of the data and the chosen features. It's also important to stay up to date with the latest techniques in natural language processing and machine learning to enhance the performance of such models.

Feel free to expand on this notebook by exploring other classification algorithms, experimenting with different feature extraction methods, and handling imbalanced datasets for more accurate results.

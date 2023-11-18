1. Importing Libraries:

Libraries such as pandas, scikit-learn, seaborn, matplotlib, imbalanced-learn, XGBoost, and Plotly are imported to facilitate data manipulation, machine learning, visualization, and handling imbalanced datasets.

2. Loading the Dataset:

The script reads a CSV file ("WA_Fn-UseC_-HR-Employee-Attrition.csv") into a pandas DataFrame and displays the first few rows and information about the dataset.

3. Handling Missing Values:

Checks for missing values in the dataset using isnull() and sum() functions.

4. One-Hot Encoding:

Converts categorical variables into numerical format using one-hot encoding. This is crucial for machine learning models that require numerical input.

5. Defining Features and Target Variable:

Defines the feature matrix (X) and the target variable (y). Attrition_Yes is the target variable indicating whether an employee left.

6. Splitting the Dataset:

Splits the dataset into training and testing sets using the train_test_split function from scikit-learn.

7. Building a Random Forest Classifier:

Creates a Random Forest Classifier model with 100 trees and trains it on the training set.

8. Model Evaluation:

Evaluates the performance of the model on the testing set by calculating accuracy, displaying a confusion matrix, and showing a classification report.

9. Feature Importance Visualization:

Calculates feature importance using the trained Random Forest model and visualizes it using a horizontal bar chart with Plotly.

10. Subplots for Employee Attrition Statistics:

Creates a subplot with three charts: employee attrition rate, feature importance, and department attrition rate. Uses Plotly for interactive visualization.

11. Attrition Rates by Department and Gender:

Groups data by relevant columns and creates a bar plot to visualize attrition rates by department and gender using Plotly. This provides insights into how attrition varies across different departments and genders.

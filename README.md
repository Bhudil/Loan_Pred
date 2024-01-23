# Loan Approval Prediction

This project implements a deep learning-based classifier which uses simple artificial neural network to make a prediction based on various features provided.

## Technologies Used
Python
TensorFlow
Pandas
NumPy
Matplotlib
Seaborn
Scikit-Learn
Project Structure

**Datasets:**

lending_club_info.csv: Contains information about loan features.
lending_club_loan_two.csv: Actual dataset for analysis.

**Code Files:**

exploratory_data_analysis.py: Python script for exploratory data analysis.
data_cleaning.py: Python script for data cleaning.
encoding_dummy_variables.py: Python script for encoding/dummy variables.
data_preprocessing.py: Python script for data preprocessing.
model_creation.py: Python script for creating and training the machine learning model.
test_in_real_world.py: Python script for testing the model in a real-world scenario.

## Usage
This project involves the analysis of lending club loan data, including exploratory data analysis, data cleaning, data preprocessing, and the creation of a machine learning model to predict loan repayment.

## How to Run
Install the required Python packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn tensorflow
```

Execute the Python scripts in the following order:

```bash
python exploratory_data_analysis.py
python data_cleaning.py
python encoding_dummy_variables.py
python data_preprocessing.py
python model_creation.py
python test_in_real_world.py
```

Check the generated results, visualizations, and model predictions.

## Additional Information
**Dataset Information:**

The lending_club_info.csv file contains information about loan features.
The lending_club_loan_two.csv file is the actual dataset for analysis.

**Exploratory Data Analysis:**

Visualizations include count plots, distribution plots, and correlation matrices.
Heatmaps and boxplots are utilized for understanding the relationships within the dataset.

**Data Cleaning:**

Handling missing values in the dataset.

**Encoding/Dummy Variables:**

Converting categorical variables into a format suitable for machine learning.

**Data Preprocessing:**

Scaling and splitting the dataset for training and testing.

**Model Creation:**

An artificial neural network model is created using TensorFlow.

**Evaluation:**

Classification report and confusion matrix are provided for model evaluation.

**Testing in Real-World:**

A script (test_in_real_world.py) demonstrates how to use the trained model for predictions in a real-world scenario.

# Airfoil Noise Prediction ML Pipeline

## Overview

Welcome to the Airfoil Noise Prediction ML Pipeline project! As a data engineer at an aeronautics consulting company, your role is crucial in building efficient Machine Learning pipelines to support the work of data scientists focusing on airfoil design. This project involves working with a modified version of the NASA Airfoil Self Noise dataset, cleaning and transforming the data, building a machine learning model to predict sound levels based on various features, evaluating its performance, and persisting the model for future use.

## Scenario

As a data engineer, your primary responsibilities include handling ETL (Extract, Transform, Load) processes and constructing ML pipelines. In this project, you will utilize the NASA Airfoil Self Noise dataset, perform necessary data cleaning, and build a machine learning model to predict sound levels based on various features. The project is divided into four main parts:

### Part 1: ETL Activity

1. **Load a CSV Dataset:**
   - Load the modified NASA Airfoil Self Noise dataset from a CSV file.

2. **Remove Duplicates and Null Values:**
   - Eliminate duplicate rows from the dataset.
   - Remove rows containing null values.

3. **Make Transformations:**
   - Apply any necessary transformations to prepare the data for model training.

4. **Store Cleaned Data:**
   - Save the cleaned data in the Parquet format for future use.

### Part 2: Create a Machine Learning Pipeline

1. **Build a Machine Learning Pipeline:**
   - Develop a pipeline for predicting sound levels based on the dataset's features.

### Part 3: Evaluate the Model

1. **Performance Metrics:**
   - Evaluate the model using relevant metrics to assess its predictive capabilities.

### Part 4: Persist the Model

1. **Save Model for Production Use:**
   - Persist the trained model for future use in production.

2. **Load and Verify the Model:**
   - Ensure the stored model can be loaded successfully and verify its correctness.

## Datasets

You will be working with the modified version of the NASA Airfoil Self Noise dataset. The original dataset can be found [here](https://archive.ics.uci.edu/dataset/291/airfoil+self+noise). Please note that this dataset is licensed under a Creative Commons Attribution 4.0 International (CC BY 4.0) license.

## Getting Started

To run this project, follow the instructions below:

1. Clone the repository to your local machine.
2. Install the required dependencies.
3. Execute the ETL process by running the script for Part 1.
4. Create and train the ML pipeline using the script for Part 2.
5. Evaluate the model using the metrics defined in Part 3.
6. Save the trained model for future production use as instructed in Part 4.

Feel free to explore, modify, and adapt the code to suit your specific needs. Happy coding!

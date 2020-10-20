# This is my "hello_flora" project
Hello, world! This is my first Machine Learning project and here I will be documenting the process below.

# Project: OVERVIEW
- The iris dataset contains the following data
  - 50 samples of 3 different species of iris (150 samples total)
- Measurements: sepal length, sepal width, petal length, petal width
- The format for the data: (sepal length, sepal width, petal length, petal width)

# Format that I used:
Python Project Template
# 1. Prepare Problem
- a) Load libraries 
- b) Load dataset
  - python modules, classes and functions 
  - loading your dataset from CSV file

# 2. Summarize Data
- a) Descriptive statistics # b) Data visualizations
  - Descriptive statistics such as summaries
  - Data visualization such as plots with Matplotlib and pandas
  - Take your time here and use the results to prompt a lot of questions, assumptions and hypotheses
    that you can investigate later with specialized models

# 3. Prepare Data
- a) Data Cleaning
- b) Feature Selection # c) Data Transforms
  - Cleaning data by removing duplicates, marking missing values and even imputing missing values
  - Feature selection where redundant features may be removed and new features developed
  - Data transforms where attributes are scaled or redistributed in order to best expose the
    structure of the problem later to learning algorithms 
  - START SIMPLE. revisit this step often and cycle with the next step until you converge on a subset
    of algorithms and a presentation of the data that results in accurate or accurate-enough models to proceed. 


# 4. Evaluate Algorithms
- a) Split-out validation dataset
- b) Test options and evaluation metric # c) Spot Check Algorithms
- d) Compare Algorithms
  - Separating out a validation dataset to use for later confirmation of the skill of your developed
model.
  - Defining test options using scikit-learn such as cross validation and the evaluation metric to 
use.
  - Spot-checking a suite of linear and nonlinear machine learning algorithms.
  - Comparing the estimated accuracy of algorithms.
  - On a given problem you will likely spend most of your time on this and the previous step until 
    you converge on a set of 3-to-5 well performing machine learning algorithms.

# 5. Improve Accuracy 
- a) Algorithm Tuning 
- b) Ensembles
  - Search for a combination of parameters for each algorithm using scikit-learn that yields the best results.
  - Combine the prediction of multiple models into an ensemble prediction using ensemble techniques

# 6. Finalize Model
- a) Predictions on validation dataset
- b) Create standalone model on entire training dataset # c) Save model for later use
  - Using an optimal model tuned by scikit-learn to make predictions on unseen data.
  - Creating a standalone model using the parameters tuned by scikit-learn.
  - Saving an optimal model to file for later use.
  # C R E D I T:
- THANK YOU to Jason Brownlee and Machine Learning Mastery for the Template & coding walkthrough! 
https://machinelearningmastery.com/ please visit & support here

# 4604-wildfires-are-hot
INFO 4604 Final Project

1. Describe the dataset and problem you are trying to solve. How big is the dataset?

The dataset we are using is from kaggle. It is about the 1.88 million U.S wildfires, based off of 24 years of geo-referenced wildfire records. There are many questions we may able to answer with this dataset but we are planning to focus on predicting the cause of a wildfire.

https://www.kaggle.com/rtatman/188-million-us-wildfires


2. Describe what steps are needed for data collection and preprocessing (if any).

There won’t be any steps needed for data collection as this data is off of kaggle.com. The dataset has a lot of rows (~1.8 million), so we will probably need to filter the data to remove some of the noise. We will be focusing on the causes of larger fires, so we will use the fire area or duration to filter the data.


3. Describe what features you will use. Describe what features are already in the dataset, and what features you intend to create (if any).

The features that we will use that are already included in the dataset will be fire area, duration, location, date/time of ignition or discovery, and possibly the first responding agency. We don't plan on needing to create any new features.


4. Describe what experiments you will do. If you are going to do the “expected experiments” listed above, you can simply state that. If you plan to do fewer experiments because you will do more work with data collection and/or feature engineering, then propose what you will do instead.

Three different classification algorithms:

- Perceptron

- SVM with linear and nonlinear kernels 

- Decision trees + random forest

- Logistic regression (may be a good starting point)

Feature selection and dimensionality reduction

Error analysis

- Confusion matrix

- Examine the misclassified instances

- Look at the weights to understand what the classifier is doing and what features are having the largest impact on classification

# deep-learning-challenge

**Analysis Overview**

The purpose of this analysis is to build and evaluate a deep learning model for predicting the success of loan applications, as indicated by the target variable 'IS_SUCCESSFUL'. The goal is to determine how well the model can predict success or failure based on input features and identify areas for improving performance.

**Results**

**Data Preprocessing**

Target Variable(s):
The target variable for the model is 'IS_SUCCESSFUL', which indicates whether the loan application was successful or not.
Feature Variable(s):
The feature variables are all columns in the dataset except for 'IS_SUCCESSFUL'. These include various applicant attributes, such as financial information, personal details, and other related factors.
Variables to Remove:
The 'EIN' and 'NAME' columns were removed from the dataset. These were neither target variables nor useful features for the model, as they likely contained non-predictive, irrelevant information.

**Model Development**

Neurons, Layers, and Activation Functions:
In the initial model design, I used two hidden layers:
Layer 1: 8 hidden nodes
Layer 2: 5 hidden nodes
The activation functions for the hidden layers were selected randomly in the first attempt. These choices were made with the intention to iterate and adjust in subsequent model-building attempts.

**Model Performance:**

The model did not meet the target accuracy of 75% during the first attempt. The final accuracy achieved was approximately 73%.
Steps Taken to Improve Model Performance:
Several strategies were employed to enhance model accuracy, including:
Adding more hidden layers.
Removing additional less relevant features.
Increasing the number of hidden nodes in the layers.
Experimenting with different activation functions (e.g., ReLU, Sigmoid, etc.).
Evaluating different configurations iteratively to see if accuracy could be improved.

**Summary**

The deep learning model achieved an accuracy of about 73%, which is slightly below the desired target of 75%. While the model performed reasonably well, there is potential for improvement. Further steps that could improve performance include:

Enhanced Data Preprocessing: 

Performing additional data cleaning and feature engineering to better capture relevant patterns and remove noise.

Model Tuning: 

Experimenting with more complex architectures (e.g., additional layers, varying the number of nodes per layer) and different activation functions (e.g., Leaky ReLU, ELU) to improve learning capacity.

Alternative Models: 

Trying other machine learning models, such as Random Forests, Gradient Boosting, or XGBoost, which may capture non-linear relationships and interactions in the data more effectively than the neural network.

In conclusion, while the deep learning model provided valuable insights into loan success prediction, further iterations and experimentation with alternative models could potentially yield higher predictive accuracy.

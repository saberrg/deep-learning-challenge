# Using Deep Learning to Find Sucess within Organizations

## Overview

Alphabet Soup, a nonprofit foundation, is in need of developing a tool to identify applicants most likely to succeed in their endeavors when funded. Using machine learning and neural networks with the sklearn and Tensorflow libraries. This model will predict whether applicants have a high likelihood of success if they receive funding from Alphabet Soup using the given dataset (charity_data.csv) to train the model.

The purpose of this analysis is to use machine learning and neural networks to help make decisions on the best business venture. 


## Results: 73% Success Accuracy

Data Preprocessing

What variable(s) are the target(s) for your model?

* is_successful

What variable(s) are the features for your model?

* Classifications, Application Type, Ask Amount, Income Amount

What variable(s) should be removed from the input data because they are neither targets nor features?

* The EIN and Name isn't needed here 

## Compiling, Training, and Evaluating the Model

How many neurons, layers, and activation functions did you select for your neural network model, and why? A variation of 2-3 layers with 2-16 neurons with activation relu.

Were you able to achieve the target model performance? The model didn't achieve the optimum accuracy of 75+.

What steps did you take in your attempts to increase model performance? Increasing layers, number of units and epochs. 

# Summary: Striving for Better Accuracy

A different model, such as a Random Forest or Gradient Boosting classifier, could also be considered as an alternative to this projecy deep learning model. In conclusion, a repeated shift in layers and units can achieve a higher optimization, but perhap other models could be explored.

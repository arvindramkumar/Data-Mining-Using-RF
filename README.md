# Random Forest Model Building 

## About the Data Set 

2500 Instances to Train (65 Variables)

1200 Instances to Test 

Binary Response (-1 and +1) 

Heavy Class Imbalance in Training Set 

No Prior Knowledge about the dataset and variables labeled as x1, x2 and so on. 

## Data Preprocessing 

In order to avoid loss of information, to handle the Class imbalance, Up-Sampling was preferred rather than Down-Sampling.

No Missing data

To handle to Categorical Variables, Label Encoder was used. 

## Model Building 

30% of the Training Data was split to validate the model. Preliminary runs were performed to see that Random Forest Model Performs best relative to other models including, SVM, NN, Perceptron and Decision Trees. GridSearchCV was employed to select the optimal values for the parameters in RF. 

## Data Post Processing 

Apart from Train and Test Accuracy, Balanced Error Rate was used as a measure of accuracy.

## Conclusion 

The Model Developed from 30% Split of Training set had a Train Accuracy of 99% and Test Accuracy of 85%. The balanced Error Rate was abput 20%. Then the model was extended to full model, and we see that the train accuracy was 95% 

## Recommendations

There is an Hypothesis that Logisitic Regression might perform better in dealing with Binary response, so this method could also be employed to obtain a better result 

## Tools Used 

Python, R, Excel

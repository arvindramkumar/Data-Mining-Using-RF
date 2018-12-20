•	A training set with 64 Variables and 2500 instances with binary response with heavy class imbalance was studied. 

•	No prior knowledge about the dataset and we have the variables labeled as x1, x2 and so on. 

•	In order to avoid loss of information, to handle the Class imbalance, Up-Sampling was preferred rather than Down-Sampling.

•	It is a well-known fact that RF works better in Data Mining and prior test were conducted to see that RF was able to provide a better accuracy. So RF was employed for the study. 

•	GridSearchCV was deployed to obtain the Optimal Parameters of the Random Forest.

•	A model was developed with Test Accuracy of 85% and the balanced error rate was 20.97%

•	On another note, since the response is a categorical output, there are high chances that a Logistics Regression Might work better. But its still an hypothesis. 

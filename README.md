# CC-Fraud

## Neural Networks - Fraud Detection
### Context
Nielsen reports that U.S. card fraud (credit, debt, etc) was reportedly 9 billion dollars in 2016 and expected to increase to 12 billion dollars by 2020. For perspective, in 2017 both PayPal's and Mastercard's revenue was only $10.8 billion each. Therefore, it is important that credit card companies should be able to recognize fraudulent credit card transactions so that customers are not charged for items that they did not purchase.

### Objective:
Build a Model (i.e. Multilayer perceptrons) for Fraud Detection using Keras.
This notebook covers,
1.	Creating a Model
2.	Adding Layers
3.	Activations
4.	Optimizers and Loss functions
5.	Earlystopping
6.	Weight Initalization
7.	Dropout
8.	Model Evaluation
   
### Dataset Description
The dataset contains transactions made by credit cards in September 2013 by european cardholders. This dataset presents transactions that occurred in two days, where we have 492 frauds out of 284,807 transactions. The dataset is highly unbalanced, the positive class (frauds) account for 0.172% of all transactions.
It contains only numerical input variables which are the result of a PCA transformation. Unfortunately, due to confidentiality issues, the original features and more background information about the data is not provided. Features V1, V2, ... V28 are the principal components obtained with PCA, the only features which have not been transformed with PCA are 'Time' and 'Amount'.
Time contains the seconds elapsed between each transaction and the first transaction in the dataset.
Amount is the transaction Amount, this feature can be used for example-dependant cost-senstive learning.
Class is the response variable and it takes value 1 in case of fraud and 0 otherwise.

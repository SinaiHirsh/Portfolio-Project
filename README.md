# Credit risk assesment 


## NON-TECHNICAL EXPLANATION OF YOUR PROJECT
100 words to explain what your project is about to a general audience. 
Our goal is to predict the probability of default based on a set of variables.

## DATA
A summary of the data you’re using, remembering to include where you got it and any relevant citations.
We will use data from https://www.kaggle.com/datasets/urvishvekariya/credit-risk-assessment?datasetId=2995523
The data consists of 32,581 records of loans.
According to the inforamation on Kaggle, the data was last Updated 3 months ago.
 Urvish Vekariya. (2023). <i>Credit Risk Assessment</i> [Data set]. Kaggle. https://doi.org/10.34740/KAGGLE/DSV/5168573

## MODEL 
A summary of the model you’re using and why you chose it. 
I used logistic regression because it is very common to use it for credit scorring in the banking sector. The shape of the sigmond function mathematiclly causes the values to be between 0 and 1 which is what we want when it comes to binary variable that we want to make probabilities for it. 

## HYPERPARAMETER OPTIMSATION
Description of which hyperparameters you have and how you chose to optimise them. 
Logistic regression has several hyperparameters on Sklearn and I optimised the most significant ones. I take my basecode from here:
https://www.kaggle.com/code/funxexcel/p2-logistic-regression-hyperparameter-tuning/notebook
and here:
https://www.projectpro.io/recipes/optimize-hyper-parameters-of-logistic-regression-model-using-grid-search-in-python
The idea is using gread search for hyperparameter tuning, when the algorithm consider all the possible combinations between the hyperparameters that we want to tune. 

## RESULTS
A summary of your results and what you can learn from your model 

You can include images of p![cm](https://github.com/SinaiHirsh/Portfolio-Project/assets/135940841/75bbfcbc-b02b-4ef4-b44b-ecbfd95cec22)
lots using the code below:

![Screenshot](image.png)

## (OPTIONAL: CONTACT DETAILS)
If you are planning on making your github repo public you may wish to include some contact information such as a link to your twitter or an email address. 


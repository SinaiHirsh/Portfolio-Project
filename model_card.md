# Model Card

As a portfolio project summarises the course, I chose to concentrate on a problem of credit risk prediction. The data was taken from Kaggle, as well as some of the codebase.

Our goal is to predict the probability of default based on a set of input variables. We will use logistic regression, so each observation gets a value between 0 and 1 - which is the probability of default.

We will use Grid Search for hyperparameter tuning, to ensure that we get the best combination of hyperparameters that make the accuracy the highest.

## Model Description

**Input:** The input variables are: 


	Age,
	Annual Income,
	Home ownership,
	Employment length (in years),
	Loan intent,
	Loan grade,
	Loan amount,
	Interest rate,
	Percent income,
	Historical default,
	Credit history length.

**Output:** The output variable is: Loan status (0 is non default 1 is default).

**Model Architecture:** Using logistic regression, our aim is to predict probability of default based on the input variables. 

## Performance

The accuracy is quite high both on train and test sets. After hyperparameter tuning the train accuracy slightly increased, while the test accuracy decreases a little bit. 

Accuracy on the training data set with the original hyperparameters:  0.8461875739904415

Accuracy on the training data set after hyperparameters tuning:  0.8466698820537554

Accuracy on the test data set with the original hyperparameters:  0.8473501125434827

Accuracy on the test data set after hyperparameters tuning:  0.8471454880294659


Confusion matrix:

![cm](https://github.com/SinaiHirsh/Portfolio-Project/assets/135940841/5537f645-10a1-4d7c-91e2-a518260ec20f)


## Limitations

1. The data source is not known, which means that it is not recommended to take it too serioesly. 
2. Too much false positive. I think the right thing to do would be to change the probability threshold so more instances would be marked as default even if their probability of default is lower than 50%. In other words, the accuracy of the model is high due to correct identification of non-defaults, but we failed in identifying the defaults. 


![cm_pct](https://github.com/SinaiHirsh/Portfolio-Project/assets/135940841/1df8f945-9b2b-4e53-9425-259451e123bf)


## Trade-offs

Again, the data and the model are only for educational purposes and should not be used to any real-life problem. 

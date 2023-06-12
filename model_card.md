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

**Model Architecture:** Using logistic regression, our aim is to predict pobability of default based on the input variables. 

## Performance

Give a summary graph or metrics of how the model performs. Remember to include how you are measuring the performance and what data you analysed it on. 



![cm](https://github.com/SinaiHirsh/Portfolio-Project/assets/135940841/5537f645-10a1-4d7c-91e2-a518260ec20f)


## Limitations

Outline the limitations of your model.

## Trade-offs

Outline any trade-offs of your model, such as any circumstances where the model exhibits performance issues. 

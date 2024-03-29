# Datasheet - credit_risk_dataset.csv

_I used data from https://www.kaggle.com/datasets/urvishvekariya/credit-risk-assessment?datasetId=2995523
The data consists of 32,581 records of loans. 
The dataset contains columns simulating credit bureau data.
According to the information on Kaggle, the data was last updated 3 months ago._

## Motivation

- For what purpose was the dataset created?  
*We don't have this information. The data appears on Kaggle in a project that was created by Urvish Vekariya, but there are no details about the origin or the motivation etc.*
- Who created the dataset (e.g., which team, research group) and on behalf of which entity (e.g., company, institution, organization)? Who funded the creation of the dataset?  
 *We don't have this information, but it seems like it's a simulation and not a real dataset.*



 
## Composition

- What do the instances that comprise the dataset represent (e.g., documents, photos, people, countries)?  
_The dataset represents 32581 observations of information about loans. It seems that each observation represents a unique loan._
- How many instances of each type are there? 
  _There are 7108 instances of default and 25473 instances of non-default._
- Is there any missing data? 
_There are 2 columns with missing values: There are 895 missing values in person_emp_length and 3116 missing values in loan interest rate._
- Does the dataset contain data that might be considered confidential (e.g., data that is protected by legal privilege or by    doctor–patient confidentiality, data that includes the content of individuals’ non-public communications)?  
_No._

## Collection process

- How was the data acquired? 
_We don't have this information, but it seems like it's a simulation and not a real dataset._
- If the data is a sample of a larger subset, what was the sampling strategy? 
_The data is not a sample._
- Over what time frame was the data collected?
 _We don't have this information, but it seems like it's a simulation and not a real dataset._

## Preprocessing/cleaning/labelling

- Was any preprocessing/cleaning/labeling of the data done (e.g., discretization or bucketing, tokenization, part-of-speech tagging, SIFT feature extraction, removal of instances, processing of missing values)? If so, please provide a description. If not, you may skip the remaining questions in this section.

*Missing values in person_emp_length were set to a value of zero. Missing values in loan_int_rate was set to the average value. Values of age that were higher than 120 were set to 120. In addition, all input variables were converted to scale values by standardisation.*

- Was the “raw” data saved in addition to the preprocessed/cleaned/labeled data (e.g., to support unanticipated future uses)?  

*All the original values are saved in the original file.*
 
## Uses

- What other tasks could the dataset be used for? 

__As we don't know the origin of the data, it is recommended to use the dataset only for educational purposes and not for real life tasks.__

- Is there anything about the composition of the dataset or the way it was collected and preprocessed/cleaned/labeled that might impact future uses? For example, is there anything that a dataset consumer might need to know to avoid uses that could result in unfair treatment of individuals or groups (e.g., stereotyping, quality of service issues) or other risks or harms (e.g., legal risks, financial harms)? If so, please provide a description. Is there anything a dataset consumer could do to mitigate these risks or harms? *There are no risks given that no one uses the data for real life probelems.*
- Are there tasks for which the dataset should not be used? If so, please provide a description.
__As we don't know the origin of the data, it is recommended to use the dataset only for educational purposes and not for real life tasks.__

## Distribution

- How has the dataset already been distributed? *Via Kaggle.*
- Is it subject to any copyright or other intellectual property (IP) license, and/or under applicable terms of use (ToU)? *CC0: Public Domain.* 

## Maintenance

- Who maintains the dataset? *We don't have this information. The data appears on Kaggle in a project that was created by Urvish Vekariya, but there are no details about the origin or the motivation etc.*


# Comparing Classifiers
 Comparing the performance of k-nearest neighbors, logistic regression, decision trees, and support vector machines

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required. The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

There are two datasets: 
1) bank-full.csv with all marketing data and 17 inputs, ordered by date 
2) bank.csv with a 10%, randomly selected dataset from the bank-full.csv

I used the sample of this data for the computational demanding vector machine classification.

## Variable details

 
| Variable Name |   Data type  |   Description                                            |
|:--------------|:------------:|---------------------------------------------------------:|
|      Age      |    Integer   |                                                          |
|      Job      | Categorical  |  Occupation, ex: admin, blue-collar, retired, unemployed |    
|    Marital    | Categorical  |  Married, single, divorced                               |  
|   Education   | Categorical  |  Tertiary, secondary, primary, unknown                   |  
|    Default    |   Binary     |  Credit in default? yes or no                            |  
|    Balance    |   Integer    |  Average yearly balance                                  | 
|    Housing    |   Binary     |   Has housing loan? yes or no                            | 
|      Loan     |   Binary     |   Has personal loan? yes or no                           | 
|    Contact    | Categorical  |   Contact communication type (cellular, telephone)       | 
|       Day     |   Integer    |   Day of the week of last contact                        | 
|     pdays     |   Integer    |  Number of days since last contact (-1 means no contact) | 
|   Previous    |   Integer    |   Number of contacts performed before this campaign      | 
|   poutcome    | Categorical  |  Outcome of previous campaign: unknown, failure, success | 
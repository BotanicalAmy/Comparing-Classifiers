# Comparing Classifiers
 Comparing the performance of k-nearest neighbors, logistic regression, decision trees, and support vector machines

The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required. The classification goal is to predict if the client will subscribe (yes/no) a term deposit (variable y).

There are four datasets: 
1) bank-additional-full.csv with all examples (41188) and 20 inputs, ordered by date (from May 2008 to November 2010), very close to the data analyzed in [Moro et al., 2014]
2) bank-additional.csv with 10% of the examples (4119), randomly selected from bank-additional-full.csv, and 20 inputs.
3) bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs). 
4) bank.csv with 10% of the examples and 17 inputs, randomly selected from 3 (older version of this dataset with less inputs). 

For my analysis, I chose to use the bank-full.csv dataset.  I used the sample of this data, bank.csv, for the computational demanding support vector machine classification.

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
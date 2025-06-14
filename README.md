# term-deposit-subscription-project
Term Deposit Subscription Project from UT Austin AI/ML Certificate

Term Deposit Subscription


Summary:
Using the data collected from existing customers, build a model that will help the marketing team identify potential customers who are relatively more likely to subscribe term deposit and thus increase their hit ratio.

 

Data Discription:
The data is related with direct marketing campaigns of a Portuguese banking institution. The marketing campaigns were based on phone calls. Often, more than one contact to the same client was required, in order to access if the product (bank term deposit) would be ('yes') or not ('no') subscribed ([Moro et al., 2014] S. Moro, P. Cortez and P. Rita. A Data-Driven Approach to Predict the Success of Bank Telemarketing. Decision Support Systems, Elsevier, 62:22-31, June 2014. Retrieved from: https://archive.ics.uci.edu/ml/datasets/Bank+Marketing)

Dataset: bank-full.csv with all examples and 17 inputs, ordered by date (older version of this dataset with less inputs)
 

Domain:
Bank Marketing

 

Attribute Information:
Bank Client Data
age - clients age
job - type of job
marital - marital status
education - clients education level
default - client has credit in default
housing - client has housing loan
loan - client has personal loan
balance - balance in account
Related with the Last Contact of the Current Campaign
contact - contact communication type
day - last contact day of the month
month - last contact month of the year
duration - last contact duration in seconds
Other Attributes
campaign - number of contacts performed during this campaign and for the client
pdays - number of days that passed by after the client was last contacted from a previous campaign
previous - number of times the client has been contacted before for the last campaign to subscribe term deposit
poutcome - coutcome of the previous marketing campaign
Target - Tell us has the client subscribed a term deposit
Notes:
duration: last contact duration, in seconds (numeric). Important note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

pdays: -1 tells us the person has not been contacted or contact period is beyond 900 days

Objective
Identify potential customers who are more liklely to subscribe to Term Deposit Subscription
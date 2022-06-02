# Term-Deposit-Subscription-Prediction
Term Deposit Subscription Prediction using Ensemble Techniques 

Problem statement (Term Deposit Sale) Using the data collected from existing customers, build a model that will help the marketing team identify potential customers who are relatively more likely to subscribe to term deposits and thus increase their hit ratio.

Attribute information

Input variables: Bank client data:

age: Continuous feature
job: Type of job (management, technician, entrepreneur, blue-collar, etc.)
marital: marital status (married, single, divorced)
education: education level (primary, secondary, tertiary)
default: has credit in default?
housing: has a housing loan?
loan: has personal loan?
balance in account
Related to previous contact: 9. contact: contact communication type 10. month: last contact month of year 11. day: last contact day of the month 12. duration: last contact duration, in seconds* Important Note: this attribute highly affects the output target (e.g., if duration=0 then y='no'). Yet, the duration is not known before a call is performed. Also, after the end of the call y is obviously known. Thus, this input should only be included for benchmark purposes and should be discarded if the intention is to have a realistic predictive model.

Other attributes: 13. campaign: number of contacts performed during this campaign and for this client 14. pdays: number of days that passed by after the client was last contacted from a previous campaign (-1 tells us the person has not been contacted or contact period is beyond 900 days) 15. previous: number of times the client has been contacted before for the last campaign to subscribe term deposit 16. poutcome: outcome of the previous marketing campaign

Output variable (desired target): 17. Target: Tell us has the client subscribed a term deposit. (Yes, No)

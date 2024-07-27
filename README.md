# BANK-MARKETING-ANALYSIS-USING-PYSPARK


The dataset pertains to direct marketing campaigns of a Portuguese bank, where marketing was conducted via phone calls. Multiple contacts were often required to determine if a client would subscribe to a term deposit.

Instances: 45,211 (bank-full.csv) and 4,521 (bank.csv)
Attributes: 16 input variables + 1 output variable
Input Variables:

age: Numeric
job: Categorical (e.g., "admin", "student", "blue-collar")
marital: Categorical ("married", "divorced", "single")
education: Categorical ("unknown", "secondary", "primary", "tertiary")
default: Binary ("yes", "no")
balance: Numeric (average yearly balance in euros)
housing: Binary ("yes", "no")
loan: Binary ("yes", "no")
contact: Categorical ("unknown", "telephone", "cellular")
day: Numeric (last contact day of the month)
month: Categorical ("jan" to "dec")
duration: Numeric (last contact duration in seconds)
campaign: Numeric (number of contacts in this campaign)
pdays: Numeric (days since last contact; -1 indicates no previous contact)
previous: Numeric (number of previous contacts)
poutcome: Categorical ("unknown", "other", "failure", "success")
Output Variable:
17. y: Binary ("yes", "no") - Indicates whether the client subscribed to a term deposit

Analysis Performed: Campaign effectiveness, loan analysis, financial, and demographic analysis.

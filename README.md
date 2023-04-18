Problem statement 
X Education sells courses online. Leads and metadata are generated from various sources. Teams are assigned to capture potential leads and convert them into hot leads. We have to create a machine learning model for the company which predicts and assigns a lead score to each lead based on different variables available from historical data. This is a logistic regression problem because we are predicting the classification of the leads as converted or not with a probability of conversion.  
Solution 
We need to find the hot leads - leads that have a higher probability of getting converted. The teams will spend more time on those and not waste time and resources on leads with low score.  
The Dataset 
The original dataset was loaded using pandas. It had 9240 rows and 37 columns. However, when we look carefully at the dataset, it becomes immediately clear that a couple of columns are irrelevant to our study. A few columns have a singular value only. This means that we have to look deeper in the data. 

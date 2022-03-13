# Customer-Segmentation-and-Profiling
Customer segmentation is a pivotal task for business analytics. Customer segmentation is  the process of splitting customers into different groups with similar characteristics for  potential business value proposition. Many companies find that segmenting their customers  enable them to communicate, engage with their customers more effectively. 

Future Bank is conducting an analysis on the existing customer profiles and the marketing  campaign data to identify the target customers who are mostly likely to subscribe long-term  deposits. As a member of the data analytics team, I am tasked to analyse historical data  and develop predictive models for marketing purposes.

The project is seeking knowledge and insights relating to:
• The demographics-based segments and their profiles;
• The representative behavioural profiles for each segment;
• How the produced segments can be mapped to a broader concept of segments in Australian community.

I used SAS to perform clustering and profiling segments with the support of other tools like R and Excel. I relateed the segments and profiles in conjunction with Roy Morgan value segments. To further understand these value segments, I used:
• http://www.roymorgan.com/products/values-segments

Task 1: Customer segmentation based on demographics data
By using the SAS Enterprise Miner, conducted a clustering and segment profiling based on the 
demographics data (Age, Job, Marital_Status, Education) and answered the following questions.
• What are the key demographics segments for the whole dataset? Describe the main 
profiles and then map them into the Roy Morgan segments. 
• What are the most important variables based on each segment? (Target: Subscribed)
• Are there differences in segments for customers subscribed to long-term deposit and 
those who did not? Discuss the segment differences.

Task 2: Customer segmentation based on behavioural data
Considering the behavioural variables in the data (Default_Credit, Housing_Loan, 
Personal_Loan), I conducted a clustering and segment profiling and answered the following questions. 
• What are the key behavioural segments for the whole dataset? Describe the main 
profiles.
• What are the important variables based on each segment? (Target: Subscribed)
• Are there differences in segments for customers subscribed to long-term deposit and 
those who did not? Discuss the segment differences. 

Task 3: Cross cluster analysis – demographics to behavioural segments
For each individual (both subscribers and non-subscribers), recorded the corresponding 
demographics and behavioural clusters (based on Task 1 and Task 2 above). Performed a cross 
cluster analysis in R by using demographics clusters as rows and behavioural clusters as 
columns in a table. I answered the following questions.
• Are there any significant associations between the two types of segments? Discuss
the associations.
• Is there a relationship between the outcome (Subscribed) and the combined
demographics and behavioural segments identified? Explain the produced combined 
segments from demographics and behavioural clusters and their associations with 
the outcome (Subscribed).

Task 4: Customer segmentation based on combined demographic and behavioural data 
Instead of conducting clustering and profiling separately on demographics and behavioural 
data and then working on cross cluster analysis, I performed the task on the 
whole data set (Age, Job, Marital_Status, Education, Default_Credit, 
Housing_Loan, Personal_Loan) except the target variable with the SAS Enterprise 
Miner. I answered the following questions.
• What are the key segments for the whole dataset? Describe the main profiles. 
• What are the important variables considering the outcome? (Target: Subscribed)
• Are there different segments and profiles identified (as compared to what were
produced in Task 3)? If yes, what are they? Discuss the differences.


# Amazon_Vine_Analysis
## Overview of the analysis:
The purpose of this analysis was to understand what is 'Big Data', and how we can take the skills learned from previous modules to perform a simple (yet complicated in size) ETL. We leverage Amazon RDS/S3 services with PySpark to create various databases and store data in the cloud as opposed to our computers. For this specific analysis, we wanted to understand vine reviews of video games to see if there was any bias occuring between paid and unpaid users 

## Results:
Based on the analysis, we can determine the following:
- The total # of reviews was: 1785997, while the total number of 5 star reviews was: 1026924


- The total number of 5-Star & paid was 1607,  while the total number of 5-Star but unpaid was 1025317


- Given the above, the % of Paid vs unpaid was: .156% Paid & 99.84% Unpaid 


Summary:
Based on the analysis, there is absolutely no bias with paid 5 star vine reviews since it is an extremely small percentange of 5 star reviews. Based on the data, a separate analysis we could evaluate would be to evaluate the free text of the reviews using ML or NLP to determine what people may tend to say to generate a 5 star review. We could possibly predict key phrases/words that can obtain a 5 star review



# A/B testing project
The task is to evaluate the results of the A/B test. At your disposal there is a dataset with user actions, a technical task and several auxiliary datasets.  
- Evaluate the correctness of the test  
- Analyze the test results  
To assess the correctness of the test, check:  
- the intersection of the test audience with a competing test,  
- the coincidence of the test and marketing events, other problems of the time boundaries of the test.  
## Technical specification  
- Test name: recommender_system_test;  
- Groups: A (control), B (new payment funnel);  
- Launch Date: 2020-12-07;  
- Date of stopping the recruitment of new users: 2020-12-21;  
- Stop date: 2021-01-04;  
- Lecture hall: 15% of new users from the EU region;  
- Purpose of the test: testing of changes related to the implementation of an improved recommendation system;  
- Expected number of test participants: 6000.  
Expected effect: in 14 days from the moment of registration in the system, users will show an improvement in each metric by at least 10%:  
- conversions to product card views - product_page event shopping cart  
- views - product_cart  
- purchases - purchase.

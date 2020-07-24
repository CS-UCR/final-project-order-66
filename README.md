# Phase 2

1. The dataset we use was downloaded from Yelp. The total size of the dataset is enormous (10 GB) thus we trimmed it down to a manageable size and only selected dataset that we need for our program. The set includes:
    - *Yelp business*: This set includes the business IDs, names, locations and more on more than 200 thousands businesses ranging from restaurants to law firms and more in Northern America. We mainly focus on exploring and analyzing this dataset. 
    - *Yelp tips*:  This dataset contains a collection of messages about the tips and recommendation on numerous businesses in Northern America. This set is based on user opinions so we try to avoid using this in scientific projects. 
    - *Yelp reviews*: Similar to the tips dataset but with reviews. We also avoid this set.
    - *Yelp users and checkin*: These 2 sets have irrelevant data to our project thus we drop them.
    
    After carefully selected the data set that we need, we proceeded to apply the data cleaning strategies to clean up the dataset. By cleaning up, we remove irrelevant information from the set and group all the important information together nicely then put them into pandas data frames. We discovered some interesting observations during our EDA. Please refer to Data_Cleaning.ipynb for more information.
    
2. In addition, it seems we need more data to work with after trimming down the dataset we downloaded from Yelp. We also utilized Yelp Fusion API to obtain further information of 50 (the size limit of Yelp API response) restaurants in Riverside, CA. The response body form Yelp API has more than 20 columns of information ranging from location to alias to latitude or longitude. However, Only 3-4 columns of information out of those 20+ are relevant to our project thus we also applied data cleaning strategies to get the information we need. We also made some initial observations on the data set. Please refer to Yelp_API.ipynb for more details.
   
3. In term of running the code, our program was written in python3 on Jupyter notebook environment. However, because the data set we used was too large, we did not include it in this repo. Fortunately, the data set is free and open to download from Yelp database. Running our program on the Jupyter notebook environment with the supplemental Yelp data set should work as intended.   

# Phase 3

1. Although we are only required to come up with 2 questions/hypothesis for this phase, we tried to answer 5 questions we came up with during our phase 1. Out of those 5 Jose Castro did question 4. Henry Nguyen did questions 1 and 2. We might have to drop question 4 since there is no information that can help us answer the question. And, we need to do question 5 still.

2. There is no dependencies except for the Yelp data set stated above in point 3 of the Phase 2.

3. How we tackle the questions?
    1. For question 1 and 2: Henry used graphs to help him visualize the relations of the restaurants. He also used the classified numbers from the data frames to help him draw a conclusion to answer the questions. He did encounter a problem with question 2 but he was able to navigate and modified the question a little bit. Please see the Phase3.ipynb for a complete detail. 

# Phase 2

1. The dataset we use was downloaded from Yelp. The total size of the dataset is enormous thus we trimmed it down to a manageable size. The set includes:
    - *Yelp reviews*: 
    - *Yelp business*: This set includes the business IDs, names, locations and more on more than 50 thousands businesses ranging from restaurants to law firms and more in Northern America 
    - *Yelp tips*:  This dataset contains a collection of messages about the tips and recommendation on numerous businesses in Northern America
    - *Yelp users and checkin*: These 2 sets have irrelevant data to our project thus we drop them.
    
2. We also used Yelp Fusion API to obtain further information of 50 (the size limit of Yelp API response) restaurants in Riverside, CA. The response body form Yelp API has more than 20 columns of information. Unfortunately, we only need 3-4 columns of information out of those 20+ thus we also applied data cleaning strategies to get the information we need. Please refer to Yelp_API.ipynb for more details.
   
3. In term of running the code, our program was written in python3 on Jupyter notebook environment. However, because the data set we used was too large, we did not include it in this repo. Fortunately, the data set is free and open to download from Yelp database. Running our program on the Jupyter notebook environment and the supplemental data set on Yelp database should work as intended.   

need to include these:
• identifies and describes the datasets that were used,
• describe your web-crawler/scraper and the data that was obtained (how many pages, what
data was scraped from the pages, etc.)
• Contain information about how to run your code.

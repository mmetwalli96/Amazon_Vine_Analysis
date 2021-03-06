## Project Overview
---

In this project, there are approximately 50 datasets. Each one contains reviews of items, from clothing apparel to wireless products. One will be picked, and by using PySpark, the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin will be peroformed. Later, SQL will be used to determine if there is any bias toward favorable reviews from Vine members in the chosedn dataset.

## Results
--- 

The below table summerizes the results:

|Question|Answer|Supporting Figures|
|--------|------|-----------------|
|How many Vine reviews and non-Vine reviews were there?|613, 64968 respectively|![Capture 174](https://user-images.githubusercontent.com/59425631/137658128-9ea0cb3f-ee9a-4c38-a992-ae03852136de.PNG) ![Capture 175](https://user-images.githubusercontent.com/59425631/137658145-6f67cbae-e258-47fd-bee7-b577f2cfe6dc.PNG)|
|How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?|222, 30543 respectively|![Capture 176](https://user-images.githubusercontent.com/59425631/137658382-7145191c-ab68-4b6b-9c6e-58687c7930d6.PNG)![Capture 177](https://user-images.githubusercontent.com/59425631/137658393-edb9e294-aa25-4171-9f74-6fe235b86a55.PNG)|
|What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?|36.22%, 47.01% respectively|![Capture 173](https://user-images.githubusercontent.com/59425631/137658583-70d72eed-5235-4bc8-9efd-8a284a19c673.PNG)![Capture 172](https://user-images.githubusercontent.com/59425631/137658608-6c0ac88b-a02b-49ad-9407-ba4138ca01c9.PNG)|

## Summary
---

- Regarding the presence of positivity bias in the reviews, it is difficult to answer this concern as more data is needed. Almost half of non-vine members rated 5-stars for the products available in the dataset, and a little bit higher than one third of vine members rated 5-stars as well which indicates that vine members tend to avoid giving five stars rating compared to non-vine members. 
- To identify the presence of bias, data regarding the purchase of the item is needed as a review from a non-buyer is not as reliable as a fomer buyer. In addition to that, if data can be gathered to identify if there is trend of the person purchasing items from a particular company which might be an indication of preference that affects the credibility of the reviewer. 

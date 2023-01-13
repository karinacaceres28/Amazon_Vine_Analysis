# Amazon_Vine_Analysis

## Project Overview
The purpose of this project was to help one of BigMarket’s clients, SellBy to optimize their marketing efforts. Using PySpark, one dataset out of 50 was chosen to perform the ETL process to extract, transforsform the data, connect it to AWS RDS instance, and load the transformed data into pgAdmin. PySpark was then used to determine whether there was any bias towards more successful reviews from Vine members from the dataset.

## Results

### Figure 1: Total Reviews -- Paid vs Unpaid
<img width="462" alt="Total Reviews Paid:Unpaid" src="https://user-images.githubusercontent.com/110318652/212209414-7a273a5f-3a2e-44ca-b6a5-8d296f3eba5f.png">

    •	Top portion shows total number of paid reviews shows a total of 613.
   
    •	Bottom portion shows the total number of unpaid reviews is 64,968.


### Figure 2: Total Number of 5 Star Reviews -- Paid vs Unpaid
<img width="938" alt="Total Number of 5 Star Reviews Paid:Unpaid" src="https://user-images.githubusercontent.com/110318652/212209413-93787fc2-c01a-4718-baa5-010b40e30991.png">

    •	Top portion of the image shows the total number of 5-stars reviews for paid reviews is 222.
    
    •	Bottom portion of image shows the total number if 5-stars reviews for unpaid reviews is 30,543.


### Figure 3: Total Percentage of 5 Star Reviews -- Paid vs Unpaid
<img width="728" alt="Total Percentage of 5 Star Reviews Paid:Unpaid" src="https://user-images.githubusercontent.com/110318652/212209411-358661e7-8a83-47a9-97c4-8b74722ce33b.png">

    •	Top portion of figure shows the total percentage of 5-stars reviews for paid reviews is 36%.
    
    •	Bottom portion of figure shows the total percentage of 5-star reviews for unpaid reviews is 47%.
    
    
## Summary
After reviewing the data and comparing the paid and the unpaid reviews, there is no positive bias for reviews in the Vine program. The data shows that there are more non-Vine members inputting reviews compared to the Vine members. As shown in the data, there were only 222 5-star reviews for Vine members and 30,543 5-star reviews for non-Vine members. If we compare the percentage, Vine members were 36% shown to write 5-star reviews while non-Vine members had 47%. One additional analysis that could be done to support the statement above would be measuring the mean, median, and standard deviation of the total number of reviews for both Vine and non-Vine members.


# Will the Customer Accept the Coupon

### Problem Statement
The local bars and coffee shops have asked me for help in exploring this coupon dataset to gain a better understanding of the characteristics of customers who accepted a coupon they received versus those that did not, and to use these insights to help them make better decisions about what they should focus on when sending out their coupons.
### Data Cleaning
The first stage involved cleaning the data. Most of the data was fairly clean, but there was a car column that contained 99.15% missing values. The car column was not really useful for this data analysis, so I decided to remove it from the data. There were some other columns with missing values (i.e. Bar, CoffeeHouse, CarryAway, RestaurantLessThan20, Restaurant20to50), but luckily the missing values made up less than 2% of their respective columns. These columns showed how many times a month the driver went to these places which made it difficult to impute these missing values, so I decided to drop these missing value rows from the data as it only made up a small portion of the overall dataset.
### EDA
The cleaned dataset consisted of 12,079 rows and 25 columns. Overall, out of the 12,079 coupons offered **56.93%** were accepted. In terms of distribution of coupon types, 

![Coupons](images/Most_Coupons_Were_For_A_Coffee_House.png)
### Findings

### Next Steps and Recommendations

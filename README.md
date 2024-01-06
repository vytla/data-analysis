# Will a Customer Accept the Coupon?

### Overview 
The goal of this project is to use visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those that did not.

Data comes from the UCI Machine Learning repository and was collected via a survey on Amazon Mechanical Turk.The survey describes different driving scenarios including the destination, current time, weather, passenger, etc., and then ask the person whether he will accept the coupon if he is the driver. Answers that the user will drive there 'right away' or 'later before the coupon expires' are labeled as 'Y = 1' and answers 'no, I do not want the coupon' are labeled as 'Y = 0'. There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, carry out & take away, bar, and more expensive restaurants ($20 - $50).

Following are the observations from Data Analysis and Project Notebook can be found [here](./prompt.ipynb).

1. Overall 56.8% of total observations choose to accept the coupon

![Overall Coupons Acceptance](./images/Overall_Acceptance.png)

2. Coupon Accetpance by Coupon types - Coffee House ans Restaurants have better coupon acceptance 

![Acceptance By Coupon tyles](./images/Acceptance_by_coupon_types.png)

3. Types of Coupons Accetpance at Different Tempratures 
- When temperatures are above 50, Customers/Drivers are preferring Coffee House and Carry out & Takeaway coupons
- When temperatures are high at around 80, Customers/Drivers are accpeting Restaurant coupons in less than 20 miles

![Acceptance By Temprature](./images/Acceptance_by_temprature.png)

4. Coupons Accetpance with Marital Status
- Married Partner drivers accepted coupon types of Restaurants 20 mins away, carry out & Take away and coffee houses more compared to other coupon types
- Single drivers and Married Partners have accepted majority of the coupons

![Acceptance By Marital Status](./images/Acceptance_by_Marital_Status.png)

![Acceptance By Marital Status 2](./images/Acceptance_by_Marital_Status1.png)

5. Total Bar Coupons Acceptance Rate

- 59.0% of Bar coupons were accepted

![Acceptance of Bar Coupons](./images/Total_Bar_Coupons_Accepted.png)

6. Bar Coupons Accepted Less than 3 vs Greater than 3

- Acceptance Rate of Customers/Drivers who went to a bar 3 or more times is 7.61%
- Acceptance Rate of Customers/Drivers who went to a bar less than 3 times is 12.79%

![Acceptance of Bar Coupons greater than 3](./images/Acceptance_Greater_than_3.png)

7. Acceptance rate for Drivers who go to Bar with age greater than 25

- Only 20.9% of Drivers/Customers who are older than 25 accepted Bar coupons.
- Drivers/Customer with Age 26 and 31 years have higher acceptance rate for Bar coupons.

![Acceptance rate for Drivers who go to Bar with age greater than 25](./images/Acceptance_Pie_greater_than_25.png)

![Acceptance rate for Drivers who go to Bar with age greater than 25 Histogram](images/Acceptance_Histplot_greaterthan_25.png)

8. Drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry

- Total 71.3% of coupon acceptance rate for Driveres/Customers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry

![occupations other than farming, fishing, or forestry](images/Acceptance_farming.png)

9. Total 71.4% of coupon acceptance rate for Drivers go to bars more than once a month, had passengers that were not a kid, and were not widowed OR Drivers go to bars more than once a month and are under the age of 30 OR Drivers go to cheap restaurants more than 4 times a month and income is less than 50K.

![Consolidated Acceptance](images/Consolidated_Acceptance.png)



Following are few observations from the data analysis for drivers who used Carry out & Take away coupons : 

1. 74.4% of the drivers accepted "Carry out & Take away" coupons
2. Majority of Carry out & Take away Coupons were accepted during Sunny Day.
3. Less Carry out & Take away coupons on Rainy day than any other weather(Sunny or Snowy)
4. 91% of the driveres used "Carry out & Take away" coupons in Reverse direction
5. Acceptance Rate of Customers/Drivers who used  Carry Out & take away coupons 3 or more times is 35.03%
6. Acceptance Rate of Customers/Drivers who used  Carry Out & take away coupons less than 3 times is 27.39%

Similar analysis can be done on other Coupons like Coffee House, Restaurant. 
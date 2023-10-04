Practical Application Assignment 5.1: Will the Customer Accept the Coupon?

This report to answer the question, will customer accept the coupon assigment. 
The link to anlysis: https://github.com/diaa-majed/Assignment_5.1.git

The link to Jupyter notebook: https://github.com/diaa-majed/Assignment_5.1/blob/main/Diaa-prompt.ipynb

Check the image folder for plots 

Date Missing 
The below is summery of missing data 
Column	Number of missing values
car	 12576
Bar	107
CoffeeHouse 	217
CarryAway  	151
RestaurantLessThan20 	130
Restaurant20To50 	189

Data Cleaning 

- [ ] “car’ column has too many missing values so delete the columns 
- [ ] Replace NaN  in Bar, CoffeeHouse, CarryAway, RestaurantLessThan20 and Restaurant20To50 with never 
- [ ] Noticed never and less1 which means the same so replaced both with '0' and replace  gt8  with 8-Or-Mor so all ranges start with number 


Summary of Findings

Number of coupons 
coupon	Number
Bar	2017
Carry out & Take away	2393
Coffee House  	3996
Restaurant between $20 -$50	1492
Restaurant under $20 	2786

Acceptance Rate
coupon	Number
Bar	41.00%
Carry out & Take away	44.10%
Coffee House  	49.92%
Restaurant between $20 -$50	44.10%
Restaurant under $20 	70.71%
The highest  accetance coupon is Restaurant under $20 

What proportion of the total observations chose to accept the coupon? 
proportion of the total observations chose to accept the coupon: 7210

What proportion of bar coupons were accepted?
proportion of bar coupons were accepted : 827

Compare the acceptance rate between those who went to a bar 3 or fewer times a month to those who went more.
Acceptance Rate for went to a bar 3 or Fewer Times: 54.46%
Acceptance Rate for went to a bar More than 3 Times: 62.25%

Compare the acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others. Is there a difference?
Acceptance Rate for Drivers Going to a Bar More than Once a Month and Over 25: 62.14%
Acceptance Rate for All Other Drivers: 62.41%
The differnce in acceptance rate between drivers over 25 to the all others: 0.27%

Use the same process to compare the acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry. 
Acceptance Rate for Drivers Going to Bars More than Once a Month and Meeting Criteria: 62.31%
Acceptance Rate for All Other Drivers: 54.60%
The differnce in acceptance rate between drivers over 25 to the all others: 7.72%

Compare the acceptance rates between those drivers who:

- Acceptance Rate for go to the bar once, no kid and not widowed: 62.31%

- Acceptance Rate for go to the bar once and are under the age of 30: 62.85%

- Acceptance Rate for go to cheap restaurants more than 4 times and income is less than 50K:  58.20%



Based on these observations, what do you hypothesize about drivers who accepted the bar coupons?
- [ ]  From the analysis  above, the highest acceptance rate is 62.85% for the group go to the bar once and are under the age of 30
- [ ] I used seaborn to virtualize acceptance group by age, marital Status, and passenger.. 
    - [ ] For Bar coupon, age 21, single, with friends is highest to accept it. 
    - [ ] For Coffee House coupon, age under 21, single with Friends
    - [ ] For Restaurant under $20 coupon, single with friend. Almost all Aage accept the coupon

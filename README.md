# Bikesharing-Challenge
# Overview of the analysis
The overview of this project is to figure out how the bike-share business works out in NYC. From there, we'll create a proposal on how it might work in Des Moines.
## Purpose of the analysis
Use Pandas to change "tripduration" column from integer to a datetime datatype. Then, using the converted datatype, you'll create a set of visualizations to:
(1) Show the length of time that bikes are checked out for all riders and genders.
(2) Show the number of bike trips for all riders and genders for each hour of each day of the week.
(3) Show the number of bike trips for each type of user and gender for each day of the week.
# Results
![Checkout Times for Users](https://github.com/arelysrsd87/Bikesharing-Challenge/blob/main/Images/checkout%20times%20for%20users.jpg)
Checkout Times for Users graph shows most bikes are rented for lesst than hour, more precisely, for 10 minutes.

![Checkout Times by Gender](https://github.com/arelysrsd87/Bikesharing-Challenge/blob/main/Images/checkout%20times%20by%20gender.jpg)
Checkout Times by Gender graph shows all genders follow the same trend of short checkout times.

![Trips by Weekday per Hour](https://github.com/arelysrsd87/Bikesharing-Challenge/blob/main/Images/trips%20by%20weekday%20per%20hour.jpg)   
Trips by Weekday per Hour graph shows there is a higher density for checkout bikes on weekdays during the morning (7-9 A.M.) and evening (5-7 P.M.) commutes. Weekend days show bikes are rented consistently thoroughout the day.

![Trips by Gender](https://github.com/arelysrsd87/Bikesharing-Challenge/blob/main/Images/trips%20by%20gender%20weekday%20per%20hour.jpg)    
Trips by Gender (Weekday per Hour) graph shows a higher density of the male population renting bikes during the morning and evening commutes. However, the female population follows the same trend.

![User Trips by Gender by Weekday](https://github.com/arelysrsd87/Bikesharing-Challenge/blob/main/Images/user%20trips%20by%20gender%20by%20weekday.jpg)    
User Trips by Gender by Weekday shows data broken down by both usertype (customer versus subscriber), weekday and by gender. The main takeaway is the higher density of user trips is by the male subscribers on weekdays.

![Customers](https://github.com/arelysrsd87/Bikesharing-Challenge/blob/main/Images/customers.jpg)   
The customers pie chart shows there is 8:2 ratio between subscribers:customer usertypes.

![Gender breakdown](https://github.com/arelysrsd87/Bikesharing-Challenge/blob/main/Images/gender%20breakdown.jpg)     
The gender breakdown pie chart shows 65% of the usertypes are males, 25% are females and 10% are unknown.

![August Peak Hours](https://github.com/arelysrsd87/Bikesharing-Challenge/blob/main/Images/August%20peak%20hours.jpg)   
The August Peak Hours graph shows most bikes are rented during morning hours of 8-9 A.M. and evening hours of 6-7 P.M. The lowest valley for renting bikes is from 3-4 A.M. We recommend this time for any bike upkeep.

# Summary
[Bike-sharing Challenge](https://public.tableau.com/app/profile/arelys.rosado/viz/BikesharingChallenge_16245815694580/Bike-sharingChallenge)
We can summarize the length of most trips is of short duration, approx. 10 minutes. Additionally, the male population is the lead renter, renting mostly on weekdays during the 7-9 A.M and 5-7 P.M. windows. This strongly suggest bikes are being rented as an alternative method to public transportatin for the morning and evening commutes. We recommend for future analysis to 
(1) analyze which stations are mostly used and the zoning around and
(2) how many bikes are needed during peak hours and if the business is meeting the demand. 

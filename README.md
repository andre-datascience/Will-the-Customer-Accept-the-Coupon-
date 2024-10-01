# Will-the-Customer-Accept-the-Coupon-
Required Assignment 5.1: Will the Customer Accept the Coupon?

Driving Coupon Acceptance Analysis

Overview
This project analyzes data from the UCI Machine Learning Repository, collected via a survey on Amazon Mechanical Turk. The survey describes various driving scenarios and asks participants whether they would accept a coupon if they were the driver. The goal is to distinguish between customers who accepted a driving coupon versus those who did not, using visualizations and probability distributions.

Data Description
The dataset includes the following attributes:

User Attributes

Gender: Male, Female

Age: Below 21, 21 to 25, 26 to 30, etc.

Marital Status: Single, Married partner, Unmarried partner, Widowed

Number of Children: 0, 1, More than 1

Education: High school, Bachelor’s degree, Associate’s degree, Graduate degree

Occupation: Various categories (e.g., Architecture & Engineering, Business & Financial)

Annual Income: Various ranges (e.g., Less than $12,500, $12,500 - $24,999, etc.)

Frequency of Visits:

Bars

Takeaway food

Coffee houses

Restaurants (less expensive, under $20 per person)

Restaurants (more expensive, $20 - $50 per person)

Contextual Attributes

Driving Destination: Home, Work, No urgent destination

Location: Geographical location of the user, destination, and venue

Weather: Sunny, Rainy, Snowy

Temperature: 30°F, 55°F, 80°F

Time: 10 AM, 2 PM, 6 PM

Passenger: Alone, Partner, Kid(s), Friend(s)

Coupon Attributes

Type: Less expensive restaurants, Coffee houses, Carryout & takeaway, Bars, More expensive restaurants

Expiration: 2 hours, One day

Labels
Y = 1: Accepted the coupon (“Right away” or “Later, before the coupon expires”)
Y = 0: Did not accept the coupon (“No, I do not want the coupon”)


Analysis and Findings
The analysis will focus on identifying patterns and factors that influence coupon acceptance. Key areas of exploration include:

Differences in acceptance rates based on user demographics (e.g., age, gender, marital status)
Impact of contextual factors (e.g., weather, time of day, driving destination)
Influence of coupon type and expiration time on acceptance rates

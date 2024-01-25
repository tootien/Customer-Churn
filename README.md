# Customer Churn Prediction

Churn rate is a marketing metric that describes the number of customers who leave a business over a specific time period. Every user is assigned a prediction value that estimates their state of churn at any given time. This value is based on:
1. User demographic information
2. Browsing behavior
3. Historical purchase data among other information
# Dataset
User demographic information Browsing behavior Historical purchase data among other information It factors in our unique and proprietary predictions of how long a user will remain a customer. This score is updated every day for all users who have a minimum of one conversion. The values assigned are between 1 and 5.
|Column name	| Description|
|:------------:|:------------:|
|customer_id | Represents the unique identification number of a customer|
|Name | Represents the name of a customer|
|age | Represents the age of a customer|
|security_no | Represents a unique security number that is used to identify a person|
|region_category | Represents the region that a customer belongs to|
|membership_category | Represents the category of the membership that a customer is using|
|joining_date | Represents the date when a customer became a member|
|joined_through |  referral	Represents whether a customer joined using any referral code or ID|
|referral_id | 	Represents a referral ID|
|preferred_offer types | 	Represents the type of offer that a customer prefers|
|medium_of operation | 	Represents the medium of operation that a customer uses for transactions|
|internet_option | 	Represents the type of internet service a customer uses|
|last_visit time | 	Represents the last time a customer visited the website|
|days_since last login | 	Represents the no. of days since a customer last logged into the website|
|avg_time spent | 	Represents the average time spent by a customer on the website|
|avg_transaction value | 	Represents the average transaction value of a customer|
|avg_frequency login days | 	Represents the no. of times a customer has logged in to the website|
|points_in wallet | 	Represents the points awarded to a customer on each transaction|
|used_special discount | 	Represents whether a customer uses special discounts offered|
|offer_application preference | 	Represents whether a customer prefers offers|
|past_complaint | 	Represents whether a customer has raised any complaints|
|complaint_status | 	Represents whether the complaints raised by a customer was resolved|
|feedback | 	Represents the feedback provided by a customer|
|churn_risk score | 	Represents the churn risk score that 0 or 1|

## Content
1. Loading dataset
2. Exploratory Data Analysis
3. Data Preprocessing
4. Feature Engineering
5. Model Part
6. Discussion & Conclusion

## Conclusion
**Comment:**

* XGBoost and Random Forest Classification algorithms give the highest prediction results with 78% when using classification model measure acccuracy
* After selecting the important attributes, we observed that the results did not change significantly in comparison to using all the attributes. From this observation, we can conclude that the unimportant attributes do not have much impact on the model's performance.
* According to the confusion matrix chart to evaluate the accuracy of classification models such as XGBoost and SVM, the mispredicted values of a label are usually distributed to the neighboring labels, and we can divide them into two clusters ({1,2} and {3,4,5}) that are often confused with each other. Therefore, we created a new target attribute with two labels of 0 and 1, respectively, corresponding to these two clusters. Overall, the prediction accuracy of the models improved significantly with a rate above 80%, and the highest rate achieved was 94%.

To retain customers, we need the following solutions:

1. **Website Improvement:** Our website should boast a sleek design, user-friendly interface, detailed product/service information, transparent pricing, and comprehensive customer care and quality assurance policies. A well-crafted website not only leaves a positive impression but also facilitates easy navigation and understanding of our offerings.

2. **Product Quality:** The quality of our products significantly influences customer trust. If our products meet high standards, customers are more likely to repurchase from us rather than exploring alternatives. Prioritizing product quality is paramount in establishing long-term relationships with customers.

3. **Professional Customer Service:** A dedicated and professional customer service team is a crucial factor in customer retention. Employees should be well-trained to address customer issues promptly and effectively. This commitment to customer satisfaction fosters loyalty and increases the likelihood of repeat business.

4. **Reduce Advertising Clutter:** Excessive advertising can create discomfort for customers and deter them from making future purchases. It's essential to streamline advertising messages, focusing on strategies that are effective without overwhelming the customer. This approach helps maintain customer interest without causing irritation.

**Conclusion:** By combining website enhancement, product quality assurance, professional customer service, and a mindful advertising strategy, we can enhance our customer retention capabilities. Long-term relationships built on trust and satisfaction are key to sustained success in business.

# Data Biography

## Student Number: 20104329

---

### 1. Who collected the data?
An independent, non-commercial project called "Inside Airbnb" collected this data from  Airbnb website.


---

### 2. Why did they collect it?

The data collected by the project are used to analyze which the phenomenon of illegal rendering exists in such a short-term rental platform on Airbnb (such as long-term rent) and the impact on the residential community(such as gentrification caused by landlords buying properties to rent on Airbnb).

---

### 3. How was it collected?

The project collected all listing information available to users of the airbnb website. The data include the house location, price, number of bedrooms and bathrooms etc., and the list of all reviews from guests who have stayed at the property is also collected.

---

### 4. What useful information does it contain?


There are mainly three types of data useful for analysis. The first type of data is related to rental houses, including the most important coordinate data :'latitude','longitude', rental houses type data:'property_type',rental price:'price', and houses’ facilities:'amenities','bathrooms_text','bedrooms'. The second category is the house host’s relevant data, including the house host’s location:’host_location’ and the total number of house of them:’host_total_listings_count’. The third category is the review data of rental houses, the evaluation level of rental houses is ‘review_scores_rating’, and the different scoring levels of each element such as ‘review_scores_cleanliness’, ‘review_scores_location’, etc.

---

### 5. What useful information is it missing?

The most serious missing fields include whether you have a house rental identity certificate: 'license'. In addition, there are many missing data in the fields related to the host, such as'host_about','host_response_rate' and reviews such as 'review_scores_rating'.

---

### 6. To what extent is the data 'complete'?

This data set has systematic omissions and random data missing. Systematic omissions include the fact that the data set does not include the tenant’s text comment field; there is also no building number for rent. Because the coordinate data ('latitude','longitude') of InsideAirbnb is the approximate coordinates within a range of 150 meters[1] after fuzzy processing, without a virtual code, it is difficult to quantify housing market impacts. As for randomly missing data, this data set has a large number of NaN values, including random loss (MSR) and non-random loss (MNAR). The former appears irregular, such as in the fields of'host_location','bedrooms', etc.; The other is because of platform data feedback caused by comments-related fields and deliberately hiding fields such as'license' to avoid government supervision problems.

---

### 7. What kinds of analysis would this support?

First of all, this data set can support Murray Cox's concerns about illegal short-term rental and community gentrification research. The former can draw a general conclusion of the city by analyzing the fields of rental houses and the number of rental days per 365 days; the latter can be combined other data to analyzes, uch as census data, property market data, etc. In addition, the data set can also analyze the following issues: How many hosts have multiple houses to rent at the same time, and locations; the distribution of urban tourist hotspots and popular areas in the urban real estate market; the relationship between rental housing pricing and its demand; relevance of tenant satisfaction to facilities and locations, etc.

---

### 8. What kinds of analysis would it _not_ support?

Because it did not grab the text review data of the tenants, the data set was difficult to analyze the trend of tenants' concern, and can not mine the expectations and most concerned content of tenants. Secondly, a large amount of NaN values makes it difficult to perform corresponding analysis. For example, due to the missing'license' field, it cannot support the analysis of the standardization and legalization ratio of the Airbnb rental market.

---

### 9. Which of the uses presented in Q.7 and Q.8 are _ethical_?

In the analysis mentioned in questions 7 and 8, all analyses are ethical except for the analysis of hosts’ properties and the comments of tenants. The research on landlord related issues will cause digital identity security problems. From the current data set, we can extract the hosts’ name, location, the number of properties under their control and other objective information, as well as the their self description text information. By combining the above information with other social platform data (Facebook, twitter), we can get the hosts’ accurate personal portraits, the study of communities and groups, is transformed into the disclosure of individual information, which destroys the balance between security and privacy [2] and is contrary to moral norms. By mining the text information of renters, the problem of data neutrality will be caused, Lauren Klein tells a story about a face recognition algorithm that is difficult to recognize black people because of the small proportion of black people in practice data [3]. The same is true for text information mining. Properties’ hosts can adjust the type of rental housing by analyzing the content that users are most concerned about. After that, the rental market will change accordingly, so that the orientation of old users will force new users to accept their tendency, which opposite to Feynman's view that the responsibility of science to society lies in the unpredictability of the open future [4].

### Reference

[1] Cox,M.( 2016 ). About Inside Airbnb. Retrieved from http://insideairbnb.com/about.html

[2] Nicole Gurran & Peter Phibbs (2017) When Tourists Move In: How Should Urban Planners Respond to Airbnb?, Journal of the American Planning Association, 83:1, 80-92

[3] Catherine D'Ignazio & Lauren Klein(2019) . Introduction. Retrieved from https://mitpressonpubpub.mitpress.mit.edu/pub/dgv16l22/release/6

[4] Amoore, L. (2019) 'Doubt and the algorithm : on the partial accounts of machine learning.', Theory, culture society., 36 (6). pp. 147-169.

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

The project collects all listing information available to users of the airbnb website. The data include the house location, price, number of bedrooms and bathrooms etc., and the list of all reviews from guests who have stayed at the property is also collected.

---

### 4. What useful information does it contain?


There are mainly three types of data useful for analysis. The first type of data is related to rental houses, including the most important data - location:'latitude','longitude', rental houses type data:'property_type',rental price:'price', and houses’ facilities:'amenities','bathrooms_text','bedrooms'. The second category is the house host’s relevant data, including the house host’s location:’host_location’ and the total number of house of them:’host_total_listings_count’. The third category is the review data of rental houses, the evaluation level of rental houses is ‘review_scores_rating’, and the different scoring levels of each element such as ‘review_scores_cleanliness’, ‘review_scores_location’, etc.

---

### 5. What useful information is it missing?

The most serious missing fields include whether you have a house rental identity certificate: 'license'. In addition, there are many missing data in the fields related to the landlord, such as'host_about','host_response_rate'.

---

### 6. To what extent is the data 'complete'?

_Your answer here_
This data set has systematic omissions and random data missing. Systematic omissions include the fact that the data set does not include the tenant’s text comment field; there is also no building number for rent. Because the coordinate data ('latitude','longitude') of InsideAirbnb is the approximate coordinates within a range of 150 meters[1] after fuzzy processing, without a virtual code, it is difficult to quantify housing market impacts. As for randomly missing data, this data set has a large number of NaN values, including random loss (MSR) and non-random loss (MNAR). The former appears irregular, such as in the fields of'host_location','bedrooms', etc.; The other is because of platform data feedback caused by comments-related fields and deliberately hiding fields such as'license' to avoid government supervision problems.
---

### 7. What kinds of analysis would this support?

First of all, this data set can support Murray Cox's concerns about illegal short-term rental and community gentrification research. The former can draw a general conclusion of the city by analyzing the fields of rental houses and the number of rental days per 365 days; the latter can combine other data to analyzes, such as census data, property market data, etc. In addition, the data set can also analyze the following issues: How many hosts have multiple houses to rent at the same time, and locations; the distribution of urban tourist hotspots and popular areas in the urban real estate market; the relationship between short-term rental housing pricing; relevance of tenant satisfaction to facilities and locations, etc.

---

### 8. What kinds of analysis would it _not_ support?

Because it did not grab the text review data of the tenants, the data set was difficult to analyze the trend of tenants' concern, and can not mine the expectations and most concerned content of tenants. Secondly, a large amount of NaN values makes it difficult to perform corresponding analysis. For example, due to the missing'license' field, it cannot support the analysis of the standardization and legalization ratio of the Airbnb rental market.

---

### 9. Which of the uses presented in Q.7 and Q.8 are _ethical_?

_Your answer here_

# The impact of various customer characteristics on the acceptance of a coupon for services #
The goal of this project is to evaluate a set of data gathered for a pilot program where coupons for discounted services for a few types of establishments (Bars, Restaurants, etc) were offered to potential customers.
Data was logged on each potential customer and the outcome of the offer (acceptance or rejection) was recorded.
We are to assess these characteristics and their impact on acceptance rates 

* The programming language used is Python, and the libraries used were: Pandas, Seaborn, Matplotlib, and numpy ####

* All work, including analysis, observations, findings, and next steps are included in the following Jupyter Notebook:

    [Completed Jupiter Notebook](https://github.com/matt-moline/coupon/main/MattMolinePractApp51.ipynb)

* The data set is located at [Coupon Dataset](https://github.com/matt-moline/coupon/main/data/coupons.csv)
  
* The data quality was generally very good, with minimal missing data for most columns

## Findings ##
 
*  For the subset of data related to the offering of coupons for use at Bars, I observed the following observations:
   - Frequency of times per month a potential customer accepted the coupon has an impact on the acceptance rate.  The more times they go the more likely they are to accept the offer.
   - Age of the consumer appears to have minimal or nop impact on acceptance rate.
   - Occupations in the Farming, Fishing, or Forestry sectors have minimal or no impact
   - The combo of lower income and times visiting inexpensive restaurants each month has a slight negative impact on acceptance, i.e. the more they frequent inexpensive restaiurants and/or the lower the salary, the lower the acceptance rate.
   - Not being widowed appears to have a positive influence on the acceptance rate.

* For the subset of data related to the offering of coupons for use at mid-range restaurants (avg $20-50), I observed the following:
    - Sunny weather has a slightly positive increase on acceptance (46.4% for sunny weather vs 44.1% for all situations) Rainy weather discourages acceptance while snowy weather has even more of a negative impact, reducing by over 1/3 the acceptance rate.
    - driving alone has a slight negative impact on acceptance and riding with kids a larger negative impact. Riding with a partner has a significant positive impact while having friends in the car has a slightly positive impact.
    - There is a slight positive impact on acceptance for the two groups representing the ages of 26 through 41.  Under 26, we see know real impact, while there is a noticable impact on acceptance when over 41.

## Next Steps ##

*  For the subset of data related to the offering of coupons for use at Bars, next steps identified are:
   - Frequency of times per month a potential customer accepted the coupon has an impact on the acceptance rate.  The more times they go the more likely they are to accept the offer.
   - Age of the consumer appears to have minimal or nop impact on acceptance rate.
   - Occupations in the Farming, Fishing, or Forestry sectors have minimal or no impact
   - The combo of lower income and times visiting inexpensive restaurants each month has a slight negative impact on acceptance, i.e. the more they frequent inexpensive restaiurants and/or the lower the salary, the lower the acceptance rate.
   - Not being widowed appears to have a positive influence on the acceptance rate.

* For the subset of data related to the offering of coupons for use at mid-range restaurants, next steps identified are:
      - I would like to see a similar analysis performed on all data points
      - Once all observations are complete, I would rank the factors in terms of those most impactful on acceptance
      - I would then observe the acceptance for a few combinations of those criteria identified
      - I would then develop marketing tactics and strategies aimed at the target audiences to roll out a more expansive Coupon program

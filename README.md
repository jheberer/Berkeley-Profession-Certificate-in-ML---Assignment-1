# Berkeley-Profession-Certificate-in-ML---Assignment-1
## Will a customer accept a coupon?

The notebook used to compile this report is here: https://github.com/jheberer/Berkeley-Profession-Certificate-in-ML---Assignment-1/blob/main/coupon.ipynb

## Problem Statement
Will a customer accept a coupon?

By analyzing the results of a marketing campaign where drivers receive coupons directly onto their cell phones, we can determine which factors impact whether the driver will accept.

## Approach
The initial prompt was to investigate bar coupons, and is outside of the scope of this report.
However, during this initial analysis it was identified that Coffee House coupons are the highest volume coupon sent to drivers.
![image](https://github.com/jheberer/Berkeley-Profession-Certificate-in-ML---Assignment-1/assets/7217117/508fcfba-1b7d-4a4f-a481-1793277cf07f)

Despite this, the acceptance rate was middling compared to the other coupon types--a poor investment from business trying to drive coupon acceptance.
![image](https://github.com/jheberer/Berkeley-Profession-Certificate-in-ML---Assignment-1/assets/7217117/38e8d252-5ed9-484a-ac78-729ca5799231)

Therefore, this analysis services as a potential way to drive massive ROIs for local businesses.

## Results

Many datapoints influenced the acceptance rate of the Coffee House coupons:
* destination: higher when there's no urgency
* passanger: higher when there is a "social" passanger--friend or partner
* weather: lower when snowy
* time: higher in the early hours
* expiration: higher when it doesn't expire right away
* age: higher for below 21
* education: highest for some high school, lowest for bachelor's
* occupation: lots of variation--difficult to interpret based on this plot alone
* monthly frequency of coffee house visits: higher if the driver visits coffee houses more frequently per month

The factors that most influenced the results were the time of day the coupon was sent, age, and occupation.
Intuitively, coupons sent in the morning were more likely to be accepted, as morning is the traditional coffee-drinking time of day.
![image](https://github.com/jheberer/Berkeley-Profession-Certificate-in-ML---Assignment-1/assets/7217117/94f1fadf-1ad3-41ba-ab0c-3e4d49be548e)

The below 21 age group accepted the coupons at an incredibly high rate, about 68% of the time.

There was an incredible variation in the acceptance rate amongst occupations. 
The occupations that had the highest acceptance rates are traditionally associated with long days, which might explain the trend.

![image](https://github.com/jheberer/Berkeley-Profession-Certificate-in-ML---Assignment-1/assets/7217117/a609ae48-54b2-45bb-a741-4e44c3d11517)

## Recommendation
Target individuals of the identified occupations, as well as young people (under 21) for promotions.
Target the promotions during the morning hours, and ideally not during snowy weather.

Further, there are some next steps that we should take to improve on this even further.

## Next Steps
The below 21 age group is a small market, with small disposable income, that is very transient.
We would benefit financially if we could identify and prove causation as to why these individuals accept the coupon at such a high rate.
If we could determine this, we could maintain a high acceptance rate with the individuals even as they "age up" to the next age groups.
We may need to acquire more data, such as survey data into their overall tastes.

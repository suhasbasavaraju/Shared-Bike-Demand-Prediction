# Shared-Bike-Demand-Prediction

### Problem Statement 

BoomBikes, a US-based bike-sharing provider, is facing revenue challenges due to the COVID-19 pandemic. To prepare for a post-pandemic market recovery, they aim to identify the key factors influencing the demand for shared bikes in the American market. They seek answers to:

The significant variables impacting bike demand prediction.
The effectiveness of these variables in describing bike demand patterns.

### Findings Summary:

#### During the Exploratory Data Analysis (EDA) process, several insights regarding the dependent variable (cnt) in relation to categorical variables were observed:

A minor negative correlation was detected between humidity (hum) and bike demand (cnt).

Bike usage is significantly higher during the fall and summer seasons, while it notably decreases in the spring season.

Demand for shared bikes is considerably lower during rainy weather conditions, as riders tend to avoid snow or rain.

There is a noticeable upward trend in bike usage from 2018 to 2019.

Notably, lower demand is observed on non-holiday days, despite the upper bound values being consistent across holidays and non-holidays.

Interestingly, whether it's a working day or not has little impact on the number of bike users.

Bike demand peaks in June, followed by May and July, whereas it hits its lowest point in January and February.

#### In the final model, the most influential features explaining shared bike demand are:

Temperature (temp) - With a coefficient of 0.477, an increase in temperature by one unit corresponds to a 0.477 unit increase in bike rentals.

Year (2019) - A yearly increase of 0.234 units in bike bookings is observed.

Rainy Weather (rainy) - A coefficient of -0.280 suggests that bookings decline by 0.280 units during stormy, thunderous, or rainy weather conditions.

These findings provide valuable insights for understanding and predicting shared bike demand, aiding in effective decision-making for bike-sharing operations.

##### Please note that detailed insights obtained at each stage of the variable analysis have been thoughtfully documented as comments within the Jupyter Notebook for reference and transparency.







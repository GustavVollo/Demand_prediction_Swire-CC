# Demand Prediction For Swire Coca-Cola
## Case competition as a capstone project at the University of Utah MSBA program.
### Project Overview: Enhancing Production Efficiency with ARIMA Modeling
The Swire Coca-Cola project focuses on forecasting demand for limited-release products using an ARIMA model to prevent overproduction and shortages. This approach optimizes production to match evolving consumer preferences, enhancing revenue growth and cost efficiency. The notebook details the modeling, data preparation, and validation efforts to support strategic decision-making.

### Personal Contribution: Addressing Forecasting Challenges for a New Product Launch
For Question 7, I focused on coding aspects to predict the demand for the "Peppy Gentle Drink Pink Woodsy .5L Multi Jug" over a 13-week period in the Southern region. Using linear regression and rpart, I found these models produced higher r-squared values compared to others. However, a significant finding was the broad demand range predicted by various models, from 59,000 to 222,500 units. This range highlighted the challenges in relying solely on these predictions. I concluded that ARIMA-modeling, which factor in seasonality, could provide more reliable forecasts, especially during a new product's launch period.

### Team Insights: Forecasting Demand for New Flavors with Historical Data
In tackling the challenge of forecasting demand for a new energy drink flavor, we initially struggled with machine learning due to limited data and expertise. Ultimately, we used historical data from 2021 to project demand into 2024, considering the typical sales surge at launch and subsequent decline. We adjusted our forecasts using a package conversion ratio and factored in a two-year market growth of 8.1%, leading to a final demand estimate. We recommend further market research to refine these projections, particularly since Swire is new to this flavor in the energy drink market.

### Risk Management in Forecasting: Balancing Over and Underforecasting Costs
Based on the cost of underforecasting and overforecasting with a ratio of 1 to 5, meaning cost is 4 times higher with overforecasting, we used normal distribution confidence intervals to give Swire Coca-Cola our best predictions. We utilized the ARIMA model as the baseline. 

<img src="/Prediction_demand.png?raw=true"/>

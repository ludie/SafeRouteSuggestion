# Safe Route Suggestion

![alt text](https://github.com/6242DVAteam46/CarAccidentVisualization.github.io/blob/223b6b7f96b6e7ba379cb1b271375cd1a7b4e542/pics/header_cover_junction.jpg)

## Motivation
**As the number of car accidents continues to increase in the United States**, there's a wealth of data available that could be used to better understand and improve safety on the roads.

We've been working on a Real-time Safety Index in the state of Georgia that combines accident data, weather conditions, time of day, and more to provide up-to-the-minute safety assessments for different routes. This could **help users make informed decisions based on current road conditions**, reducing the risk of accidents. We've been also developing Predictive Route Planning using historical data to predict the likelihood of accidents on specific routes. This allows users to choose safer paths, enhancing overall road safety. Additionally, we've developped lots of dynamic data visualizations to help users explore accident patterns and safety indices, fostering a deeper understanding of road safety.

Caring about this project is crucial because it directly addresses the escalating issue of road safety. Our tools empower individuals to make informed decisions based on current conditions, decide safer routes, and contribute to a collective effort in reporting real-time information. **Investing in this project means investing in technologies that have the potential to prevent accidents, save lives, and improve overall road safety.**

## Dataset
For this project we used the Kaggle dataset of US accidents from 2016 to 2023. This is a countrywide car accident dataset that covers 49 states of the USA. The dataset contains and detailing geographical, meteorogical and dynamical information about 7.7 million accident records.

Futher detail please refer: [6242DVAteam46/CarAccientVisualization.github.io](https://github.com/6242DVAteam46/CarAccidentVisualization.github.io.git)

## Prediction model approches:
We first had to create a graph **G = {V,E}** of intersections **V** and road segments **E**, assigning accident locations to the least-squared closest roads. The resulting graph captures the number of accidents per road segment in the state of Georgia. By defining a path planning algorithm, it is enough to modify the weights of the graph (the real distance between each intersection) to obtain a graph taking into account the distance and the dangerousness of this intersection.
To do so, we have developed two approaches:

*A **static hour-based method** to see the influence of daytime on the number of accidents
*A **predictive method** to evaluate the upcoming month number of accidents; it is a robust method that takes into account changes in the number of accidents

Futher detail please refer: 

## Experiment and result:

Based on the statistical data and forecast, we are able to give real-time route suggestion on given starting point and destination.

Demo:

![6242routedemo-ezgif com-video-to-gif-converter](https://github.com/ludie/SafeRouteSuggestion/assets/52432788/eafe9b74-1a02-4b55-9f55-0f1c6192d857)

Futher detail please refer: 

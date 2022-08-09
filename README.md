# Highway to Hell : A Project on Road Accident Analysis in New York City
## Introduction
New York City ranks 4th in the United States for the worst traffic. A 2019 CDC report categorically stated that road accidents were the 3rd leading cause of death in the United States. New York is infamous for its traffic and disproportionately high motor accidents. These statistics propel the need for the analysis of motor accidents in order to mitigate this much-avoidable crisis.

This prompted us to take up the project of analyzing motor accidents in NYC. Our goal is to understand the story behind this data and observe trends, which will allow us to come up with suggestions that could lead to reductions in the number of fatalities.

We wish to :

* Decipher if a correlation between the time and frequency of accidents? If yes, then what are the factors leading up to more accidents at a certain time of the day than others. Through this analysis, we wish to understand how the accidents vary over the course of a day, and whether a similar trend is observed throughout the dataset.

* Understand the proportion of accidents that end up injuring the victims based on the time of the day. (Day-partition : morning, afternoon, evening and night). Using this, we get a better idea of the exact percentage of accidents occuring in different day partitions, which builds on the first analysis.

* Observe the boroughs over the span of 8 months and analyse if some boroughs of NYC are more accident-prone than their counterparts and what the administration can probably do to decongest the boroughs. We analyze the boroughs and plot the accidents in respective boroughs on a map which allows us to see which ones have the highest number of accidents.

* Discern the leading cause of accidents in the boroughs with most number of accidents (top-3). Could there be a strategy implemented to reduce the occurrence of these accidents? We want to find out the borough that has the highest injuries/fatalities to have some counter-measures in place, like increased response time, more readiness in the health services or more regulation of traffic to prevent accidents in these boroughs.

* Understanding if certain types of vehicles were more involved in accidents than the others and hypothesizing the results of the analysis with automotive safety. This will allow us to dive deep into the vehicles causing the most accidents and will enable us to make changes based on whether the privately owned cars or the public/commercial cars cause more accidents.

Through the above questions, we are attempting to make a story which starts off with finding the total accidents occuring throughout the city and giving us an idea of the most accident prone time of the day. Based on this, we attempt to find out the most accident-prone boroughs, and try to correlate this to their population/area and find if the data supports the hypothesis. Once we have the most accident-prone boroughs, we will dive deep into the actual causes of accidents for each of them to try and come up with a solution to mitigate accidents. We also aim to find the exact type of vehicles that are involved so we can take action accordingly based on their type.

## Dataset Description
The dataset was obtained through Kaggle named "NYC Traffic Accidents", posted by mysar ahmad bhat. It is a collection of motor vehicle collisions reported by the New York City Police Department. The dataset has around 75,000 rows and 29 columns, and contains information such as the location of accidents, the boroughs, crash date, time, the cause of accidents, the vehicles involved in the accidents and the number of fatalities (injured and killed). The link to the dataset is as follows: https://www.kaggle.com/mysarahmadbhat/nyc-traffic-accidents

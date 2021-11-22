# Surfs Up
## Analyzing weather data in jupyter notebook and making an app

## Overview of analysis
The purpose of our analysis is to see temperature statistics for June and December to see if running a surf shop is sustainable year around. The way we get the temperature data is by running two seperate queries, one being for June and the other being December. Once we run our queries we store the temperatures in a list then convert them to a dataframe. Once our dataframe is created we are able to get our summary statistics by using the .describe() method. Here is what we found:

## Results
In June we had a total count of 1700, mean of 74.9, min of 64.0 and max of 85.0

<img width="303" alt="Screen Shot 2021-11-21 at 9 33 08 PM" src="https://user-images.githubusercontent.com/90435301/142806415-21fc1a69-c5f4-420c-a86c-28556060e5d0.png">

In December we had a total count of 1517, mean of 71.0, min of 56.0 and max of 83.0

<img width="271" alt="Screen Shot 2021-11-21 at 9 33 29 PM" src="https://user-images.githubusercontent.com/90435301/142806600-d03fa21f-f930-42a2-9bf1-828b63144ae7.png">

Standard deviation is 3.25 in June and 3.75 -- making a .5 difference in the two different seasons

## Summary
The data we analyzed shows us the temperatures, however, since there are other attributes that contribute to to weather such as precipitation and humidity, we can run additional queries to gain a deeper understanding and provide a more well rounded and relevant analysis. With the addition of the new queries, we can decide how we would like to build the shop and what areas would make this a more prominent location for visitors to come.

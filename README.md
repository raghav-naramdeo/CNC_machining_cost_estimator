# CNC_machining_cost_extimator
This model will scrape the website and get data related to cnc machining and then as per your BOM you can modify it.

First of all we scrape the MFG.com (https://www.mfg.com/)
you can choose otherwise

Aim is to get material they work with, size they work with, complixity they handel, location.

Then we create a data frame to train the algorithm

Right now we have used random forest regressor to train

NOTE:
At point the price data and complixity are manually added, but ot actually deply we need actual data

Problems:
one is data is insufficient and almost incorrect

Future addition:
Prediction based on location using longitude and lattitude
prediction on prices closer to yout budget
prediction based on drawings and other params.

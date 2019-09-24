# 911-Capstone-
For this capstone project we will be analyzing some 911 call data. The data contains the following fields:
lat : String variable, Latitude.
lng: String variable, Longitude.
desc: String variable, Description of the Emergency Call.
zip: String variable, Zipcode.
title: String variable, Title.
timeStamp: String variable, YYYY-MM-DD HH:MM:SS.
twp: String variable, Township.
addr: String variable, Address.
e: String variable, Dummy variable (always 1).
This dataset records the time, location, priority, and reason for calls to 911 in the city .
The study discussed in this article reviewing 911 calls found that that incidents of police violence lead to large drops in the number of 911 calls.
we uses numpy and pandas and Import visualization libraries and set %matplotlib inline
we can use seaborn's lmplot() to create a linear fit on the number of calls per month.
we create heatmaps with seaborn and our data.

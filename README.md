# Overview

We are trying to help our client understand information about temperature & precipitation trends for the months of June and December (the driest and wettest months in Hawaii, respectively) in Oahu. This information will help the client make a decision on whether or not to invest in a surf shop that serves ice cream. 

# Results

First, the summary statistics for the temperatures for the month of June were collected. Information in the database were from the years 2010-2017. All temperatures for every day in the month of June for those years were put into a DataFrame. 

![image](https://user-images.githubusercontent.com/103383489/182007725-3b1d5577-03b9-4830-9132-fb4b6694f518.png)

The summary statistics from that DataFrame were as follows.

![image](https://user-images.githubusercontent.com/103383489/182007748-de415ff8-0813-4490-bd60-4b8950b6eb87.png)

* First Finding: The mean temperature for the month of June in Oahu is 74.94 Degrees F with a maximum degrees of 85. 

Second, the summary statistics for the temperatures for the month of December were collected. Information in the database were from the years 2010-2016. All temperatures for every day in the month of December for those years were put into a DataFrame. 

![image](https://user-images.githubusercontent.com/103383489/182007812-c575d9a2-27d3-4bce-8b9e-df8f3b832413.png)

The summary statistics from that DataFrame were as follows.

![image](https://user-images.githubusercontent.com/103383489/182007824-98b04594-66a1-4e0b-8f9d-420dae2792ad.png)

* Second Finding: The mean temperature for the month of December in Oahu is 71.04 Degrees F with a minimum degrees of 56. 

## Comparing June and December's Temperatures

* Third Finding: The average temperatures for June & December in Oahu only have a difference of around 4 degrees, indicating a low temperature variance between the warmer summer months and the colder winter months. The coldest it gets in December on average is 56 Degrees F, while the hottest it gets in June is 85 degrees. Pretty mild weather year round!

---
# Summary & Additional Queries

While finding out Oahu's temperatures in December and June are useful as we now know that there is little variance between seasons (according to this older dataset, anyway), it might also be useful to see how rainy the area gets. 

Two additional queries were run to determine precipitation in June & December using the same SQLite weatherstation data as in our temperature queries. 

* June Precipitation Queries

![image](https://user-images.githubusercontent.com/103383489/182008141-e3479c05-3f75-4183-9f2f-d3188a78795f.png)

![image](https://user-images.githubusercontent.com/103383489/182008151-45832d6f-4b28-4e5b-a809-5143ea9cade4.png)

* June Precipitation Visualization using MatPlotLib

![image](https://user-images.githubusercontent.com/103383489/182008187-78245824-559f-4ac5-afbf-2ad27af62030.png)

* December Precipitation Queries

![image](https://user-images.githubusercontent.com/103383489/182008123-b6d482d0-557b-4db8-b330-9cac63abadcc.png)

![image](https://user-images.githubusercontent.com/103383489/182008129-1dd28186-4f75-4dc2-aad3-2514f93c4d3d.png)

* December Precipitation Visualization using MatPlotLib

![image](https://user-images.githubusercontent.com/103383489/182008203-c6d72d4f-25e1-4a6a-b9d8-5905ff37c9fe.png)

* Additional Findings: The mean precipitation for the month of June in Oahu is 0.136 inches with a maximum of 4.43 inches/day in six years. The mean precipitation for the month of December in Oahu is 0.217 inches with a maximum of 6.42 inches/day in six years. According to the visualizations, it appears that 2010 & 2011 were Oahu's most rainy years recently. 

* Just like with temperatures, the variance in precipitation between the months of June and December are not significant, indicating a surf and ice cream shop could be a worthwhile investment on the shores of beautiful Oahu. 








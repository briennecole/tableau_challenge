# citibike Data Analysis Challenge (utilizing Tableau)

#### By: Brienne Cole
----------------------------------------------------------
### Introduction
#### Task and Objectives:
As the new lead analyst for the New York Citi Bike Program, I am now responsible for overseeing the largest bike sharing program in the United States. In my new role, I will be expected to generate regular reports for city officials looking to publicize and improve the city program.

I will use this initial data story to track changes and find trends across 4 years of citibike data regarding the following questions/objectives:
- Which stations have the highest traffic and why? Has this changed over time, why and how can we use these trends to predict future trends?
- Who are our customers and where do we have opportunities to increase awareness and accessibility?
- Track peak riding times to assist with business operations planning

### Gathering the Data
https://s3.amazonaws.com/tripdata/index.html
- 201707-citibike-tripdata.csv
- 201807-citibike-tripdata.csv
- 201907-citibike-tripdata.csv
- 202007-citibike-tripdata.csv

### Analysis
#### Link to Tableau Public Workbook
https://public.tableau.com/profile/brienne.cole#!/vizhome/NYCCitiBikeTripData/citibikeUserStory

The first very curious thing I noticed was that after being the most popular start AND end station 2017-2019, Pershing Square also took the largest hit with the Covid Pandemic in 2020. Why? After closer examination, this station is at Grand Central Terminal and therefore, highly sensitive to commuting and potentially tourism traffic. With more time I would like to take a closer look at what occupies the surrounding blocks around each of our top start and end locations.


![Screen Shot 2021-05-22 at 1 32 00 PM (2)](https://user-images.githubusercontent.com/75045133/119240117-a5beb680-bb02-11eb-972a-78127d148cbd.png)


There is considerably less traffic in the areas outside of Manhattan. Is this just because of population concentration or is there an opportunity to increase awareness and/or accessibility? Would like to dive deeper into population demographics of the various neighborhoods to learn more.


![Screen Shot 2021-05-22 at 1 32 37 PM (2)](https://user-images.githubusercontent.com/75045133/119240139-c4bd4880-bb02-11eb-996a-5ebc8196912e.png)


As expected, peak usage times are M-F during commuting hours and on 10am-7pm on Weekends. An interesting phenomena I did not expect to see was that the average trip duration is highest between the hours of 12am and 5am. With more time, I would like to look further at the routes typically taken during those hours. Is it because certain industries travel further to get to work in the city, because customers are more tired at that time or something else?

Also interesting to note, women ride longer on average than men. Are they riding further or just more leisurly riders?


![Screen Shot 2021-05-22 at 1 32 51 PM (2)](https://user-images.githubusercontent.com/75045133/119240158-de5e9000-bb02-11eb-9188-f1a172ff0565.png)



![Screen Shot 2021-05-22 at 1 32 58 PM (2)](https://user-images.githubusercontent.com/75045133/119240185-f46c5080-bb02-11eb-9918-0c64ed8be55e.png)

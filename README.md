# surfs-up
This project creates an app to track weather data in Oahu, Hawaii. My client wants to use this data to forecast the success of a surfing and food service business in this location. 

## Results ##
I used Python, Pandas, and SQLAlchemy to pull data from an SQLite file that captured temperature and other weather data from Oahu. I generated summary statistics from this data to provide my client summer weather data from June and winter weather data from December. 
 
(June)
<img width="154" alt="Screen Shot 2022-02-15 at 7 20 41 PM" src="https://user-images.githubusercontent.com/95657458/154172335-99462dc4-c7c7-4661-962d-907d3fa0c99b.png">

(December)
<img width="141" alt="Screen Shot 2022-02-15 at 7 21 12 PM" src="https://user-images.githubusercontent.com/95657458/154172382-4866f679-796a-491d-8b85-34bfb482bc89.png">

There are three major differences between these statistics from June and December.
* The minimum temperature is over 10 degrees lower in December than in June.
* The average temperature is slightly higher in June than in December, but not by much. 
* The total counts of captured observations is significantly higher in June than in December, which may have some effect on the accuracy of data captured in December. 

## Summary ##
Overall, the temperatures in June and December are characteristically warm, considering the prospective business location in Hawaii. With that said, further data may further illuminate whether this business is viable for the location. One additional query that would add more information would measure more recent weather data from the last 5 years. Changes to weather patterns shaped by global warming may provide other indicators. Another additional query to could measure the height of tides in different Oahu locations throughout the year, as any surfer would consider the tides before they decide whether or not to surf that day. Oahu is a popular surfing destination, but offers options of several beaches. Knowing which beach provides ideal tides to the target customer would allow my client to select the business location more successfully.

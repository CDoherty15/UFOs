# UFOs
Module 11: UFO sightings with JavaScript

## Overview
We are helping Dana build a webpage that displays a UFO sighting data. We took a JSON dataset that contains recorded sightings and displayed it as a table. We scripted an HTML script to display the information on a webpage. Since we used a webpage, we were able to add a filter for the sighting data. Dana likes her new webpage source and to help with more in-depth analysis, we added more filters for city, state, country and shape. 
## Results
Here we can see the results and steps how to use the filters:
![mod16_UFO_home](https://user-images.githubusercontent.com/79118630/120908634-31bffa80-c63a-11eb-88ed-11e010772fb4.png)
- Here we can see the whole webpage, with a description about scientists talking about if we are alone or not in the universe. If you look towards the bottom of the page, we can see the different filter entry fields to the left and the data table to the right. As shown in the entry fields, there are examples of how to enter the filters. Lets go through a quick example on how to use the page
#### UFO sighting filters
- Originally, we started with filtering the date, and that is what we will start with when looking for more in-depth analysis, lets enter "1/1/2010"
![mod16_UFO_date](https://user-images.githubusercontent.com/79118630/120908705-ece89380-c63a-11eb-8025-bf482028a6d7.png)
- Now, the table has been drastically changed and much easier to read. There were a bunch of sitings recorded on this day, so much that the screenshot does not contain all of the sightings. We could enter a city if we choose too, but this will take away a lot of the choices. We can see that California had a lot of sightings this day. So for now, lets see how many were in California this day by entering "ca". 
![mod16_UFO_date_state](https://user-images.githubusercontent.com/79118630/120908734-58326580-c63b-11eb-8809-05bade008596.png)
- There were a good amount in California, we have some other options to go from here. If we wanted to we could filter by city for more of a specific location. We don't need to worry about the country field since it looks like all the data was entered correctly and "us" is entered in every row. For this example, lets look at "light" for the shape of the sightings. 
![mod16_UFO_date_state_shape](https://user-images.githubusercontent.com/79118630/120908780-0e964a80-c63c-11eb-9446-c3c08148d515.png)
- With just entering 3 filters entries, we were able to take the giant table and narrow it down to under 10 rows of UFO sightings. 
- With our 3 filters, we can see that there were 7 different light UFO sightings in California on January 1, 2010. What's even more unique, is that each one was in a different city. 

## Summary
#### Drawback
- Using a JSON file for the dataset requires Dana or whoever helps udpdate the data manually. This requires the programmer to manually look up and check news sources for UFO sightings and updating the JSON file. Then refreshing the HTML file and checking to make sure the table is updated correctly without affecting other parts of the page. 
#### Recommendations
- Adding a "News" section could help interest viewers. The table displayed only adds limited information, displaying news articles and/or links might encourage users to learn more about UFOs. Thus leading to more users reading and keeping up with Dana's work. 
- Setting up an UFO API to find the necessary information for the displayed table will help with updating the information more frequently and more accurately. An example is that this data only contains information from 2010. With a small dataset it can be easier to make small adjustments because errors will be easier to spot. However, this is over 10 years old, users might like the data, but it is a little outdated. Having current and frequently updated data will interest and attract more users. 

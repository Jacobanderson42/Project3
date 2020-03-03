# Project3
Project 3 for B ME 450 \
GitHub repository link: https://github.com/Jacobanderson42/Project3 \
GitHub code link: https://github.com/Jacobanderson42/Project3/blob/master/Project_3.ipynb

# Problem Statement
This project is looking to analyze seismic data taken by the U.S. Geological Survey. This project looks to be able to analyze the 
magnitude of earthquakes in the NE Pacific Ocean based on date as well as location and boundary type. This type of analysis can be used 
to find the correlation between boundary type and magnitude of earthquake as well as locating seismic activity that is present during a 
certain time period.

# Background/Solution/Results
Seismometers measure small variation in ground movement that is used to detect earthquakes. By comparing seismometer data from different 
locations, the origin of the earthquake and the magnitude can be found. The U.S. Geological Survey provides this data on their website and 
can be downloaded for any area and range of magnitudes. This data is provided as a latitude and longitude coordinate of where the 
earthquake originated from as well as the magnitude and time of the earthquake. This data can be used to locate and compare fault lines as 
well as locate certain seismic activity. To analyze this data a python code was written that downloads the data and then plots it on 
different graphs to analyze different information.

The function takes in a start and end time as well as a minimum and maximum latitude and longitude for the location of interest. The 
function then takes this information and requests the data from the USGS website for the given location and time. This data is then   
separated into latitude, longitude, time, and magnitude. A plot is then created of the magnitude versus date and then a plot is created 
of each earthquake at its geographic location where the marker is a circle with a radius that is proportional to the magnitude.

A set of plots is created for the total data from the beginning of 2010 to the current date. Then the transform and divergent boundaries 
are narrowed in on and plots are created for each of the two areas. An overall plot is then created for the month of April to look at 
the seismic activity around the Juan De Fuca plate. All of these graphs can be seen below.

# Graph for the Juan De Fuca Plate from 2010 to Now
![](https://github.com/Jacobanderson42/Project3/blob/master/Images/Date%20for%202010%20to%20Current.png)
![](https://github.com/Jacobanderson42/Project3/blob/master/Images/Location%20for%202010%20to%20Current.png)

# Graph for the Juan De Fuca Plate in April 2015
![](https://github.com/Jacobanderson42/Project3/blob/master/Images/Date%20for%20April.png)
![](https://github.com/Jacobanderson42/Project3/blob/master/Images/Location%20for%20April.png)

# Graphs for the Transform Boundary
![](https://github.com/Jacobanderson42/Project3/blob/master/Images/Date%20for%20Transform.png)
![](https://github.com/Jacobanderson42/Project3/blob/master/Images/Location%20for%20Transform.png)

# Graphs for the Divergent Boundary
![](https://github.com/Jacobanderson42/Project3/blob/master/Images/Date%20for%20Divergent.png)
![](https://github.com/Jacobanderson42/Project3/blob/master/Images/Location%20for%20Divergent.png)

# Conclusions
It can be seen from the first set of plots, that cover the whole Juan De Fuca plate, that most of the earthquakes happen along the plate 
boundaries. This happens because this is where the plates meet up. The plates that meet at these boundaries slip past each other and 
this is what causes earthquakes to happen. The magnitude of the earthquakes in this area range from 2.5 to 6.8 with an average 
magnitude of about 3.18.

Looking at the plot for April 2015, there are two clumps of earthquakes in this area. The first is north of Vancouver Island, close to 
the Gulf of Alaska. The other cluster of earthquakes is located west of the mouth of the Columbia River. This is also the location of 
the Axial Seamount volcano, which caused around 8,000 earthquakes on April 24th. 

Comparing the plots of the transform and divergent boundaries it appears that there is no difference between the earthquakes for the two 
different types. For the Transform boundary, the range of magnitudes is from 2.5 to 6.3 with an average of 3.53. For the Divergent 
boundary, the magnitudes range from 2.5 to 5.9 with an average of 3.66. There is a slightly higher maximum for the transform boundary 
and a slightly higher average for the divergent boundaries however there doesn't seem to be a noticeable trend in the magnitudes for the 
two different types of boundaries.

# References
https://earthquake.usgs.gov/earthquakes/map/ \
https://www.oregonlive.com/pacific-northwest-news/2015/04/a_volcano_may_be_erupting_off.html?fbclid=IwAR1eJeTpRu9wbXUaqgLgfx27RkC2iuIh9XLu1jr8NgMlq0ldYBmQSXfLvp8

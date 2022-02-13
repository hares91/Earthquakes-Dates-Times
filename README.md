# Earthquakes-Dates-Times
Working with dates, times and time zones
<br>
One of the challenges for a data analyst is dealing with date and time. Fortunately, doing that in Python seems to be an easy task.

I found a dataset of significant earthquakes happened between 1965 and 2016. In order to do this exercise, I had to assume that the dates and times reported in the dataset are local dates and times, because usually earthquakes are reported in universal time UCT.

The challenges here were:
<br>
•	Identify the time zone of the earthquake considering the reported longitude and latitude. <br>
•	Convert the date and time from string to datetime. <br>
•	Make sure the time zones reported in the data set match the time zones included in the pytz module. <br>
•	Identify how many hours of difference there are between the local time and the universal time UTC. <br>

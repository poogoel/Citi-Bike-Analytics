
# Citi-Bike-Analytics

![alt text](https://d21xlh2maitm24.cloudfront.net/nyc/Annual-Membership-Image.png?mtime=20190331121650)

<p align="center">
  <a href="#data-source">Data Source</a> •
  <a href="#findings">Findings</a> •
  <a href="#technology-Used">Technology Used</a>
</p>

An analysis of the New York Citi Bike Program, in who are responsible for overseeing the largest bike sharing program for 200,000+ data points in the United States
 in order to generate business insights in terms of visulize the peak time in both summer and winter period and the top start location in New York City and Jersey City, New Jersey
 
* Click [here](https://public.tableau.com/profile/poonam.goel#!/vizhome/CitiBikeDataAnalysis_15762113466980/CitiBikeDataAnalysis?publish=yes) to view complted dashboard

## Data Source
![alt text](https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/citi-bike-station-bikes.jpg?raw=true)

This [Citi Bike Data](https://www.citibikenyc.com/system-data) has been processed to remove trips that are taken by staff as they service and inspect the system and any trips that were below 60 seconds in length 
(potentially false starts or users trying to re-dock a bike to ensure it's secure).

<table class="hide-while-loading table table-striped">
<tbody id="tbody-content">
<thead>
<tr>
<th>Name</th>
<th>Date Modified</th>
<th>Size</th>
<th>Type</th>
</tr>
</thead>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201901-citibike-tripdata.csv.zip">JC-201901-citibike-tripdata.csv.zip</a></td>
<td>Feb 11th 2019, 08:43:41 am</td>
<td>506 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201902-citibike-tripdata.csv.zip">JC-201902-citibike-tripdata.csv.zip</a></td>
<td>Mar 4th 2019, 10:21:48 am</td>
<td>480 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201903-citibike-tripdata.csv.zip">JC-201903-citibike-tripdata.csv.zip</a></td>
<td>Apr 15th 2019, 01:34:52 pm</td>
<td>609 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201904-citibike-tripdata.csv.zip">JC-201904-citibike-tripdata.csv.zip</a></td>
<td>May 6th 2019, 02:07:33 pm</td>
<td>847 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201905-citibike-tripdata.csv.zip">JC-201905-citibike-tripdata.csv.zip</a></td>
<td>Jun 11th 2019, 02:37:55 pm</td>
<td>910 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201906-citibike-tripdata.csv.zip">JC-201906-citibike-tripdata.csv.zip</a></td>
<td>Jul 15th 2019, 12:42:09 pm</td>
<td>1.02 MB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201907-citibike-tripdata.csv.zip">JC-201907-citibike-tripdata.csv.zip</a></td>
<td>Aug 5th 2019, 04:34:01 pm</td>
<td>1.13 MB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201908%20citibike-tripdata.csv.zip">JC-201908 citibike-tripdata.csv.zip</a></td>
<td>Sep 18th 2019, 03:33:15 pm</td>
<td>1.26 MB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201909-citibike-tripdata.csv.zip">JC-201909-citibike-tripdata.csv.zip</a></td>
<td>Oct 11th 2019, 02:42:04 pm</td>
<td>1.27 MB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201910-citibike-tripdata.csv.zip">JC-201910-citibike-tripdata.csv.zip</a></td>
<td>Nov 5th 2019, 04:10:56 pm</td>
<td>1.09 MB</td>
<td>ZIP file</td>
</tr>
</tbody>
</table>

* <b>Limitation </b>: It appears that male are the dominant customer at all time.

![alt text](https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/Ridership%20by%20month.PNG?raw=true)


## Findings 


### (1) The current major citi bike riders fall into young male group between 18 -20 but number of femal riders is increasing over time.

![alt text](https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/trip%20duration%20by%20age.PNG?raw=true) 

### (2) The 1st and 2nd peak hours during a day would usually be 7-8 AM and 5-6 PM season-regardless 

![alt text](https://raw.githubusercontent.com/poogoel/Citi-Bike-Analytics/master/images/Popular%20times%20of%20ridership.PNG)

### (3) When the temperature is cold in winter, people tend not to ride as well because of the lack of comfort individuals face when riding in low temperatures. 

![alt text](https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/Ridership%20by%20month.PNG?raw=true)

## Map visualization 

![alt text](https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/top_location.PNG?raw=true)
![alt text](https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/top_location2.PNG?raw=true)

## Technology Used

<img src="https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/Python_logo.jpg?raw=true" width="240" height="50"/>

<img src="https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/Tableau_Logo.png?raw=true" width="240" height="60"/>


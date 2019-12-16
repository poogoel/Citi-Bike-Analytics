
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
![alt text](https://github.com/poogoel/Citi-Bike-Analytics/blob/master/images/citibikedata.png)

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
<td>Apr 6th 2019, 02:01:43 pm</td>
<td>255 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201902-citibike-tripdata.csv.zip">JC-201902-citibike-tripdata.csv.zip</a></td>
<td>Apr 6th 2019, 02:01:44 pm</td>
<td>275 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201903-citibike-tripdata.csv.zip">JC-201903-citibike-tripdata.csv.zip</a></td>
<td>Apr 6th 2019, 02:01:44 pm</td>
<td>241 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201904-citibike-tripdata.csv.zip">JC-201904-citibike-tripdata.csv.zip</a></td>
<td>Aug 1st 2019, 09:20:54 am</td>
<td>432 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201905-citibike-tripdata.csv.zip">JC-201905-citibike-tripdata.csv.zip</a></td>
<td>Aug 1st 2019, 09:20:55 am</td>
<td>529 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201906-citibike-tripdata.csv.zip">JC-201906-citibike-tripdata.csv.zip</a></td>
<td>Aug 1st 2019, 09:20:56 am</td>
<td>647 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201907-citibike-tripdata.csv.zip">JC-201907-citibike-tripdata.csv.zip</a></td>
<td>Aug 1st 2019, 09:20:57 am</td>
<td>676 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201908%20citibike-tripdata.csv.zip">JC-201908 citibike-tripdata.csv.zip</a></td>
<td>Oct 3rd 2019, 08:52:49 am</td>
<td>711 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201909-citibike-tripdata.csv.zip">JC-201909-citibike-tripdata.csv.zip</a></td>
<td>Oct 3rd 2019, 08:52:49 am</td>
<td>667 KB</td>
<td>ZIP file</td>
</tr>
<tr>
<td>&nbsp;<a href="https://s3.amazonaws.com/tripdata/JC-201910-citibike-tripdata.csv.zip">JC-201910-citibike-tripdata.csv.zip</a></td>
<td>Jan 31st 2018, 01:15:18 pm</td>
<td>703 KB</td>
<td>ZIP file</td>
</tr>
</tbody>
</table>

* Limitation
It appears that male are the dominant customer at all time.

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


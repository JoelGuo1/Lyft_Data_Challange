# Lyft_Data_Challange
Data Challenge held by Lyft.
You'll find three CSV files attached with the following data:
<h2>data/driver_ids.csv</h2>
<ul>
  <li>driver_id:Unique identifier for a driver</li>
  <li>driver_onboard_date:Date on which driver was on-boarded</li>
</ul>
<h2>data/ride_ids.csv</h2>
<ul>
  <li>driver_id:Unique identifier for a driver</li>
  <li>ride_id:Unique identifier for a ride that was completed by the driver</li>
  <li>ride_distance:Ride distance in meters</li>
  <li>ride_duration:Ride duration in seconds</li>
  <li>ride_prime_time:Prime Time applied on the ride</li>
</ul>
<h2>data/ride_timestamps.csv</h2>
<ul>
  <li>ride_id:Unique identifier for a ride</li>
  <li>event:event describes the type of event (see below)</li>
  <li>timestamp:Time of event</li>
</ul>
You can assume that:
<ul>
  <li>All rides in the data set occurred in San Francisco</li>
  <li>All timestamps in the data set are in UTC</li>
</ul>
After exploring and analyzing the data, please:<br>
1. Recommend a Driver's Lifetime Value (i.e., the value of a driver to Lyft over the entire projected lifetime of a driver).<br>
2. Please answer the following questions:<br>
<ol type="a">
  <li>What are the main factors that affect a driver's lifetime value?</li>
  <li>What is the average projected lifetime of a driver? That is, once a driver is onboarded, how long do they typically continue driving with Lyft?</li>
  <li>Do all drivers act alike? Are there specific segments of drivers that generate more value for Lyft than the average driver?</li>
  <li>d. What actionable recommendations are there for the business?</li>
</ol>
3. Prepare and submit a writeup of your findings for consumption by a cross-functional audience.<br>
Here is an overview of the event types:<br>
requested_at&emsp;&emsp;&emsp;&emsp;passenger requested a ride<br>
accepted_at&emsp;&emsp;&emsp;&emsp;driver accepted a passenger request<br>
arrived_at&emsp;&emsp;&emsp;&emsp;driver arrived at pickup point<br>
picked_up_at&emsp;&emsp;&emsp;&emsp;driver picked up the passenger<br>
dropped_off_at&emsp;&emsp;&emsp;&emsp;driver dropped off a passenger at destination<br>
You can make the following assumptions about the Lyft rate card:<br>
Base Fare&emsp;&emsp;&emsp;&emsp;$2.00<br>
Cost per Mile&emsp;&emsp;&emsp;&emsp;$1.15<br>
Cost per Minute&emsp;&emsp;&emsp;&emsp;$0.22<br>
Service Fee&emsp;&emsp;&emsp;&emsp;$1.75<br>
Minimum Fare&emsp;&emsp;&emsp;&emsp;$5.00<br>
Maximum Fare&emsp;&emsp;&emsp;&emsp;$400.00<br>

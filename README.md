# Lyft_Data_Challange
Data Challenge held by Lyft.
You'll find three CSV files attached with the following data:
<h2>data/driver_ids.csv</h2>
<ul>
  <li>driver_id Unique identifier for a driver</li>
</ul>
driver_onboard_date Date on which driver was on-boarded

data/ride_ids.csv
driver_id Unique identifier for a driver
ride_id Unique identifier for a ride that was completed by the driver
ride_distance Ride distance in meters
ride_duration Ride duration in seconds
ride_prime_time Prime Time applied on the ride
data/ride_timestamps.csv
ride_id Unique identifier for a ride
event event describes the type of event (see below)
timestamp Time of event
You can assume that:
● All rides in the data set occurred in San Francisco
● All timestamps in the data set are in UTC
After exploring and analyzing the data, please:
1. Recommend a Driver's Lifetime Value (i.e., the value of a driver to Lyft over the entire
projected lifetime of a driver).
2. Please answer the following questions:
a. What are the main factors that affect a driver's lifetime value?
b. What is the average projected lifetime of a driver? That is, once a driver is
onboarded, how long do they typically continue driving with Lyft?
c. Do all drivers act alike? Are there specific segments of drivers that generate more
value for Lyft than the average driver?
d. What actionable recommendations are there for the business?
3. Prepare and submit a writeup of your findings for consumption by a cross-functional
audience.
Here is an overview of the event types:
requested_at passenger requested a ride
accepted_at driver accepted a passenger request
arrived_at driver arrived at pickup point
picked_up_at driver picked up the passenger
dropped_off_at driver dropped off a passenger at destination
You can make the following assumptions about the Lyft rate card:
Base Fare $2.00
Cost per Mile $1.15
Cost per Minute $0.22
Service Fee $1.75
Minimum Fare $5.00
Maximum Fare $400.00
Submission instructions:
● Summarize your conclusions at the beginning of your writeup.
● Your writeup should be a PDF (max 5 pages) and labeled with the following naming
convention:
[Team Name]_[Writeup]_[First Student Initials]_[Second Student Initials].pdf;
Ex. “LyftDataChallengeTeam_Writeup_DF_HL.pdf”
● Your writeup and all of your working materials should then be saved together as a zip file
with the following naming convention:
[Team Name]_[First Student Initials]_[Second Student Initials].zip;
ex: “LyftDataChallengeTeam_DF_HL.zip”
● The max file size for your zip file is 10 MB (so please do not include the raw data CSVs).
● Keep in mind that we will be assessing the challenge based on its technical soundness
and depth, business applications and insights, and structure and organization.
● Our intention is for teams to spend no more than 8 hours on this prompt.
● The deadline to upload your submission is Sunday, September 15 11:59pm PDT . Late
entries will not be evaluated.
● If you have questions or technical difficulties, please contact us at
data-challenge@lyft.com

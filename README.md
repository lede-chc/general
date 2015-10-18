# Lede Hackathon

## Project Ideas:

### 1. Problem: Reduce Motor Vehicle Collisions
#### Potential Data Sets:
* [NYC Open Data on Motor Vehicle Collisions](https://data.cityofnewyork.us/Public-Safety/NYPD-Motor-Vehicle-Collisions/h9gi-nx95)
* [NYC Street Centerline Data](https://data.cityofnewyork.us/City-Government/NYC-Street-Centerline-CSCL-/exjm-f27b)
* [NYC Sidewalk Features](https://data.cityofnewyork.us/City-Government/Sidewalk-Features/vfx9-tbb6)

#### Questions to address:
* Where is it most dangerous (intersections, neighborhoods, zip codes)?
* When is it most dangerous (day of the week, time of day, weather conditions, etc.)?
* What are the most frequent contributing causes of accidents? 
* Do these answers vary in cases with injuries and fatalities?

#### What you need:
* An algorithm for predicting your target variable (which can vary, depending on how you frame the central question)
* Data for every NYC intersection (maybe)
* Feature data for every NYC intersection (maybe)

### 2. How Does Weather Influence Our Behaviour?
#### Datasets
* [NOAA - NCDC Climate Data Online Data Search](https://www.ncdc.noaa.gov/cdo-web/search?datasetid=GHCND)
	* Provides historical weather data for most US and Canadian cities, as well as some major cities overseas; can specify exact data wanted (precipitation, temperature, sunshine, etc.)
* [Yelp Dataset Challenge](https://www.yelp.com/dataset_challenge/dataset)
	* Reviews, tips, and check-ins from select cities. Reviews and tips have dates associated with them; each business has a city and coordinates associated with it as well
* [Million Music Tweets Dataset (MMTD)](www.cp.jku.at/datasets/MMTD/)
	* Detailed listening history (2011-11-09 to 2013-04-30) of Twitter users who tweeted their "now playing" songs through on Spotify. Includes location based on the Twitter profile

#### Questions to address:
* **Yelp**
	* Are reviews affected by the weather at all?
		* Number of reviews submitted, ratings given, length of reviews
		* Text analysis: Are people more likely use certain words depending on the weather?
* **Million Music Tweets Dataset (MMTD)**
	* Are certain songs/genres/(other musical characteristics) played more often or less often depending on the weather?
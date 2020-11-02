# World_Weather_Analysis
Mapping your vacation plan
---
---

## Goals & Overview
In this analysis, we use APIs to visually map a trip, taking into account preferred locale temperatures and hotel access.

### Deliverable1: Weather Database
An error occurred in Step 6, where we iterate through cities by their individual Open Weather Map webpages and pull data Latitude and longitude, Maximum temperature, Percent humidity, Percent cloudiness, Wind speed, and Weather description. However, there was in issue that prevents our city names list from connecting with its url, and none of the data came through. This effectively voided the rest of this analysis and the resulting CSV. 

### Deliverable2: Vacation Search
Vacation Search was largely successful, except that we needed information generated in the CSV from the prior deliverable. Resulting, a file with placeholder data was used for the analysis. 

That steps 6a-6f resulted in "Hotel not found... skipping." for every entry in concerning. However, we were able to generate a map of hotels.

### Deliverable3: Vacation Itinerary
In this step, we intended to plot a road trip, after selecting 4 cities on a roundtrip adventure. 
The issue here is with Step 7 "list indexing". If this had been done, the tuples should have flowed into the figure at the next step to make a connected route. Fortunately, we were able to plug in the specific locations and show their information boxes. 

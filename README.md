# UFO Sightings - The Truth Is Out There!!!
![UFO pic](https://user-images.githubusercontent.com/89044350/140238694-04bb1efc-de52-42cf-8c7e-8942d944584f.PNG)

## Overview of Project
Create a website containing a table built using JavaScript where users can search historical UFO sighting data, utilizing multiple filters. Using Bootstrap and HTML/CSS, we were able to customize the look of the website as shown below: 

![website](https://user-images.githubusercontent.com/89044350/140239576-035d46a5-2991-4dc9-be1e-0b26ce50a91a.JPG)

## How It Works
Users are able to search utilitizing 5 filters:
 1. Date
 2. City
 3. State
 4. Country
 5. Shape
 
![filters](https://user-images.githubusercontent.com/89044350/140239723-edd4b6ca-e98e-40f9-9025-d3072b8dc913.JPG)

Entering data into a search field will yield all results containing data specific to what is entered into the search field.  Example below:

![filter result](https://user-images.githubusercontent.com/89044350/140240034-cb7379e9-6094-46d6-bf6e-2a81ce68cd91.JPG)

## Summary
### Drawbacks:
In order to retrieve data, the user must already know specific data pertaining to the sightings.  For example, there is no option to search a "date range", you must enter a specific date.  This would create a lot of work if someone was trying to determine if there is a time of year that provides more UFO sightings as compared to different time of year. The search criteria is also case sensitive.  The filter data must be typed exactly as it is in the dataset, or no data will be returned on a search. Lastly, the term "light" is used as a shape description, which is an odd adjective to describe the shape of an object.

### Recommendations For Further Development:
1. Add a date range option to allow the user to explore sightings during different times of year, instead of one specific day
2. Customize the filtering to be less strict on case sensitivity.  Allow users to type "San Diego", instead of "san diego".  Also, if a user accidentally places a "space" at the end of their search criteria, the search will yield zero results.  This needs to be fixed.

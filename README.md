# 11_UFO_JavaScript
Module 11 UFO Sightings with JavaScript

## Overview of Project: 

In this module we learned how to work with JavaScript to build a table to organize UFO data stored in a JavaScript array. We created filters to make this table fully dynamic, meaning that it will react to user input, and then put the table into an HTML file with visualizations that users can interact with

We were looking at some UFO data our client, Dana wished to put into a webpage.  The webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, we added table filters for the city, state, country, and shape.


## Results: 

The website we were able to create has information about UFO sightings including data about the Date of the sighting, location information (city, state, and country) and some information about the sighting itself (shape, duration and comments).  The data is shown in a table
### UFO Sightings site with data table.

![Site before filtering - all data viewable](/Resources/site_unfiltered.png)


To make the data more usable for those interested in UFO sightings, we created filters to all the users to interact with the data.  In the example below, the table is filtered on both "State" and "Shape"

### UFO Sightings filtered for state of California and "light" shape

![Site with filters - filtered by state and shape](/Resources/site_filtered.png)


## Summary: In a summary statement, describe one drawback of this new design and two recommendations for further development.

### Drawback to current design
One drawback to the current design is that it can be confusing to understand how to clear the filters.  All of the filters can be cleared by either refreshing the page, or deleting data from each field, however, it may be beneficial to include a "clear filters" button


### Recommendations for further development 
In order to enhance the design of the "UFO Sightings" site further development could include
1. adding a button to `clear filters`
2. Addition of filter for `duration` . This would entail some cleaning of the data as it is currently a free text field with multiple ways of showing the data (`10 min` vs `6 minutes`) and errors in spelling, but if this was to be cleaned up, it could be useful
3. Currently the `shape` parameter is a confusing. In addition to clean up of the data to group together things like `circle` and `sphere` , it could be useful to have a dropdown for this filter to select choices.

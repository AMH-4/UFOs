# **UFOs**
*Use JavaScript, HTML, and CSS to create a custome webpage that showcases UFO sighting data.*


## Overview of Project:

#### *Purpose:*
This project allows users to interact with the webpage and discover recorded data on UFO sightings. Additionally, the creatation of this webpage showcases the dynamic realtionship between the three coding languages, JavaScript, HTML, and CSS, used to build this site. 


## Results 

#### *How To Search:*
The layout of this webpage is simple, yet aestheticly pleasing for users to begin searching and filtering the UFO sighting data. Once the webpage is active, a quick scroll through the page will allow for the usere to gain an top-level understanding of the project and the type of data that is filterable. The data table showcases all of the UFO sighting data ordered in chronological date order. 

While, manually searching through the table data is possible, it is not optimal. The "Filter Search" table on the left side of the webpage allows users to filter the table data utilizing five available filters: date, city, state, country, and/or shape.

![UFO_index_landing page_overview](UFO_index_landingpage.png)

Users may filter the UFO sighting data using one or multiple filter options. Once a filterable search is entered into the search boxes and the user click the "Enter" or "Return" button on their keyboard, the filtered data will appear in the table data area. To search or filter the data with different paramenters, clear the filter text box and change the search paramaters. Then click "Enter" or "Return" to display the new filtered data. 

![UFO_data_onefilter](UFO_filter_date.png)

![UFO_data_threefilter](UFO_filterdata_date_state_shape.png)

Each time a user fileteres the data, an event is recorded to the consol. The following snipit of code fom the "app_chappenge.js" file attaches an event to listen for change to each filter. The image below is what can viewd in the consol on inspection of the website. 

``  
  d3.selectAll("input").on("change", updateFilters);
``

![UFO_consol_target_search_recorded](UFO_filterdata_colsole.png)

## Summary:

Although this webpage accomplishes its intended purpose, there is room for improvement. One major drawback is associated with the table data and filters. It is overwhelming to a user to discover the seemingly never ending list of table data. Additionally, a new user may not know what to search for in the filters section. Futher development for these issue would allow for a smoother webstite interaction for users. 

I recommend a drop down list of avaible filters for each of the filters. This would allow users to know the avaible dates, cities, states, countries, and shape they can search for in the table data. I also recommend "shrinking" the inital table data initially displayed to show only the first five to ten UFO sightings. A "see more" button would display additonal data in increements of five (or any desired length). These recomendations for futhere developemnt would allow for the webpage to be more user-friendly for useage and allow additional content to be created (and seen) below the table data if diesired.


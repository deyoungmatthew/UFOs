# UFOs

## **Overview**

The purpose of this project was to take a large set of data containing UFO sightings, including multiple data points for each sighting, and combine that data into a table into a website.  Multiple filters were added so that a user could input data into which would then automatically filter the the table to only display the information the user described with their filter selections.  

## **Results**

There are five filters available for the user to filter the table results.
* Date
* City
* State
* Country
* Shape

Any time a entry is made in any filter, once the user clicks to another filter or off the filter selection they just made, the table data will automatically update.

Below is a screen shot of an example where the following filters have been entered:
* Date: 1/1/2010
* State: ca
* Shape: light

![example](https://user-images.githubusercontent.com/78942457/117591350-209ad100-b102-11eb-9510-122547cceecf.PNG)

If all filters are cleared, then the table will display all data from the original file in the table.

## **Summary**

While the data and filters are extremely helpful for narrowing down the data, it might not be easy for someone who is unfimiliar with the data to know what items are in the data.  For example, if they wanted UFO sightings for anything after 1/13/2010, they wouldn't know that any information after that date isn't available.  One limitation is there is no way to know if the data they are filtering for is even present in the dataset.

Some additional recommendations for development include drop down lists for each filter and an interactive map. The drop down filter would allow someone to scroll through the available options and pick the item that was relevant to them.  This way they wouldn't have to guess if what they were looking for was included in the table.  The other recommendation is for an interactive map that would mark the locations of where the sightings occured.  This would allow someone to get an idea of the area of where the sighting took place and possibly offer an explanation for the incident to occur.

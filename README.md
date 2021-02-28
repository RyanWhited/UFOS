# UFO Sightings with Javascript 
![Albert-Anthony-UFO-Pic](https://github.com/RyanWhited/UFOS/blob/main/images/albert-antony-HWQXIYbs8PM-unsplash.jpg)

## Overview
It was requested to provide a more in-depth analysis of the UFO sightings web page by allowing users to filter for multiple criteria at the same time. In addition to the original date filter, I added table filters for the city, state, country, and shape.

## Results

I created a function updateFilters() what would save the element that was change with its value and ID to an array. This would then call the function filterTable() that would use a forEach loop to apply the filters to the table. Finally, the buildTable() function would be called to rebuild the table according to the new filters applied. 

Here are some examples of the filters in action...

  - In this particular instance I filtered the table to the state of Florida by typing "fl" in the state input box. The result would display all of the UFO sightings in this state. 

![Filter_by_State](https://github.com/RyanWhited/UFOS/blob/main/images/filter_by_state.jpg)

  - Perhaps you want to see all of the UFO sightings that had a circular shape. You could do so by typle "circle" in the shape input box!

![Filter_by_Shape](https://github.com/RyanWhited/UFOS/blob/main/images/filter_by_shape.jpg)

  - You're not just limited to one filter at a time. You can type in numerous inputs to be more specific with your search. For example, I wanted to see the UFO sightings in the state of California from January 2, 2010. I typed "ca" in the State input box and "1/2/2010" in the Date input box and two sightings were the result. 

![Multi-Filter](https://github.com/RyanWhited/UFOS/blob/main/images/multi_filter.jpg)

## Summary

While this website successfully does what it was designed to do, it's very easy to get no results. Why? There are two reasons:
  1. Not enough data. There are 111 data entries and having this many filters can result in little to no results. Solution would obviously be to gather more data if possible.
  2. The input boxes leave it up to the user to create the filter which can cause some issues. For example, there are 19,495 incorporated cities, towns and villages in the United States. There's plenty of opportunity for them to type an entry in the city input box and get no result. The solution would be to consider doing a drop down list instead of an input box. This way they can select an option that is available in the data table instead of blindly guessing. 

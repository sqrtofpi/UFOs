# UFO Sightings with JavaScript
Link to the HTML file: [index.html](https://github.com/sqrtofpi/UFOs/blob/16e348f831549b61cd1b1e97d0bbf70bcbef07f9/index.html) | Link to the JavaScript file: [app.js](https://github.com/sqrtofpi/UFOs/blob/16e348f831549b61cd1b1e97d0bbf70bcbef07f9/static/js/app.js)

## Overview of the Analysis

The objective of this analysis was to create a webpage featuring a dynamic table with the ability to filter results of UFO information from a prepopulated data file. This is the second iteration of the project as the first table featured the same data table but included only a filter for the date and also a button that would have to be pressed for the filter to function. With this update the ability to filter by City, State, Country, or Shape were added along with a feature that automatically filters the data when "tabbing" to the next field.

## Results

The data section of the webpage now includes the additional filter criteria which can be seen in this first image:

![Unfiltered Data](https://github.com/sqrtofpi/UFOs/blob/16e348f831549b61cd1b1e97d0bbf70bcbef07f9/Resources/Unfiltered%20Data.png)

Placeholders for the data have also been added to help the user know what kind of data should be entered for the filter to function properly.

This second image shows the filter in use:

![Filtered Data](https://github.com/sqrtofpi/UFOs/blob/16e348f831549b61cd1b1e97d0bbf70bcbef07f9/Resources/Filtered%20Data.png)

In this example, we have filtered using the city "el cajon".

## Summary

One major drawback of this current webpage and possibly the most significant is having "blind filtering" for a lack of better terminology. In other words, when filling in the data in any of the filter boxes, you must know what you are looking for which means you should have an understanding of all of the data in the dataset. For this limited data it is less of an issue but if there were millions of data points, this simply would not be useful in it's current state. To correct this issue it would be more helpful if when starting to type in any of the filter boxes, it would show the list of possible matches based upon the characters entered into the filter box.

Two additional recommendations to improve this project are:

1. Adding a second date filter box so the search can find results between the two dates that are input. This will help with the quality of the results as with a large data set, you may have many dates that only have a single result.
2. Adding a search box for the comment field. There could be a lot of data that could be gleaned by specific words included in the comment field. For example, typing "lights" in this search box would show all of the instances that the word "lights" was mentioned, or any other criteria of interest.

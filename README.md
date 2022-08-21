# UFO-s

Analyzing UFO data stored in a JavaScript array and creating a dynamic table to place into an HTML file for viewing

<p align="center">
    <img width="500" height="300" src= "https://github.com/rloufoster/UFO-s/blob/main/static/images/AlienGraphic.png">
</p> 

## Project Overview

The goal of this project is to sift through a large JavaScript file filled with UFO sightings information and organize it into an interactive table that can be viewed on The Web. In the first phase of this project we built a table using data stored in the JavaScript array, added filters to make the table fully dynamic and then placed the table into an HTML file for easy viewing. The table was then customized with Bootstrap and enabled with several fully functional filters that allows the user to interact with our visualizations. In the second phase of the project, we were tasked with doing a more in-depth analysis by allowing the users to filter for city, state, country and shape of the sighting.

Two deliverables were specifically requested:

* **Deliverable 1: Filter UFO sightings on multiple criteria**
* **Deliverable 2: A written report on the UFO analysis README.md.**


### Resources:

* Data Source: ufo_starterCode.js and index.html
* Data Tools: ECMAScript, JavaScript, Jupyter Notebook, Python and MongoDB
* Software: ES6+, ECMAScript, MongoDB, Python 3.8.3, Visual Studio Code 1.50.0


### Method: 

* Using JavaScript and HTML, the Phase 1 code was modified in the index.html file to enable the additional filters.  In addition to the original date filter, city, state, country and shape filters were applied. See image below.





* The handleClick() function in the app.js file was replaced with an new function
In order to react when an element is changed, we use Javascript functions to loop through the data to build the table and create a customized dashboard. The customizations include filters with event listeners that will record the information when an element has changed and develop an interactive webpage. Filters can be applied in many ways. In this exercise, we reviewed how to display default data in the table, listen for a button click or trigger the table to update based on the user's input with a select criteria. Finally, we use HTML, Bootstrap and CSS to read the Javascript code and create a webpage that is easy to view, includes filters, images, and a synopsis of the topic.


## Results


## Summary

### Problems:

* The search field is "case-sensitive". The table will not update if you do not enter exactly how the data is stored and does not allow for   partial entries. This is an issue because it does not intuitively tell the user how the information should be entered other than the         "default" example shown.

* There is no button to click, wording or action that tells the user that the table will update after you hit "enter".

* The data is limited and outdated since it is not linked to a "live" source.


### Future Development




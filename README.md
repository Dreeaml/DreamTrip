DreamTrip
DreamTrip is an easy and user friendly webside inspired in Trivago () and Momondo (). Here users can plan their stay in several countries, searching for the following categories: accomodation, food places, attractions, transportation and healthcare centers. 

UX
DreamTrip is a webside for travellers looking for plan their activities in their destinations. 
In this webside users can search for many relevant categories regarding travels that are importat to have in mind when you are visiting a new place.
DreamTrip integrated the popular categories but also include information about transportation and healthcare center in case of emergency.

At the beginning of the webside is provided an alert/message created with Bootbox, for the user explaining the concept of the side, so they know what to expect from it.

The first step is to read the concise message regarding the funcionality of DreamTrip.
The second step is to select the country the user is interested to go.
The third step is to write with help of an autocomplete function the specific city of the country the user want to visit.
The last step is to select which categorie the user want to know.
Finally, scrolling down to the "Result list" section, a clear list of the results is going to be displyed.

The user can click on any of the items in the result list an then check where is in the map and also is provided specific details of the place, such as Name, telephon, webside and ranking.

Also a contact form is provided in case the user want to leave a message. 

Features
Alert: Using bootbox a smooth message is going to appear when the page loads so the user understand the concept of DreamTrip.
NavBar: Section that contains the logo of DreamTrip and a simple contact button that redirect the user to the footer.
Filters: Consist of three filters( Country, City and Category).
Reset: Is a button to clear the parameters selected so the user can start a new search.
Map: An interactive map from Google Maps where all the result are going to display with markers on it.
Result List: The list of places are going to be displayed within this section.
Contact form: By clickin a bottom, a contact form will be displayes.

Existing Features
Feature 1: alert/message  - allows users to click the "OK" button in the initial message/alert so the window can close.
Feature 2: country filter - allows users to click on the "Country" filter and choose between several options. Once a country is selected the map will zoom automatically to it.
Feature 3: city filter - allows users to write a city with the help of an autocomplete function. This feature have a restriction funcionality that only cities from the selected country in the previous step will be displayed. Once a city is selected the map will zoom automatically to it.
Feature 4: reset button - allows users to clear all the filters and start a new search
Feature 5: map - allows users to visualize the result of the search, click on each result and see and Info window with relevant details about it. Js file: /assets/js/map.js
Feature 6: result list - allows users to have a clear list of all the result and they are able to click on them an see it in the map.
Feature 7: contact form - allow users to contact the author via a form.

Features Left to Implement:
Include more countries to the filter.
Create a wish list where users can save the searches and specific places they like.

Technologies Used:
Bootbox: http://bootboxjs.com/ To create an alert in a cleaner and easy way.
Bootstrap: https://www.bootstrapcdn.com/ To make the webside responsive.
HTML
CSS
JavaScript
Emailjs
Google Maps API: https://developers.google.com/maps/documentation/?hl=es To implement google maps and the facilities that it provide in the webside 
Google Fonts: https://fonts.google.com/
Font Awesome: https://fontawesome.com/ To include social accounts icons.
favicon : https://www.favicon-generator.org/
Marker : https://www.iconfinder.com/iconsets/online-shop-7
JQuery
The project uses JQuery to simplify DOM manipulation.

Testing

Contact form:
Click the "Contact" button.
Try to submit the empty form and verify that an error message about the required fields appears
Try to submit the form with an invalid email address and verify that a relevant error message appears
Try to submit the form with all inputs valid and verify that a success message appears.

The webside is tried in Responsinator (https://www.responsinator.com/) to check if all the media queries fit in Iphone, tablets and laptop screens.

Deployment
This site is hosted using GitHub pages, deployed directly from the master branch. To run locally, you can clone this repository directly into the editor of your choice by pasting git clone 
https://github.com/Dreeaml/DreamTrip---Milestone-Project.git into your terminal.

Credits
I received inspiration for this project from Trivago.com, Momondo.com and Holiday Planner (Code Institute student project).
This is for educational use.


# MiniProjectPP
Programming practices mini project of 3rd sem
PROJECT NAME - Geotrack Application 




Goal of the Project  -

An application which gives precise location of the user and helps user to keep track of his/her Running and Cycling Goals on a given location. It marks the location at which user wants to do the activity and also logs all the data provided by the user in local storage so that even when the user has closed his browser whenever he visits to the application next time it will show his goals which he saved earlier.

Technologies Used -

HTML,CSS,JAVASCRIPT(including OOPs concept), GEOLOCATION API, LEAFLET.JS,	
LEAFLET.CSS,Local Storage Browser API.

Sources preferred during the making of project -

MDN Web Docs

Leaflet Documentation

How does this work ? 

 When the user visits the webpage a pop up will appear asking for the access of his location

After the user has allowed for the location it will show his/her exact location  and also his previous activities which the user has marked on the web page.


Whenever user clicks on the map a form will appear with 2 main options - Running or cycling now user can set his Either running or cycling goal.


When the user will submit the form his location with his goal will be marked on the map

And also the data provided by the user will be saved in the local storage of the browser. So that even if he exits the browser and visits the application next time it will show his goals and he can keep track of his goals on the map.


How the project is made?

HTML and CSS is used to design the structure of the webpage.
When user opens the application and allows the access to his location with the help of Geolocation API in the browser the exact longitude and latitude is received and then with the help of api of openstreetmap we display the exact location of the user 
Now whenever user clicks on a particular location with the help of eventHandler function we get the exact coordinates of that location and by using this we display a marker at that exact location
When user clicks on a particular location a html form pop ups containing two options running or cycling with their own suboptions 
When user submits the form the marker is set on that exact location containing a tag with the text written “Running/Cycling on Date” and also appears on the logs on the left side of the page
This data is stored in the local storage in the form of key value pair.
Finally all of the code is structured in OOPs with a main class App containing two subclasses workouts and map and also some methods like its own constructor , getPosition,loadMap,showForm,toggleElevationField,newWorkout.
The classes Running and Cycling inherits the class Workout.
Here the constructor in the class App runs when the page loads , loadMap is used to receive position , showForm runs when user clicks on the map, toggleElevationField runs when user changes input and newWorkout when user submit the form.




















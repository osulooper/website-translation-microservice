# website-translation-microservice
A microservice that will allow the end user to translate a webpage into their chosen language at the click of a button


This program uses Flask. There are 2 files in this directory, server.py and index.html. index.html is inside a templates folder; it is the GUI that a user would use to translate a website. Integration of this would mean either including all of the functionality in this file in your own app(Language drop down menu and submit button). The server.py file represents the backend of the microservice. There are 2 methods wrapped with Flask wrappers that indicate what happens when the user goes down those routes. The home route just renders index.html. The my-link method and route represents when the user clicks the submit button in the GUI. The logic then redirects to the website and language of the users choice. If you implement this in your own web site you can take out the logic where the user chooses the website and just add your own url there.

You must install Flask before this can work. Here is the quickstart guide for Flask https://flask.palletsprojects.com/en/1.1.x/quickstart/

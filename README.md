# Realtime_weatherapp
Readme file for Weather App

This is a basic weather app that displays weather data for a given city. It uses the OpenWeatherMap API to fetch weather data in JSON format and display it on a web page.

The app is built using Django, a high-level Python web framework, and includes a single view named "index". When a user enters a city name in the search field and submits the form, the view retrieves the weather data for the given city using the OpenWeatherMap API and passes it to the template to display.

The template displays the weather data using HTML and Bootstrap, with some basic CSS styling.

To run the app, you'll need to have Python and Django installed on your machine. After downloading the code, navigate to the root directory and run the following command to start the development server:

```
python manage.py runserver

```

Then, open a web browser and go to `http://localhost:8000/` to access the app.

Note: You'll need to sign up for an OpenWeatherMap API key to use this app. Replace the value of `appid` in the URL in `views.py` with your own API key.

Thanks everyone!!!

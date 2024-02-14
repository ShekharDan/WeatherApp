Weather App

Introduction
This is a simple weather application developed using Java, Servlets, JSP, HTML, CSS, and JavaScript. It allows users to check the current weather conditions for a specific city.

Features
Real-time Weather Data: The app fetches real-time weather data from the OpenWeather API.
User-friendly Interface: The user interface is designed to be intuitive and easy to use.
Dynamic Weather Icons: The app displays dynamic weather icons based on the current weather conditions.
Technologies Used
Java: Used for backend development and handling HTTP requests.
Servlets: Handle HTTP requests and responses for dynamic content.
JSP (JavaServer Pages): Used to create dynamic web pages.
HTML/CSS: Responsible for the structure and styling of the web pages.
JavaScript: Used for dynamic behavior and updating the UI based on user input.
OpenWeather API: External API used to fetch real-time weather data.
How to Use
Enter the name of the city for which you want to check the weather.
Click the search button.
View detailed weather information, including temperature, humidity, wind speed, and weather conditions.
Code Structure
MyServlet.java: Backend servlet that handles HTTP requests, interacts with the OpenWeather API, and forwards data to JSP.
index.jsp: Dynamic web page that receives data from the servlet and displays it to the user.
style.css: Stylesheet for the HTML pages.
index.js: JavaScript file for dynamic behavior, including updating weather icons based on conditions.
Setup
Clone the repository.
Deploy the application on a Java Servlet container (e.g., Apache Tomcat).
Access the application through the deployed server.

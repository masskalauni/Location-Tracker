Location Tracker Web App
Overview
This is a straightforward web application designed for users to track their location using geolocation services. The app leverages the OpenCage Geocoding API to obtain the location name based on the user's latitude and longitude coordinates.

Features
Track Location: Click the "Track Location" button to initiate location tracking.
Continuous Updates: The app continuously updates and displays the location name, timestamp, and a link to view the location on Google Maps.
Automatic Stop: Tracking stops automatically after 30 seconds.
Usage
Open the HTML file in a web browser.
Click the "Track Location" button.
Grant permission for the app to access your location.
The app continuously updates and shows your location information.
Tracking ceases after 30 seconds.
Technologies Used
HTML
CSS
JavaScript
External APIs
OpenCage Geocoding API: Converts latitude and longitude coordinates into location names.
How to Run
Open the HTML file in a web browser to use the application. Ensure your browser supports geolocation services, and an internet connection is available.

Important Note
For security reasons, avoid exposing API keys in client-side code in a production environment. In a real-world scenario, API keys and sensitive operations should be handled on a server. This example is for educational purposes only.
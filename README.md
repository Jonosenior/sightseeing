# README

This is a toy project to practice interacting with the Google Maps API. It has the following features:

  - Users can add locations, and the address entry field will autocomplete using data from the Google Maps API.
  - When a location is added, the database entry is automatically filled with the latitude and longitude, using data from Google Maps via the Geocoder gem.
  - Each location's show page features a Google Map with the location as a pin.
  - The index page shows a list of every location and a map with a pin at every location.
  - The API key is stored securely using the Figaro gem.

These features will all be used in my best-restaurants project. 

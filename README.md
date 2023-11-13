# Geography of Japan Web Application

## Overview
This project is a web application designed to showcase the geographical features of Japan, specifically focusing on its volcanoes and earthquakes. It leverages Mapbox GL JS for map visualization and includes interactive elements for an engaging user experience.

## Files Description

### `index.html`: the main entry point of the web application. It presents an interactive map highlighting volcanoes in Japan.
- **Features**:
  - Displays a list of volcanoes in Japan.
  - Interactive map where users can view volcano locations.
  - Popups on the map to show names of volcanoes when hovered over.
  - Link to navigate to the earthquakes information page (`earthquake.html`).

### `earthquake.html`: This page focuses on displaying earthquake data in Japan.
- **Features**:
  - Interactive map showing earthquake locations.
  - Table listing earthquake details.
  - Back button to return to the main page (`index.html`).

### `assets/`
- **Contains**:
  - GeoJSON files for earthquakes and volcanoes data.
  - Any other static assets used in the web application.

## Functionality
- **Volcanoes**: The `index.html` page provides a visual and interactive representation of volcanoes in Japan. Users can see the location of each volcano on the map and get the name of the volcano by hovering over the points.
- **Earthquakes**: The `earthquake.html` page is dedicated to showcasing earthquake data. It offers a similar interactive experience, allowing users to understand the distribution and details of earthquakes in Japan.

## Technologies Used
- HTML5
- CSS3
- JavaScript
- Mapbox GL JS

## Future Enhancements
- Implementing a search functionality for easier navigation through the list of geological features.
- Adding more interactive elements and detailed information about each geological feature.

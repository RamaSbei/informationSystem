# Implementation Document

## Find Street Crime Web App

Prepared for coursework / project documentation

Figure 1. Context diagram for the Find Street Crime web app.

## Introduction

The web application enables users to search for street crime incidents and view matching results on an interactive map. Users enter a street name into the search field, and the application filters the crime dataset to display relevant incidents. Each result is shown as a map marker, and clicking a marker displays details about the selected incident, including the street name and crime category.

## Dataset

- The system uses a GeoJSON dataset containing street crime information.
- The dataset stores coordinates, street-name information, and crime categories.
- The dataset is loaded locally by the web application at runtime.

## Known issues

- If the GeoJSON file is incomplete or corrupted, the application may fail to display incidents correctly.
- Searching for a non-existent street name returns no results.
- Multiple incidents may share the same street name and appear as several markers.

## Software architecture

The application follows a layered architecture style, separating the user interface, business logic, and data access responsibilities.

## Technology stack

- HTML for structure
- CSS for styling
- JavaScript for search logic and behaviour
- Leaflet.js for the interactive map
- GeoJSON for data storage

## Use cases

### Use Case 1: Searching by Street Name

1. Open the application in a web browser.
2. Locate the street-name search field.
3. Enter a street name, for example "High Street".
4. Click the Search button.
5. The system filters the dataset and displays matching crime incidents on the map.

### Use Case 2: Viewing Crime Details on the Map

1. Perform a street search.
2. View the markers displayed on the map.
3. Click on a marker.
4. Read the popup information shown on screen.

### Use Case 3: Searching with No Exact Match

1. Enter a street name that does not exist in the dataset.
2. Click the Search button.
3. The system processes the search.
4. No matching incidents are displayed on the map.

## Application diagram

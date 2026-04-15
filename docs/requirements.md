# Requirements Specification

## Find Street Crime Web App

Prepared for coursework / project documentation

Figure 1. Context diagram for the Find Street Crime web app.

## User Needs

### User stories

- As a user, I want to search for crime incidents by street name, so I can quickly find crime information for a location I am interested in.
- As a user, I want to view crime incidents on an interactive map, so I can understand where incidents are located visually.
- As a user, I want to click a map marker, so I can view more details about a crime incident.
- As a user, I want to see the street name and crime category for each result, so I can better understand the data shown.
- As a developer, I want to load crime data from a GeoJSON file, so the application can display mapped crime information correctly.
- As a user, I want the app to be simple and easy to use on desktop and mobile devices.

### Actors

- Users: members of the public who want to search for and view street crime information.
- Developer: responsible for building and maintaining the application and its data integration.

### Use cases

## Software Requirements Specification

### Functional requirements

- FR1: The system shall allow users to search for crime incidents by street name.
- FR2: The system shall display crime incidents on an interactive map.
- FR3: The system shall load crime data from a GeoJSON file.
- FR4: The system shall place markers on the map for matching crime incidents.
- FR5: The system shall display a popup when a user clicks a marker.
- FR6: The popup shall show the street name of the selected crime incident.
- FR7: The popup shall show the crime category of the selected incident.
- FR8: The system shall provide a clear user interface with a search field and map display.

### Non-functional requirements

- NFR1: The application shall be easy to use for non-technical users.
- NFR2: The application shall load and display map data within a reasonable time.
- NFR3: The application shall be accessible through a web browser.
- NFR4: The interface shall remain readable on different screen sizes.
- NFR5: The map shall remain responsive during interaction.

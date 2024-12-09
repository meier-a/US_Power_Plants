# U.S. Power Plants Map

## Overview
The **U.S. Power Plants Map** is an interactive web application that visualises the distribution of electricity generation sources across the United States. Power plants are represented as proportional circles for each state, allowing users to explore the dominance of different energy sources, from fossil fuels to renewables. The application provides a geographic perspective on the US energy landscape and its reliance on different energy sources.

This project was inspired by the [New York Times article](https://www.nytimes.com/2024/11/12/climate/fossil-fuel-emissions-2024-record.html) entitled *"Fossil Fuels Are Still Winning: Global Emissions Head for a Record"* (12 November 2024). The visualisation complements the article by highlighting emissions hotspots and areas transitioning to cleaner energy alternatives.

The visualisation aims to provide an accessible tool for exploring the spatial distribution of power plants across the United States. It highlights regional differences in energy production, facilitates comparisons between different energy sources, and provides insights into the structure and dynamics of the US energy infrastructure.

## Features
- **Filter by Energy Source**: Use the drop-down menu to display power plants for specific energy sources (e.g., wind, solar, coal).
- **State-Level Insights**: Hover over a state to view a detailed breakdown of power plant counts by its energy source.
- **Interactive Navigation**: Zoom, pan, and reset the map for a customizable view.
- **Visual Legend**: A legend explains the circle sizes and color coding for easy interpretation.
- **Welcome Popup:** A brief introduction explains the map's purpose and key features, guiding users on how to navigate and interact with the visualization.

## Data Sources
The following datasets were used in this project:
- **U.S. Energy Information Administration (EIA)**: [Power Plant Data](https://atlas.eia.gov/datasets/eia::power-plants/explore?location=29.746965%2C61.504000%2C2.98)
- **U.S. Census Bureau**: [State Boundary Shapefiles](https://www.census.gov/geographies/mapping-files/time-series/geo/carto-boundary-file.html)

The basemap tiles are provided by [CartoDB DarkMatter](https://carto.com/attributions), and geographic data is sourced from [OpenStreetMap](https://www.openstreetmap.org/copyright).

## Main Packages and Libraries
This application was built using the following key packages:
- **[Leaflet.js](https://leafletjs.com/)**: For interactive map rendering.
- **Google Fonts**: For custom typography (`Titillium Web`).
- **HTML/CSS/JavaScript**: For web development and styling.



**Author:** Anna Meier

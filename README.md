# Seattle's Interactive Map Application

## Project Name
Tile Mapping Application of Seattle

## Introduction
This interactive web map provides a platform for exploring different layers of Seattle's landscape, emphasizing its rich cultural history and landscape. The map combines a user-friendly interface with various visual layers that represent the city's streets, urban centers, and areas of cultural significance, especially relating to the relevant event of Black History Month.

## Map Access
You can view and interact with the map [here](https://anthonykminsu.github.io/NewTmapApplication/). (Note: Replace the hash (#) with the actual URL where the web map is hosted.)

## Screenshots
- Base Map Layer: Shows a simple dark-themed layout of Seattle. The zoom level in this case goes over 14 and has unlimited min zoom due to tile sourcing.
Location: Seattle, Washington
- Streets Layer: Provides detailed street maps for easy navigation. The zoom level in this case also goes over 14 and also had unlimited min zoom.
Location: Seattle, Washington
- Urban Areas Layer: Derived from Seattle’s open data, highlighting urban centers. The zoom level in this case is 12-22 for the best view.
Location: Seattle, Washington
- Black History Month Theme Layer: Emphasizes locations significant to Black History Month. The max zoom level in this is 11 and the min zoom is 3.
Location: Redmond, Oregon

## Geographic Area Examined (Location)
The map focuses on the Seattle area, encompassing urban centers, commercial hubs, and regions of cultural significance.

## Zoom Levels
Each tile set within the map can be viewed at various zoom levels, allowing users to dive into street-level details or get an overview of the city.

- Base Map: Zoom levels 0-22
- Streets: Zoom levels 0-22
- Urban Areas: Zoom levels 12-22 (for detailed viewing)
- Black History Month Theme: Zoom levels 3-11

## Descriptions of Each Tile Set
- Base Map: A dark mode base map that provides a subtle backdrop to other data layers.
- Streets: A detailed representation of Seattle's thoroughfares, perfect for navigation and street-level detail.
- Urban Areas: This layer outlines the designated urban centers, villages, and industrial centers within Seattle, based on the data from [SeattleCityGIS](https://data-seattlecitygis.opendata.arcgis.com/datasets/SeattleCityGIS::urban-centers-villages-and-manufacturing-industrial-centers/explore?location=47.677863%2C-122.345360%2C11.00).
- Black History Month Theme: Themed layer utilizing the colors of unity and pride, symbolizing important locations for Black history in Seattle.

## Libraries in Use
- Mapbox GL JS
- Leaflet CSS
- jQuery UI CSS

## Data Sources
The "Urban Areas" layer data is sourced from the [City of Seattle’s open data platform](https://data-seattlecitygis.opendata.arcgis.com/).

## Credit
This map application was created by me Anthony Kim as part of a lab at the University of Washington.

## Acknowledgment
Special thanks to the City of Seattle and Professor Zhao for providing open data which makes this map a valuable resource for locals and visitors alike. Shoutout to Liz for help on GIS techniques.

# Seattle's Interactive Map Application
![tilemap](https://github.com/anthonykminsu/NewTmapApplication/assets/77130958/8fcf58c8-91e3-43d8-8d0e-009c0be6caa2)

## Project Name
Tile Mapping Application of Seattle

## Introduction
This interactive web map provides a platform for exploring different layers of Seattle's landscape, emphasizing its rich cultural history and landscape. The map combines a user-friendly interface with various visual layers that represent the city's streets, urban centers, and areas of cultural significance, especially relating to the relevant event of Black History Month.

## Map Access
You can view and interact with the map [here](https://anthonykminsu.github.io/NewTmapApplication/). (Note: Replace the hash (#) with the actual URL where the web map is hosted.)

## Screenshots
<img width="720" alt="Screen Shot 2024-03-08 at 12 13 32 AM" src="https://github.com/anthonykminsu/NewTmapApplication/assets/77130958/4f9ce2e2-a51f-42cf-8e3a-694a9dbe1398">

- Base Map Layer: Shows a simple dark-themed layout of Seattle. The zoom level in this case goes over 14 and has unlimited min zoom due to tile sourcing.
- Location: Seattle, Washington  

---

<img width="720" alt="Screen Shot 2024-03-08 at 12 13 36 AM" src="https://github.com/anthonykminsu/NewTmapApplication/assets/77130958/a4fbf9c6-c90e-4745-bc2e-fa387d4faba6">
- Streets Layer: Provides detailed street maps for easy navigation. The zoom level in this case also goes over 14 and also had unlimited min zoom.
- Location: Seattle, Washington


---

<img width="720" alt="Screen Shot 2024-03-08 at 12 13 41 AM" src="https://github.com/anthonykminsu/NewTmapApplication/assets/77130958/5f17f0cd-6bea-4571-9e51-decaccae2e77">
- Urban Areas Layer: Derived from Seattle’s open data, highlighting urban centers. The zoom level in this case is 12-22 for the best view.
- Location: Seattle, Washington

---

<img width="720" alt="Screen Shot 2024-03-08 at 12 14 09 AM" src="https://github.com/anthonykminsu/NewTmapApplication/assets/77130958/dea1f687-f7c4-4038-a701-d33fc3a7adcb">
- Black History Month Theme Layer: Emphasizes locations significant to Black History Month. The max zoom level in this is 11 and the min zoom is 3.
- Location: Redmond, Oregon

---

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

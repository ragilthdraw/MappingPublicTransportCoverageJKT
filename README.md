# MappingPublicTransportCoverageJKT
This project aims to evaluate the coverage and accessibility of public transport services in the city of Jakarta, Indonesia, by utilizing spatial data and GTFS (General Transit Feed Specification) format.Due to the unavailability of an official GTFS feed for Semarang, a custom dataset was manually compiled from available route maps and OpenStreetMap data. The main goal is to identify which areas in Semarang are well-served by public transport and which are underserved, using spatial buffers and overlay techniques.

🎯 Objectives:
Convert Semarang’s public transport information into GTFS format

Visualize public transport stop locations

Generate 500-meter walking distance buffers around each stop

Overlay buffer coverage with administrative boundaries

Calculate the percentage of each neighborhood covered by public transport

Produce interactive maps and statistical summaries

🛠️ Technologies Used:
Python: GeoPandas, Shapely, Folium, Pandas

QGIS: Data preparation and shapefile handling

GTFS: stops.txt, routes.txt, trips.txt (custom-built)

OpenStreetMap: Base map and road network reference

GeoJSON / Parquet: For geospatial data storage

📈 Expected Outcomes:
A spatial layer showing walkable coverage areas from transport stops

A choropleth map visualizing the coverage percentage per neighborhood

CSV reports summarizing underserved areas

Recommendations for route expansion and stop placements

📦 Use Cases:
City planning and equitable transport policy analysis

Transportation accessibility studies

Supporting sustainable mobility and smart city initiatives

---
title: "QGIS Workshop Agenda"
permalink: /qgis/agenda/
---

**Introduction to QGIS Workshop**  
*Tentative Agenda*  
**8:30 AM – 4:30 PM**

---

## Morning Session

### 8:30 – 9:00 | Welcome & Overview of GIS
- Participant introductions  
- What is GIS?  
- Vector vs. Raster data  
- Coordinate systems (conceptual overview)  
  - WSG 84, UTM 15 NAD 83, Mercator - commonly used with Web Maps

### 9:00 – 9:30 | Introduction to the QGIS Interface and 
- Tour of the QGIS window and Interface
- Extensions and the plugins we need to turn on as well as other tool bars/panels
  -   HCMGIS
- Adding Data and file formats
  -  ShapeFiles
  -  GeoJSON
  -  GeoPackage
  -  CSV - with and without coordinates
  -  ESRI Geo Database
- Connect to Data Directory by adding a Favorite
- Start a new project and adding the "world" Easter Egg as a background
  - vacationStates.shp and files inside National-Regional/
- Changing the Project CRS  
- Saving and managing projects
- Layer Management
- Add some basic symbology

### 9:30 – 10:15 | Building Our First Thematic Map  
- Add Iowa county boundary data
- Connecting to ESRI background map using HCMGIS plugin
- Add Data
  - ia_border_utm15n
  - airports
  - highway
  - ia_county_utm15n
- Managing layer order 
- Create a choropleth map  
- Adjust classification methods  
- Explore categorical vs. numerical data symbology

### 10:15 – 10:30 | Break

### 10:30 – 11:30 | Data & Layer Management  
- Adding vector and raster layers  
- Connecting to OpenStreetMap (XYZ Tiles)  
- Managing layer order  
- Adjusting transparency  
- Organizing projects effectively
- Edit the Vacations data layer
- Add csv with coordinates
  -  sampleCoordinates.csv
- Join population CSV data (example 1 with total population)
  - county_PopulationTotalTrends/counties_pop1990_2020.csv

### 11:30 – 12:00 | Introduction to Print Layout (Part 1)  
- Creating a new layout  
- Adding map elements  
- Exporting PDF and JPEG  

### 12:00 – 1:00 | Lunch Break

---

## Afternoon Session

### 1:00 – 1:45 | Symbology Deeper Dive and Labels
- Styling points, lines, polygons  
- Classification and color ramps  
- Refining the Iowa or US map  

### 1:45 – 2:15 | Working with Attribute Tables
-Explore the Schools/2025_26_SchoolDistricts_Enrollment
- Sorting and filtering  
- Field Calculator  
- Expressions  

### 2:15 – 2:30 | Break

### 2:30 – 3:00 | Joining & Editing Data
- CSV joins part 2
  - county_census_acs_2017_5year_b11003.csv
- Digitizing features
  - Modify USA Map
  - Make new Geometry
- Saving edits and new geometry into a GeoPackage

### 3:00 – 3:30 | Geoprocessing Tools - Introduction
- Temporary Files
- Geoocoding
  - iowa_geocoding_safe_50.csv
- Buffer  
- Clip or Intersect  
- Reprojecting data

### 3:30 – 3:50 | Print Layout (Part 2 – Advanced)
- Multiple map frames / Overview map
  - Use Schools/2025_26_SchoolDistricts_Enrollment 
- Legend refinement  
- Export settings  

### 3:50 – 4:30 | Practice and Wrap-Up
- Final Q & A

### Resources
- [Documentation](https://www.qgis.org/resources/hub/)
- [User Manual](https://docs.qgis.org/3.44/en/docs/user_manual/)
- [Training Manual](https://docs.qgis.org/3.44/en/docs/training_manual/)
- 3D
  - Great Intro to 3D by [Jess Zimmerman on YouTube](https://www.youtube.com/watch?v=xcHG0ivjDxE)

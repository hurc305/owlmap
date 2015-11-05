# Sammy Map

This is an in class exercise for the HURC 305 students.

## Goals

1. Explore how smartphones and other technologies create VGI.
  - students used their phones to take photos and extract EXIF geospatial data
  - students used the drop-pin function on their devices to find geospatial data of where they were at a moment
  
2. sync data from GoogleDrive to CartoDB
  - a simple google spreadsheet with lon / lat / name / description / img src was shared with students to enter data
  - it is synced to a cartoDB dataset
  - students can continue to edit the google spreadsheet without having to access cartoDB and the map will update once every hour
  
3. explore fine-tuning via Leaflet.js of cartoDB generated maps
  - this file is shared with students via github
  - we can use the Map State options of Leaflet to contorl how users zoom / pan in the map
  - the map options are a jumping off point to exploring everything possible in leaflet
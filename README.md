# LSTINDEX
This interactive web application allows users to calculate, visualize, and export the median Land Surface Temperature (LST) for Greater Melbourne. It is built using the Google Earth Engine API to process satellite data 
# Land Surface Temperature (LST) Web App

## Description
This repository contains the Google Earth Engine JavaScript code for a web application that calculates and visualizes the median Land Surface Temperature for Greater Melbourne using MODIS data.

- **Student Name:** AYMAN ABDELKARI
- **Student ID:** [S3749580]
- **GEE App Live Link:**[https://prac3-468307.projects.earthengine.app/view/lstmelbindex]

## How to Use the Code
1.  Click the Google Earth Engine script link below.
2.  It will open the code in the GEE Code Editor (you must be logged in).
3.  Click "Run" to see the app panel appear.
4.  Ensure your Melbourne boundary asset is correctly linked and shared publicly.

## GEE Script Link
[https://code.earthengine.google.com/e438108c4f3ede1a4479fe6e58eb0ab6]

## Code Overview
The main logic of the application includes:
- Importing the MODIS MYD11A2 dataset.
- Filtering by date and region.
- Calculating median composite and converting Kelvin to Celsius.
- Generating zonal statistics for SA2 regions.
- Providing a UI for calculation and export.

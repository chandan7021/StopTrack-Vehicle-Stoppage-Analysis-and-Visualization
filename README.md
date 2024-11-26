
# VEHICLE STOPPAGE IDENTIFICATION 

## Overview
This project is a web application designed to identify and visualize vehicle stoppages using GPS data. The application processes real-time data to detect stoppage points and displays them on an interactive map, providing detailed information about each stoppage.
<br/>
 
 ![image](https://private-user-images.githubusercontent.com/106874326/346134356-5be555cf-798d-48c3-9012-e752f3dacc94.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzI2MTY0NDUsIm5iZiI6MTczMjYxNjE0NSwicGF0aCI6Ii8xMDY4NzQzMjYvMzQ2MTM0MzU2LTViZTU1NWNmLTc5OGQtNDhjMy05MDEyLWU3NTJmM2RhY2M5NC5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQxMTI2JTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MTEyNlQxMDE1NDVaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT1hNjY5ZTg3OGM1OWRmMWU3YTc5ZGUyMjliZmFmMDdlYmVmZWFjZGNjYmEzNDY4YTIwMDQ3NDhhYzg4NDNjNjQyJlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCJ9.OTsQ00CQZ5ojTKZz_8faHgmqqOagY3g_TfDAM3VhXGo)


 
## Features

   Interactive Map: Visualize vehicle paths and stoppages on a Leaflet map with custom markers.\
   Real-time Data Processing: Fetch and parse GPS data from a user-provided CSV URL.\
   Stoppage Detection: Identify stoppages based on speed and time thresholds, and display detailed information about each stoppage.\
   User Customization: Allow users to input custom CSV URLs and adjust stoppage detection thresholds.

## Technologies Used

   Frontend: React, Material-UI\
   Mapping: Leaflet\
   Data Fetching: Axios

## Components

   App: Main component managing state and layout.\
   Mapfunction: Renders the interactive map with vehicle paths and stoppages.\
   StoppageForm: Provides an interface for users to set stoppage detection thresholds.\
   FileReader: Fetches and parses CSV data from a provided URL.\
   StoppageProcessor: Processes the GPS data to detect stoppages.
   
## How to Use

   Enter CSV URL: Provide the URL of a CSV file containing GPS data.\
   Set Threshold: Adjust the threshold for stoppage detection in minutes.\
   View on Map: The map will display the vehicle path and detected stoppages with detailed information.



## Installation 
   Clone the repository:
```
   git clone https://github.com/yourusername/vehicle-stoppage-visualization.git
```
   Navigate to the project directory:
   
```
   cd vehicle-stoppage-visualization
```
   
   Install dependencies:
```
   npm install
```
   Start the development server:
```
   npm start
```

## Usage

   Open your browser and navigate to http://localhost:3000. \
   Enter the URL of a CSV file containing GPS data.\
   Set the stoppage detection threshold in minutes.\
   View the vehicle path and stoppages on the map.


 ## Example CSV Format
 ```csv
latitude,longitude,speed,eventdate,eventGeneratedTime
12.9715987,77.5945627,0,1622548800000,1622548800000
12.9715987,77.5945627,5,1622548860000,1622548860000
...

```
## Contact
For any inquiries or feedback, please contact chandanhz1207@gmail.com



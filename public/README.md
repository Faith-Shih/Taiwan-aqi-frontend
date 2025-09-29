# Taiwan Air Quality Index Application

This project is a web application that provides real-time air quality information for Taiwan. It consists of a Node.js backend that fetches data from an external API and serves it to a front-end HTML page.

## Frontend Overview

The frontend of the application is located in the `public` directory, specifically in the `aqi.html` file. This file is responsible for displaying the air quality data fetched from the Node.js backend.

### How to Use

1. **Open the HTML File**: You can open `aqi.html` directly in a web browser. This file will make requests to the Node.js backend to retrieve air quality data.

2. **Select County and Town**: Use the dropdown menus to select a specific county and town. The application will filter the air quality data based on your selection.

3. **View Air Quality Information**: Click on the markers on the map or select a town from the dropdown to view detailed air quality information, including:
   - Site Name
   - County
   - Air Quality Index (AQI)
   - Status
   - Publish Time
   - Longitude
   - Latitude

### Dependencies

The frontend uses the following libraries:
- Google Maps API for displaying the map and markers.
- MarkerClusterer for clustering the markers on the map.

### Development

To run the application in a development environment, ensure you have Node.js installed. You can start the server by running the following command in the root directory of the project:

```
npm start
```

This will start the Express server, and you can access the application through your browser.

### Notes

- Ensure that you have a valid API key for the Google Maps API.
- The backend fetches air quality data from the specified API endpoint and processes it before sending it to the frontend.

For more information on the overall project setup and usage, refer to the main `README.md` file in the root directory.
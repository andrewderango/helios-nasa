**Authors**: Andrew De Rango | Hashim Bukhtiar | Hashir Imam | Marco Tan | Pranav Chandrakumar | Rafael Toameh

# HELIOS

## About HELIOS: the High-resolution Earth Light and Infrared Observation System.
This project was developed as part of the 2024 NASA Space Apps Challenge, tackling the challenge of integrating Landsat Surface Reflectance (SR) data with ground-based spectral measurements. The goal is to create a web-based application that allows users to define a target location, receive notifications when a Landsat satellite will pass over, and access the corresponding SR data, simplifying a previously labor-intensive task. Visit our team page on the website [here](https://www.spaceappschallenge.org/nasa-space-apps-2024/find-a-team/maplenauts/?tab=project)!

## Objective
The application provides users with the ability to:

- Define a target location (via map selection or manual input of latitude/longitude).
- Receive alerts about upcoming Landsat overpasses for that location.
- Access, display, and analyze corresponding Landsat SR data.
- Compare satellite observations with ground-based surface spectral measurements.
- This tool is designed to support experiential learning, empower citizen scientists, and promote Earth observation studies by making Landsat data more accessible and user-friendly.

## Features
- Location Selection: Users can define a target location by place name, coordinates, or by placing a pin on a map.
- Satellite Overpass Notifications: Users will be notified before a Landsat satellite passes over their defined location.
- Data Display: Landsat SR data is visualized in a 3x3 grid of pixels surrounding the target area, including scene metadata (cloud cover, acquisition time, etc.).
- Threshold Customization: Users can filter data based on cloud cover or date range.
- Data Export: Download the data in a useful format like CSV for further analysis.

## Use Cases
- Educational Tool: Promotes learning through the comparison of satellite and ground-based data, helping students and researchers connect landscape observations with real-world satellite measurements.
- Research and Validation: Assists scientists and land managers in validating satellite data with ground reference measurements to ensure data accuracy.

## Getting Started
First, run the development server:

```bash
cd helios-frontend
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

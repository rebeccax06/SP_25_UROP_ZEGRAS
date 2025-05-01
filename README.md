# Interactive Mapping: Bicycle Accessibility Workshop

This project provides a simple interactive mapping website for a workshop on bicycle accessibility. The website uses static GeoJSON and GeoTIFF files to display data for different urban areas. Participants can toggle layers and choose which area to view.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Steps](#steps)
- [File Structure](#file-structure)
- [Usage](#usage)
- [Customizing Data](#customizing-data)
- [License](#license)

## Features

- **Interactive Map:** Built with Leaflet, the map displays an OpenStreetMap base layer.
- **Data Layers:**
  - **GeoJSON Layer:** Visualizes features such as bike lanes, intersections, and points of interest.
  - **GeoTIFF Layer:** Displays travel time surfaces or isochrone maps.
- **User Controls:** Sidebar options to toggle data layers and select different urban areas.
- **Responsive Design:** Optimized for various screen sizes.

## Installation

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, etc.)
- A static file server (optional) for local development (e.g., `http-server`, Python’s `http.server`, etc.)

### Steps

1. **Clone or Download the Repository:**

   ```bash
   git clone https://github.com/yourusername/interactive-mapping-workshop.git
   cd interactive-mapping-workshop

2. **File Structure Setup**
    interactive-mapping-workshop/  
    ├── index.html  
    ├── README.md  
    ├── data/  
    │   ├── conveyal_geotiff_spring_2025_all_modifications.geotiff  
    │   ├── conveyal_isochrone_spring_2025_all_modifications_at_60_minutes.json  
    data/ holds all the static files
3. **Run the Application**
    - Using a static server:
        - With Node.js (http-server)  
        `npm install -g http-server  
        http-server . `  
        Open your browser and navigate to http://localhost:8080.


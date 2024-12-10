```markdown
# Water Quality Monitoring System

## Overview
A desktop application for monitoring and analyzing water quality data, focusing on Persistent Organic Pollutants (POPs) and Fluorinated Compounds (PFAS) across multiple sampling locations.

## Features
- **Real-time Data Visualization**
  - Interactive time-series charts
  - Geospatial distribution maps
  - Compliance indicators

- **Multi-Parameter Analysis**
  - POPs concentration tracking
  - PFAS level monitoring
  - Threshold compliance checking

- **Data Management**
  - CSV data import/export
  - Historical data analysis
  - Sampling point management

## Technologies
- Qt 6.x - Core framework
- C++17 - Programming language
- CMake 3.16+ - Build system
- CSV Parser - Data handling

## Installation
bash
git clone https://github.com/username/waterqualitymonitoring.git
cd waterqualitymonitoring
mkdir build && cd build
cmake ..
make
```

### Main Components
- **Dashboard**: Provides an overview of the main pages and core functionality.
- **Data Page**: Displays pollutant data in a table format, enabling efficient browsing and editing.
- **Analysis Pages**:
  - **Pollutant Trends**: Visualizes pollutant concentration changes over time.
  - **Safety Compliance**: Highlights alerts for non-compliant pollutant levels.
  - **Geographical Hotspots**: Offers a map or heatmap of sampling points.
  - **Summary Statistics**: Displays averages, maximums, minimums, and other insights.

## Key Features
- **Internationalization**: Automatically adjusts the application language based on system locale settings.
- **Modular UI**: Logical grouping of controls and data in a sleek card layout.
- **Interactive Tooltips**: Provides additional context when hovering over UI elements.

## Design Choices
- **Model/View Architecture**: Ensures flexibility in handling large datasets and separates data logic from presentation.
- **Advanced Visualization**: Charts and compliance indicators for clear interpretation of pollutant data.
- **Card-Based Layout**: Groups related controls and data into easily navigable cards for better usability.

## Known Issues
- Slight delay when transitioning between pages.
- Map feature is currently in development and uses static placeholder data.

## Future Development
- Integrate dynamic geospatial maps with interactive markers.
- Add support for advanced statistical analysis.
- Implement user authentication for multi-user access control.

## Team Members
- Mohamed Shamir 
- Hpone Thu 
- Veerinrada Pianapitham 
- Alp Akkor 

## Folder Structure
```
waterqualitymonitoring/
├── src/                 # Source code for the application
├── data/                # Directory for CSV files
├── ui/                  # UI design files
├── README.md            # Project documentation
├── CMakeLists.txt       # Build configuration
└── LICENSE              # License for the project
```

## License
This project is licensed under the MIT License. See the `LICENSE` file for more details.

## Acknowledgments
- Special thanks to the Qt Community for their excellent resources and documentation.
```

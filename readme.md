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
- `Qt 6.x` - Core framework
- `C++17` - Programming language
- `CMake 3.16+` - Build system
- `CSV Parser` - Data handling

## Installation
```bash
git clone https://github.com/username/waterqualitymonitoring.git
cd waterqualitymonitoring
mkdir build && cd build
cmake ..
make

## Application Structure

### Main Components
- **Dashboard**: Provides an overview of the application’s main pages and core functionality.
- **Data Page**: Displays pollutant data in a table format, allowing us to browse relevant fields. Utilises the model/view architecture from the starter code.
- **Analysis Pages**:
    - **Pollutant Trends**: Visualises changes in pollutant levels over time.
    - **Safety Compliance**: Displays alerts for pollutant levels that exceed recommended limits.
    - **Geographical Hotspots**: Provides a map view or heat map of sampling points.
    - **Summary Statistics**: Calculates and displays averages, maximums, minimums, and other summary data.

## Key Features
- **Internationalisation**: The app supports language changes based on system locale settings.
- **Modular UI**: Using a "card" approach, each data type or control is grouped logically within the interface.
- **Tooltips**: Hovering over elements displays additional context, improving usability.

## Design Choices
- **Model/View Architecture**: Chosen for flexibility in data handling and to separate data presentation from underlying storage.
- **Data Visualisation**: Includes basic charts and compliance indicators to ensure intuitive data interpretation.
- **"Card" Layout**: The UI is modularised into “cards,” each focused on a specific data group or control area.

## Included Files
- **Source Files**: Core source files such as `mainwindow.cpp`, `fluorinatedcompounds.cpp`, `datamanager.cpp`, `mainwindow.hpp`, `fluorinatedcompounds.hpp`, `datamanager.hpp`, etc.

## Known Issues
- Slight stiff transition between switching pages.

## Future Development
- Will be improving the overall code to be able to implement map feature along with roll-over markers.

## Team members
- Mohamed Shamir, Hpone Thu, Veerinrada Pianapitham, Alp Akkor

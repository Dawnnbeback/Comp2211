```markdown
### Overview
- This application is designed to monitor and analyse water quality data, with a focus on pollutant tracking and compliance with safety standards. 
- It was developed using **C++/Qt6** with a modular and user-friendly interface that adapts to changes in locale for basic internationalisation.
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

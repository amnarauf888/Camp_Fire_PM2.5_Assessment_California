
## Camp Fire PM2.5 Assessment in California, 2018

| | |
|---|---|
| **Author** | Amna Rauf |
| **Course** | ENV 859 — Geospatial Data Analytics |
| **Instructor** | John Fay |
| **Date** | December 10, 2025 |

Project Overview: This project analyzes how the 2018 Camp Fire affected air quality in Northern California by comparing PM2.5 concentrations at EPA monitoring stations before and after the fire. The analysis uses a 100km buffer around the fire perimeter to identify affected monitors and includes a reusable ModelBuilder tool.

Key Findings:
The Camp Fire resulted in a substantial average PM2.5 increase of 91.7 µg/m³ (57% increase) at monitoring stations within 100km of the fire perimeter. 

Quick Start
Open Project: Air_Quality_California.aprx in ArcGIS Pro
View Maps: Study Area Map and Results Map (color-coded by PM2.5 change)
Run Tool: Catalog-> Toolbox-> "Fire Air Quality Analysis"

Tool Usage

To Run the Tool:
1. Open Catalog->Air_Quality_California.atbx -> Double-click "Fire Air Quality Analysis"
2. Select Fire Perimeter and PM2.5 Monitors from dropdowns (already in map)
3. Set buffer distance (default: 100 km) and output name
4. Click Run

Parameters: Fire Perimeter, PM2.5 Monitors, Buffer Distance, Output Name
Note: Layers must be in your map before running. For different fires, add your data to map first.

Workflow Summary

Phase 1: Data Acquisition
Downloaded Camp Fire perimeter (NIFC)
Obtained EPA monitor locations and PM2.5 data (Oct-Dec 2018)

Phase 2: Spatial Analysis (ModelBuilder)
Created 100km buffer around fire
Selected 27 PM2.5 monitors within buffer
Exported selected monitors for data processing

Phase 3: Data Processing (Excel)
Filtered PM2.5 data to selected monitors
Calculated Before (Oct 9-Nov 7) and After (Nov 26-Dec 25) averages
Computed PM2.5 changes and percent changes

Phase 4: Visualization
Created Study Area and Results maps
Generated before/after comparison chart

Data Sources
Fire Perimeter: NIFC Historic Perimeters 2000-2018
Monitor Locations: EPA Air Quality System (aqs_monitors.csv)
PM2.5 Data: EPA AQS Daily Summary Data (daily_88101_2018.csv)

Note: Please refer to the file 'Project Document' in the Documentation Folder under Results for a complete project overview.

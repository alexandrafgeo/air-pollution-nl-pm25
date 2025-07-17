# air-pollution-nl-pm25
Mapping PM2.5 air pollution in the Netherlands for 2024, (interpolated data), interim data, June 2025

##  Objectives
- Visualize PM2.5 levels across the Netherlands
- Identify regional pollution hotspots
- Explore spatial correlation between industrial activity and pollution patterns

##  Final Maps
  **•	Created surface visualization of PM2.5 with classified symbology**
   - Shows the spatial distribution of PM2.5 concentrations in 2024.
   - Based on interim interpolated raster data from EEA.

  **Average PM2.5 by Region**
   - Zonal statistics applied to polygon boundaries of municipalities.
   - Provides regional averages for clearer administrative comparisons.

  **Industrial Facilities Emissions (2023, PM10)**
   - Point data showing large industrial facilities reporting PM10 emissions (latest available 2023 year).
   - Overlayed on top of pollution data to highlight potential contributing sources.
   - Note: PM2.5 emissions were not available, so PM10 was used as a proxy.

##  Tools and Methods
- **Software:** ArcGIS Pro
- **Analysis:**
  - Displayed raster and tabular data with proper coordinate systems
  - Used classification and symbology to visualize pollution intensity
  - Zonal Statistics to aggregate raster values by region
  - Manual inspection of potential industrial impact through spatial overlay
- **Sources:**
  - EEA PM2.5, European air quality data for 2024, (interpolated data), interim data, June 2025
  - EEA Industrial Reporting Dataset (PM10 emissions, 2023)
  - Dutch administrative boundaries (GADM)

##  Notes
- PM2.5 emissions from industrial sources were not available as of 2024 reporting; PM10 was used to approximate spatial emission patterns.
- Temporal mismatch acknowledged: pollution data (2024), industrial data (2023). Still valid for long-term industrial analysis. 

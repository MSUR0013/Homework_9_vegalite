# Australia LGA Population Change 2023–24 (%)

This project visualizes the **population change across Australian Local Government Areas (LGAs)** for the period **2023–2024**, using a choropleth map based on percentage change.

## Overview

- **Type of data**: Population percentage change by LGA
- **Map idiom used**: Choropleth (normalized data)
- **Geographic focus**: Australia (zoomed in appropriately)
- **Projection**: Regional projection optimized for Australian geography
- **Tool used**: Mapshaper / Vega-Lite (can be integrated)

##  Visualization Quality

This map adheres to best practices in cartographic design:
- Uses **normalized data (percentage)**, which is correct for choropleths
- **Appropriate projection** for Australian regional view
- **No excessive whitespace** or global context clutter
- **Clear legend** indicating population change bands
- **Color scale** uses a sequential palette (light yellow to dark red), which is appropriate for magnitude-based data
- **Descriptive title** includes topic, region, and time period

## Data Source

All data was sourced from the **Australian Bureau of Statistics (ABS)**:

- [ABS Regional Population 2023–2024 – Data Downloads](https://www.abs.gov.au/statistics/people/population/regional-population/latest-release#data-downloads)

## Files Included

- `lga_population_change_map.html`: HTML interactive version of the choropleth map
- `LGA_2024_AUST_GDA2020.json`: GeoJSON file of Local Government Areas
- `population_change_2023_24.csv`: CSV file containing LGA codes and % change
- `README.md`: Project documentation

## Notes

- Regions with **no data** are shown in white and are labeled accordingly
- The visualization avoids inappropriate map idioms, misleading color channels, or missing legends

## License

This project is for educational purposes under Monash University's FIT3179 Data Visualization course. Original data belongs to the ABS.

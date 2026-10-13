# Zambia Administrative Boundaries and Provincial Population Density Mapping

## Project Overview
This project uses QGIS to map the spatial distribution of population density across Zambia's ten provinces using 2022 provincial population data and administrative boundaries.

## Objectives
- Map Zambia's provincial administrative boundaries.
- Calculate provincial land area and population density.
- Visualise differences in population density using graduated symbology.
- Produce a publication-quality map for spatial interpretation and GIS portfolio demonstration.

## Data Sources
- **Administrative boundaries:** geoBoundaries.
- **Population data:** Zambia Statistics Agency (ZamStats), 2022 Census of Population and Housing, National Analytical Report.

## Methodology
1. Load and inspect Zambia's national and provincial administrative boundaries in QGIS.
2. Join provincial population data to the provincial boundary layer using province names.
3. Calculate provincial land area in square kilometres.
4. Calculate population density as population divided by area.
5. Symbolise the resulting density values using five Natural Breaks (Jenks) classes.
6. Compose and export the final map with a legend, scale bar, north arrow, title and source note.

## Outputs
- `Zambia_Population_Density_2022.pdf`
- `Zambia_Population_Density_2022.png`

## Limitations
Population density is calculated at provincial level and therefore does not reveal how population is distributed within individual provinces. Provincial averages can mask substantial differences between urban and rural areas. The map represents population data for 2022 and should not be interpreted as a current population estimate.

## Tools
- QGIS
- Spatial data processing and attribute-table joins
- Field Calculator and graduated map symbology
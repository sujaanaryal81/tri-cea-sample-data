# Biophysics Data

Environmental and physical variables relevant to siting and operating CEA systems (greenhouses, vertical farms).

## Subfolders
- weather/ - temperature, precipitation, climate data by county
- sunlight-exposure/ - solar irradiance and daylight hour data by county
- water/ - water availability, access, and quality data by county
- soil-site/ - soil quality, terrain, and site suitability data

## Status
Data collection in progress. Spatial and GIS versions of this data are maintained separately and are not duplicated here.

## External data source: CEAOD

Controlled-environment agriculture crop-trial data (greenhouse & vertical farm)
is not stored in this repo. It comes from the **Controlled Environment
Agriculture Open Data (CEAOD)** project and can be accessed directly:

- Source repository: https://github.com/CEAOD/Data
- Download / browse: https://ceaod.github.io/download/
- Project home: https://ceaod.github.io/

To pull it locally, run `scripts/fetch_ceaod.sh` (see repo root).
Please cite each dataset per its own README; licenses vary by dataset.

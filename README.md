# Common Analysis Part 1

## Goals 
The goal of this project was to collect wildfire and AQI data to analyze the effect wildfires have on AQI. 

## Relevant API Documentation

- [EPA Colab File]([https://www.mediawiki.org/wiki/API:Main_page](https://colab.research.google.com/drive/1bxl9qrb_52RocKNGfbZ5znHVqFDMkUzf))
- [Wildfire GEO Approximation](https://colab.research.google.com/drive/1qNI6hji8CvDeBsnLDAhJXvaqf2gcg8UV)
## Requirements
Need Python installed on the system with pandas, json, time, and requests, sklearn, math, collections, and matplotlib installed as libraries. 

## Data Files

- `gaseous_aqi_data.json`: Contains data related to gaseous AQI indicators from the US EPA, specifically relating to Larimer County 
- `particulate_aqi_data.json`:  Contains data related to particulate AQI indicators from the US EPA, specifically relating to Larimer County 

## Known Issues and Special Considerations

1. The wildfire data pulled from the USGS was combined with multiple other datasets, mistakes could be present. 
2. Poor correlation was found between my wildfire severity index and the real AQI measurements. 

## Additional Resources

- [USGS Wildfire Data Source](https://www.sciencebase.gov/catalog/item/61aa537dd34eb622f699df81)
- [More Information on Wildfire Smoke](https://www.epa.gov/air-quality/wildfires-and-smoke)

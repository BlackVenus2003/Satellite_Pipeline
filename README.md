# Satellite Data Pipeline

## Overview
This project automates the processing of satellite imagery and GeoTIFF files to extract key metadata and generate summaries. It is designed to simplif>


## Features
- Automates the download and processing of satellite imagery and GeoTIFF files.
- Extracts metadata such as coordinates, date, and time from GeoTIFF files.
- Generates structured reports summarizing processed data.
- Organizes data into raw, processed, and reports directories.

## Project Structure
- `data_pipeline.sh`: Main script for automating data processing.
- `raw_data/`: Directory for storing raw satellite imagery and GeoTIFF files.
- `processed_data/`: Directory for processed data outputs.
- `reports/`: Directory for generated metadata summaries.

### **Usage**
```markdown
## Usage
1. Add the URLs of the satellite imagery and GeoTIFF files in the `data_pipeline.sh` script.
2. Run the script as shown in the setup instructions.
3. Open the `reports/summary.txt` file to view extracted metadata.

---

## Dependencies
- **Shell Scripting**: Required to execute the automation script.
- **Python 3**: Used for processing GeoTIFF metadata.
  - Required library: `rasterio`
- **Image Viewer**: To view processed images (`eog` or equivalent).


## Acknowledgments
- Data sources: NASA Earth Observing System Data and Information System (EOSDIS).
- Tools: Rasterio library for GeoTIFF processing.




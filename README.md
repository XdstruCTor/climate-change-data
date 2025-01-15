# **Geospatial Data Processing and Visualization**

This project focuses on processing, merging, and visualizing geospatial raster data using Python and the `rasterio` library. The workflow includes extracting data from compressed files, merging multiple raster files into a mosaic, and visualizing the results for specific geographic regions. The project is designed to analyze climate and emissions-related datasets, such as methane emissions, and provide insights into regional data.

---

## **Project Overview**

The notebook performs the following tasks:
1. **Data Preparation**: Extracts geospatial data from ZIP files and prepares it for processing.
2. **Data Merging**: Combines multiple raster files into a single mosaic using `rasterio`.
3. **Data Visualization**: Visualizes the merged raster data for specific regions (e.g., Democratic Republic of the Congo) using Matplotlib.
4. **Metadata Inspection**: Extracts and inspects metadata such as Coordinate Reference System (CRS), bounds, and layer counts.
5. **Regional Analysis**: Focuses on specific regions (e.g., Lubumbashi) by extracting and analyzing data within defined bounding boxes.
6. **Second Dataset Processing**: Repeats the workflow for a second dataset (methane emissions) to enable comparative analysis.

---

## **Key Features**
- **Geospatial Data Processing**: Combines multiple raster files into a unified mosaic for large-scale analysis.
- **Visualization**: Uses Matplotlib and `rasterio.plot.show` to create detailed visualizations of raster data.
- **Cloud Integration**: Leverages Google Colab and Google Drive for seamless data storage and processing.
- **Regional Focus**: Extracts and analyzes data for specific regions using bounding box techniques.
- **Metadata Extraction**: Inspects and utilizes metadata (e.g., CRS, bounds) to ensure accurate data interpretation.

---

## **Technologies Used**
- **Python**: Primary programming language for data processing and analysis.
- **Rasterio**: Library for reading, writing, and manipulating geospatial raster data.
- **Matplotlib**: Used for creating visualizations of raster data.
- **Pandas**: Enables data manipulation and analysis in tabular form.
- **Google Colab**: Cloud-based environment for running the notebook and integrating with Google Drive.

---

## **Workflow**
1. **Install Dependencies**: Install required libraries such as `rasterio`.
2. **Mount Google Drive**: Access datasets stored in Google Drive.
3. **Extract Data**: Unzip compressed files to access raster data.
4. **Merge Raster Files**: Combine multiple raster files into a single mosaic.
5. **Visualize Data**: Plot the merged raster data using Matplotlib.
6. **Inspect Metadata**: Extract and analyze metadata (e.g., CRS, bounds).
7. **Regional Analysis**: Focus on specific regions by defining bounding boxes and extracting data.
8. **Process Second Dataset**: Repeat the workflow for a second dataset (methane emissions).

---

## **Code Structure**
- **Import Libraries**: Import necessary Python libraries for data processing and visualization.
- **Install Rasterio**: Install the `rasterio` library and its dependencies.
- **Mount Google Drive**: Connect Google Drive to access datasets.
- **Extract Data**: Unzip and list extracted files.
- **Merge Raster Files**: Combine raster files into a mosaic and save the output.
- **Visualize Data**: Plot the merged raster using Matplotlib.
- **Inspect Metadata**: Print metadata such as CRS and bounds.
- **Regional Analysis**: Extract and visualize data for specific regions (e.g., DRC, Lubumbashi).
- **Process Second Dataset**: Repeat the workflow for a second dataset.

---

## **Usage**
1. Open the notebook in Google Colab or a local Jupyter environment.
2. Mount Google Drive to access the datasets.
3. Run the cells sequentially to install dependencies, process data, and generate visualizations.
4. Modify the bounding box coordinates to focus on different regions of interest.

---

## **Datasets**
- **Primary Dataset**: Global Historical Climatology Network Daily (GHCN-Daily) Version 3.2.
- **Secondary Dataset**: Methane Emissions Data (fossil fuel-related, 1999).

Documentation for the datasets can be found here:
- [GHCN-Daily Documentation](https://catalog.data.gov/dataset/global-historical-climatology-network-daily-ghcn-daily-version-3-2)
- [Methane Emissions Documentation](https://earth.gov/ghgcenter/data-catalog/tm54dvar-ch4flux-monthgrid-v1)

---

## **Results**
- Merged raster files for large-scale analysis.
- Visualizations of geospatial data for specific regions (e.g., DRC, Lubumbashi).
- DataFrames containing extracted raster data for further analysis.

---

## **Contributing**
Contributions are welcome! If you'd like to improve this project, please:
1. Fork the repository.
2. Create a new branch for your changes.
3. Submit a pull request with a detailed description of your improvements.

---

## **License**
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## **Contact**
For questions or feedback, please reach out to [Your Name] at [Your Email].

---

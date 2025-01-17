# Temperature Anomaly Analysis

This notebook analyzes temperature anomaly data from the NOAA GlobalTemp dataset.

## Description

The notebook performs the following steps:

1. Imports necessary libraries, including `netCDF4` and `pandas`.
2. Loads the NOAA GlobalTemp dataset using `netCDF4.Dataset`.
3. Extracts the temperature anomaly data and latitude/longitude information.
4. Subsets the data to a specific region of interest defined by latitude and longitude boundaries.
5. Converts the subsetted data into a pandas DataFrame for further analysis.

## Usage

To run this notebook, you will need to have the following installed:

- Python 3.x
- netCDF4 library (install with `pip install netCDF4==1.6.3`)
- pandas library (install with `pip install pandas==2.0.3`)

1. Download the NOAA GlobalTemp dataset (e.g., `NOAAGlobalTemp_v5.0.0_gridded_s188001_e202212_c20230108T133308.nc`) and place it in your working directory or provide the correct path to the file.
2. Open the notebook in Google Colab or a Jupyter Notebook environment.
3. Execute the cells in the notebook sequentially.

## Data Source

The data used in this notebook is from the NOAA GlobalTemp dataset, which can be downloaded from the NOAA website.

## Output

The notebook generates a pandas DataFrame containing the subsetted temperature anomaly data for the specified region of interest. This DataFrame can be used for further analysis, such as plotting, statistical analysis, and modeling.
# Earthquake-Analysis

This repository contains PySpark code for processing earthquake data. The code reads earthquake data from a CSV file, performs various transformations and analyses using PySpark, and visualizes the results on a world map using Folium.

### Requirements

- Operating System: Ubuntu
- Python IDE: Jupyter Notebook
- Python Libraries:
  - PySpark
  - Folium
  - Pandas

### Installation

1. Install PySpark: Follow the instructions on the [official PySpark documentation](https://spark.apache.org/docs/latest/api/python/getting_started/install.html) to install PySpark.
2. Install Folium: Run `pip install folium` to install the Folium library.
3. Install Pandas: Run `pip install pandas` to install the Pandas library.

### Usage

1. Clone the repository or download the code files.
2. Open Jupyter Notebook on your Ubuntu system.
3. Load and run the provided Jupyter Notebook containing the PySpark code.
4. Ensure that the `database.csv` file is present in the same directory as the notebook.
5. Execute each cell in the notebook to perform data processing and visualization steps.
6. The processed data will be saved as CSV files in the `processed_data` directory.
7. The earthquake map visualization will be saved as an HTML file named `earthquake_map.html`.

### Code Overview

- The PySpark code reads earthquake data from a CSV file and processes it.
- It performs transformations such as concatenating date and time columns, converting data types, and filtering earthquake records.
- Magnitudes are categorized into levels (Low, Moderate, High) using a user-defined function (UDF).
- The code calculates the distance of each earthquake from the reference location (0, 0).
- Results are visualized on a world map using Folium, with each earthquake represented as a marker.
- Processed data is saved as CSV files, and the earthquake map is saved as an HTML file for further analysis and visualization.

### File Structure

- `ReadMe.md`: This file containing project information and usage instructions.
- `earthquake_analysis.ipynb`: Jupyter Notebook containing the PySpark code for earthquake data processing.
- `database.csv`: Sample CSV file containing earthquake data.
- `processed_data/`: Directory containing processed data CSV files.
- `earthquake_map.html`: HTML file containing the earthquake map visualization.

### Authors

- Abhinav Rai



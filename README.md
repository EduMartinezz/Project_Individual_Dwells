# GPS Data Analysis For Individual Dwell

This repository contains code for find Individual Dwells from GPS data using K-Means and DBSCAN algorithms for clustering and Individual Dwell estimation, as well as performing analysis on the clustered data.

## Purpose

The purpose of this repository is to analyse and visualize of GPS data.The code is designed to process GPS data, estimate dwell periods, and create insightful visualizations to understand user behavior and spatial patterns.

### Dependencies

To run the code in this repository, you will need:
- Python 3

**Install Dependencies:**
Ensure you have the required dependencies installed. If not, install them using:
- Jupyter Notebook or any Python IDE (e.g., PyCharm, VSCode)
- Required Python packages:
  - pandas
  - numpy
  - scikit-learn
  - matplotlib
  - seaborn
  - geopandas

You can install the required packages using pip:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn geopandas

**Files**

1. GPS_Dwell_Codes.ipynb: Jupyter Notebook containing the main code for GPS data analysis and visualization.

2. (https://gps-london.s3.eu-west-2.amazonaws.com/gps.csv): link to download GPS data in CSV format. You can replace this file with your own GPS data.

3. **Run the Jupyter Notebook:**

   Open and run the GPS_Dwell_Codes.ipynb notebook using Jupyter.

4. **Replace GPS Data:**

   Replace the sample gps.csv file with your own GPS data in CSV format. Ensure your data has the columns: `user_id`, `datetime`, `lat`, `lon`.

5. **Execute the Notebook:**

   Execute each cell in the Jupyter Notebook to perform data analysis and generate visualizations.

## Additional Information

The GPS_Dwell_Codes.ipynb notebook contains detailed comments and explanations for each code section.

**License**

This code is provided under the [MIT License](LICENSE).


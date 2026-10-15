Air Pollution Analysis: Lucknow

An analysis of air quality in Lucknow, India, covering data cleaning, cross-checking of monitoring stations, and weather normalisation of pollutant readings.

Project Overview

Air pollution readings are noisy: stations report missing values, sensors disagree with each other, and weather conditions (wind, temperature, humidity, rainfall) strongly influence pollutant levels. This project works through those problems step by step to get a cleaner picture of Lucknow's air quality.

Notebooks
Notebook	What it does
lucknow_cleaning.ipynb	Cleans the raw air quality data: handles missing values, fixes formats and timestamps, and removes outliers.
station_crosscheck.ipynb	Compares readings across monitoring stations to check consistency and spot unreliable sensors.
weather_normalisation.ipynb	Adjusts pollutant levels for weather effects so that long-term trends are easier to see.

Run them in the order listed above.

Data
Source: [add the data source here, e.g. CPCB / OpenAQ / Kaggle, with a link]
Pollutants: [e.g. PM2.5, PM10, NO2, SO2, CO, O3]
Period covered: [e.g. Jan 2020 to Dec 2023]
Stations: [number of stations in Lucknow]

The raw data is not included in this repository. Download it from the source above and place it in the same folder as the notebooks.

Tools and Libraries
Python 3
pandas, NumPy
Matplotlib / Seaborn
scikit-learn (for weather normalisation, if used)
Jupyter Notebook

Install the dependencies with:

bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
How to Run
Clone the repository:
bash
   git clone https://github.com/khushi78vaish/Air_pollution_lucknow.git
   cd Air_pollution_lucknow
Add the data file(s) to this folder.
Start Jupyter and open the notebooks in order:
bash
   jupyter notebook
Key Findings
[Finding 1, e.g. PM2.5 levels peak in the winter months]
[Finding 2, e.g. Station X reported readings inconsistent with its neighbours]
[Finding 3, e.g. After weather normalisation, the underlying trend shows ...]
Author

Khushi Vaish GitHub: khushi78vaish

# Neris River Water Quality Analysis

## Overview
This project analyzes time-series data from the Neris River in Lithuania to understand water quality dynamics. Key goals include identifying seasonal trends, handling missing data, and exploring relationships between water quality indicators.

## Data
Data was obtained from the Lithuanian State Monitoring dataset: [Upių valstybinio monitoringo duomenys](https://data.gov.lt/datasets/2075/). The dataset includes the following parameters:

- Water temperature (`vandens_temp`)  
- Dissolved oxygen (`deguon_istirpes`)  
- pH (`ph`)  
- Alkalinity (`sarmingumas`)  
- Electrical conductivity (`elektr_laidis`)  
- Dissolved substances (`suspend_medziagos`)  

## Key Findings
- Water temperature peaks in summer, while dissolved oxygen is higher in colder months (correlation ~ –0.73).  
- Alkalinity and electrical conductivity are strongly positively correlated (0.72–0.79).  
- pH and alkalinity show a moderate positive correlation (0.30–0.33).  
- Dissolved substances show noisy seasonal patterns, often peaking in late spring–summer.

## Usage
1. Clone the repository:
git clone https://github.com/Viktorija-L/Neris-River-Water-Quality-Analysis.git
2. Install dependencies:
pip install -r requirements.txt
Open and run the Jupyter notebooks using VS Code with the Anaconda 3 kernel.

Libraries Used
pandas

matplotlib

seaborn

matplotlib.dates

sklearn.preprocessing.MinMaxScaler

License
This project is released under the MIT License.

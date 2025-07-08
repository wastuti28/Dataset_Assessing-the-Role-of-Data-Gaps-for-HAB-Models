# Assessing the Role of Data Gaps on Harmful Algal Bloom (HAB) Prediction Models for Inland Lakes

**Data Aggregation**

Meteorological and water quality data collected from all lakes have varying temporal resolutions. For example, water quality data in Utah Lake were obtained from five monitoring stations, each with different sampling frequencies.

| No | Station ID | Station Name |
|--------|--------|--------|
| 1 | 4917500 | Utah Lake 3 Mile WNW of Lincoln Beach |
| 2 | 4917310 | Utah Lake 0.5 mi West of Geneva Discharge #15-A |
| 3 | 4917365 | Utah Lake 2 Mile West of Vineyard, UT |
| 4 | 4917370 | Utah Lake 1 Mile East of Pelican Point |
| 5 | 4917600 | Utah Lake Goshen Bay Southwest End | 

<img width="409" height="524" alt="Image" src="https://github.com/user-attachments/assets/17408166-dbfe-4391-9049-e1d7d18a354d" />
 
In Utah Lake, temporal resolution of the water quality data differs by parameter. Total nitrogen (TN) and total phosphorus (TP) were sampled a monthly from March or April to November, while chlorophyll-a (Chl-a) was measured monthly from May to November. In contrast, meteorological data were collected at a finer temporal resolution, either daily or hourly.
To create a representative dataset for Utah Lake, water quality measurements from the five monitoring stations were averaged for each time step. This spatial aggregation provides a lake-wide estimate of key parameters (e.g., nutrient concentrations, turbidity, dissolved oxygen), supporting system-level modeling of processes such as algal bloom dynamics. Monthly values were then derived by summing (for precipitation) or averaging all available observations within each calendar month. This approach aligns with standard practices in lake modeling and long-term trend analysis, where spatial aggregation helps reflect overall system behavior.

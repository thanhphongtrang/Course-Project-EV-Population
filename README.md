# Washington State EV Population Analysis 🚗⚡

## Project Overview

This project conducts an exploratory data analysis (EDA) of the Electric Vehicle (EV) population in Washington State. The goal is to understand the landscape of EV adoption, identify key trends, and uncover patterns related to vehicle makes, models, types, and geographical distribution. The analysis leverages **Python** with the **pandas** and **numpy** libraries for data wrangling and **matplotlib** and **seaborn** for visualization.

---

## Dataset

* **Source:** [data.wa.gov - Electric Vehicle Population Data](https://data.wa.gov/Transportation/Electric-Vehicle-Population-Data/f6w7-q2d2)
* **Description:** This dataset contains all currently registered Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) in Washington State. It is updated regularly and provides a comprehensive look at the state's EV fleet.

### Key Attributes
* `County`, `City`, `Postal Code`: Geographic location of the registered vehicle.
* `Model Year`: The year of the vehicle model.
* `Make`, `Model`: The manufacturer and specific model of the vehicle.
* `Electric Vehicle Type`: Categorizes vehicles as either Battery Electric Vehicle (BEV) or Plug-in Hybrid Electric Vehicle (PHEV).
* `Electric Range`: The vehicle's electric range in miles.
* `Base MSRP`: The manufacturer's suggested retail price for the vehicle's base model.
* `Legislative District`: The legislative district associated with the vehicle's registration.

---

## Analysis Summary

The analysis, detailed in the `ev_washington_analysis.ipynb` notebook, follows these steps:

1.  **Data Loading and Cleaning:**
    * Loaded the dataset using pandas.
    * Performed an initial inspection to understand data types and structure.
    * Handled missing values, noting that `Electric Range` and `Base MSRP` had some zero values that required interpretation.

2.  **Exploratory Data Analysis (EDA):**
    * **EV Growth Over Time:** Analyzed the number of EVs registered by model year, showing a clear exponential increase in recent years.
    * **Geographic Distribution:** Identified the counties and cities with the highest concentration of EVs. **King County** overwhelmingly leads in adoption.
    * **Vehicle Popularity:** Determined the most popular EV makes and models. **TESLA** is the dominant make, with the **MODEL Y** and **MODEL 3** being the most common models.
    * **BEV vs. PHEV:** Visualized the split between Battery Electric Vehicles and Plug-in Hybrids, showing BEVs are significantly more common.
    * **Range and Price Analysis:** Investigated the distributions of electric range and MSRP, observing the market landscape for different vehicle capabilities and price points.

3.  **Key Findings & Insights:**

    * **Exponential Growth:** EV adoption in Washington has accelerated dramatically, especially from 2017 onwards.
    * **Geographic Concentration:** EV ownership is heavily concentrated in the Puget Sound region, with King, Snohomish, and Pierce counties accounting for the vast majority of vehicles.
    * **Market Domination:** Tesla holds a commanding market share in Washington's EV landscape.
    * **BEVs are the Preference:** Consumers in Washington strongly prefer fully electric vehicles (BEVs) over plug-in hybrids (PHEVs).

---

## How to Run This Project

1.  Clone or download the repository.
2.  Ensure you have Python, Jupyter Notebook, pandas, numpy, matplotlib, and seaborn installed.
3.  Place the downloaded `Electric_Vehicle_Population_Data.csv` file in the `data/` directory.
4.  Navigate to the `notebooks/` directory.
5.  Open and run the `ev_washington_analysis.ipynb` notebook to see the full analysis.

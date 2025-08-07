An Analysis of the Electric Vehicle Market in Washington State
Overview
This project presents a comprehensive data analysis of the electric vehicle (EV) population in Washington State. The goal is to explore key trends, identify market leaders, and understand the geographical distribution of EVs using Python and its core data science libraries: pandas, numpy, matplotlib, and seaborn. This analysis serves as a demonstration of a complete data analysis workflow, from data acquisition and cleaning to exploratory data analysis and insight generation, structured as a formal course project.

The analysis delves into the growth of EV adoption over time, the market share of different manufacturers and models, the geographic concentration of EVs across counties, and the evolution of EV technology, particularly in electric range.

Data Source
The dataset used for this analysis is the "Electric Vehicle Population Data" provided by the State of Washington. It is a publicly available dataset sourced from the official U.S. Government open data portal, Data.gov. The dataset is updated regularly and contains records for all Battery Electric Vehicles (BEVs) and Plug-in Hybrid Electric Vehicles (PHEVs) currently registered in Washington State.

Dataset Link:(https://catalog.data.gov/dataset/electric-vehicle-population-data)

Source Provider: Washington State Department of Licensing

Data.gov Reference: The use of official government data ensures a high degree of relevance and provides a basis for real-world analysis, a practice encouraged for developing robust data skills.

Key Findings
Accelerated Growth: The adoption of electric vehicles in Washington State has seen exponential growth, with a significant inflection point around 2018. The cumulative number of EVs on the road continues to rise sharply.

Market Dominance: The market is heavily dominated by a few key players. Tesla stands out as the clear market leader, with its Model Y and Model 3 being the two most registered EV models in the state by a significant margin.

Geographic Concentration: EV ownership is not evenly distributed across the state. King County, the most populous county, accounts for over half of all registered EVs, indicating a strong correlation between urbanization and EV adoption.

Technological Advancement: There is a clear trend of improving EV technology over time. The average electric range of vehicles has steadily increased with each model year, and Battery Electric Vehicles (BEVs) are significantly more prevalent than Plug-in Hybrid Electric Vehicles (PHEVs), making up over 75% of the EV population.

File Structure
Test_2/
│
├── data/
│   └── Electric_Vehicle_Population_Data.csv
│
├── EV_Population_Analysis.ipynb
├── README.md
├── requirements.txt
└──.gitignore


-   **`data/`**: Contains the raw dataset file.
-   **`EV_Population_Analysis.ipynb`**: The Jupyter Notebook with the complete Python code, analysis, and visualizations.
-   **`README.md`**: This file, providing an overview of the project.
-   **`requirements.txt`**: A list of Python libraries required to run the analysis.
-   **`.gitignore`**: A standard file to exclude unnecessary files from version control.

## Technical Requirements

This project was developed using Python 3.9. The analysis depends on several key libraries, which are listed in the `requirements.txt` file.

-   `pandas`
-   `numpy`
-   `matplotlib`
-   `seaborn`
-   `jupyterlab`

## Execution Instructions

To reproduce this analysis, please follow these steps:

1.  **Clone the Repository:**
    ```bash
    git clone [https://github.com/thanhphongtrang/Test_2.git](https://github.com/thanhphongtrang/Test_2.git)
    cd Test_2
    ```

2.  **Set Up a Virtual Environment (Recommended):**
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
    ```

3.  **Install Dependencies:**
    ```bash
    pip install -r requirements.txt
    ```

4.  **Launch Jupyter Notebook:**
    ```bash
    jupyter lab
    ```

5.  Open and run the `EV_Population_Analysis.ipynb` notebook to see the full analysis.

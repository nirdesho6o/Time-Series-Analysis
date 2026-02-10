# Time Series Analysis and Fault Detection

This repository contains a collection of Jupyter Notebooks for exploring and analyzing time series data. The primary focus is on air quality data and electricity consumption.

## Notebooks

### 1. Exploratory Data Analysis (`Exploratory_Data_Analysis.ipynb`)
-   **Dataset**: Beijing Air Quality Data (PRSA Data) from the UCI Machine Learning Repository.
-   **Description**: This notebook performs exploratory data analysis (EDA) on the PRSA dataset. It includes data loading, cleaning, parsing dates, and visualizing various air quality metrics (PM2.5, PM10, SO2, NO2, CO, O3) over time.

### 2. Handling Missing Values (`Handling_Missing_Value.ipynb`)
-   **Dataset**: Beijing Air Quality Data (PRSA Data).
-   **Description**: This notebook demonstrates techniques for identifying and handling missing values in the PRSA dataset. It explores the extent of missing data and potential strategies for imputation or removal.

### 3. Moving Averages (`Moving_Averages.ipynb`)
-   **Dataset**: Electricity Consumption Data (`electricity_consumption.csv`).
-   **Description**: This notebook focuses on time series smoothing using moving averages. It calculates simple moving averages to identify trends and patterns in electricity consumption data.

## Getting Started

### Prerequisites
To run these notebooks, you will need the following Python libraries:
-   `pandas`
-   `numpy`
-   `matplotlib`
-   `seaborn`
-   `download`
-   `tqdm`

You can install them using pip:

```bash
pip install pandas numpy matplotlib seaborn download tqdm
```

### Running the Notebooks
1.  Clone this repository.
2.  Navigate to the project directory.
3.  Start Jupyter Notebook:

```bash
jupyter notebook
```

4.  Open the desired notebook (`.ipynb` file) to view and run the analysis.

## Data Sources
-   **Beijing Air Quality Data**: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Beijing+Multi-Site+Air-Quality+Data)
-   **Electricity Consumption Data**: Srivatsan88's GitHub Repository (https://github.com/srivatsan88/YouTubeLI)

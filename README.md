# Data-Analysis-with-Ydata-Profile-Tunisia-Air-Case-Study
### Overview
The purpose of this project is to explore and understand the Tunisair dataset using data profiling techniques. This involves identifying missing values, correlations, outliers, and unusual patterns in the data. The scope of this project is limited to data exploration and profiling of the Tunisair dataset using ydata-profiling and pandas libraries. The problem addressed by this project is the need to understand the characteristics and quality of the Tunisair dataset, which is essential for any subsequent data analysis, modeling, or machine learning tasks.

### Key Features
- Data profiling and exploratory analysis of the [Tunisiair dataset].
- Automated report generation using **ydata-profiling**.
- Insights and visualizations for key metrics.

### Dataset
Details about the dataset:
- Source: provided in the class
- Description: The structure of the dataset is such that it has 107,833 entries, 9 Columns, a RangeIndex and 1 column (Arrival delay) with Float64 datatype while the other columns are Object data type
Column Names
1. Flight_date: The date on which the flight took place.
2. Flight_ID: A unique identifier for each flight.
3. Departure point: The airport or location from which the flight departed.
4. Arrival point: The airport or location at which the flight arrived.
5. Scheduled_departure_time: The planned departure time of the flight.
6. Scheduled_arrival_time: The planned arrival time of the flight.
7. STATUS: The status of the flight (e.g., on-time, delayed, cancelled).
8. Aircraft_code: The unique code or identifier for the aircraft used for the flight.
9. Arrival delay: The amount of time by which the flight arrival was delayed.

### Requirements
A list of required libraries or dependencies:
- `pandas`
- `ydata-profiling`
- `numpy`
  
### How to Run
1. Clone this repository:  
   ```bash
   git clone <repo-url>
   cd <repo-folder>
   ```
2. Install dependencies:  
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook:  
   ```bash
   jupyter notebook ydata-profiling-checkpoint-2-Tunisiair.ipynb
   ```

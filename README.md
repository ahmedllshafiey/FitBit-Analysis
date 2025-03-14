# Bellabeat Analysis

## Project Overview

The Bellabeat Analysis project is a data analysis initiative aimed at exploring and understanding user activity data collected from fitness devices. The goal is to derive insights into user behavior, activity patterns, and overall health metrics.

## Dataset

The analysis uses the `Daily_Activity.csv` dataset, which contains the following key columns:

- `Id`: Unique identifier for each user.
- `ActivityDate`: Date of the activity.
- `TotalSteps`: Total steps taken by the user.
- `LightActiveDistance`: Distance covered during light activity.
- `SedentaryActiveDistance`: Distance covered during sedentary activity.
- `FairlyActiveMinutes`: Minutes spent in fairly active states.
- `SedentaryMinutes`: Minutes spent in sedentary states.
- `Calories`: Calories burned.

## Key Features of the Analysis

1. **Data Cleaning and Transformation**:

   - Renamed columns for better readability.
   - Converted date columns to datetime format.
   - Added new calculated columns such as `TotalMinutes` and `TotalHours`.

2. **Exploratory Data Analysis (EDA)**:

   - Inspected data structure and types using `df.info()`.
   - Checked for missing values with `df.isnull().sum()`.
   - Generated descriptive statistics using `df.describe()`.

3. **Feature Engineering**:
   - Extracted day names from the `Date` column for weekday analysis.

## Prerequisites

To run the analysis, ensure you have the following Python libraries installed:

- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`

You can install these libraries using pip:

```bash
pip install numpy pandas matplotlib seaborn
```

## How to Run

1. Clone the repository or download the project files.
2. Place the `Daily_Activity.csv` file in the `Database` folder.
3. Open the `Bellabeat.ipynb` notebook in Jupyter Notebook or any compatible IDE.
4. Run the cells sequentially to execute the analysis.

## Results

The analysis provides insights into:

- User activity patterns across different days of the week.
- Relationships between activity levels, sedentary behavior, and calorie burn.
- Total active hours and their distribution.

## Future Work

- Incorporate additional datasets for a more comprehensive analysis.
- Perform advanced visualizations to uncover deeper trends.
- Develop predictive models for user activity and health metrics.

## License

This project is for educational purposes and is not licensed for commercial use.

## Author

Ahmed Sayed

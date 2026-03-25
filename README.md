# Digital Fitness Market Analysis

## Objective
This project analyzes global and national trends in digital fitness classes using Google Trends data. The goal is to understand the popularity of keywords like *workout*, *home workout*, *gym workout*, and *home gym* over time and across countries, to inform potential opportunities in digital fitness products and services.

## Data
The project uses CSV files containing international and national-level Google Trends data:

- `workout.csv` – Monthly worldwide popularity index for the keyword "workout".
- `three_keywords.csv` – Monthly worldwide popularity indexes for "home workout", "gym workout", and "home gym".
- `workout_geo.csv` – Country-level popularity of "workout" (2018–2023).
- `three_keywords_geo.csv` – Country-level popularity of "home workout", "gym workout", and "home gym" (2018–2023).

## Tools & Technologies
- Python
- Pandas (for data manipulation)
- Matplotlib (for visualizations)
- Jupyter Notebook

## Analysis
- Visualized keyword trends worldwide and over time.
- Compared country-level trends to identify regions with high or low interest.
- Observed peak trends during COVID for home workouts.
- Provided insights into opportunities for digital fitness products and services.

## How to Run
1. Install the required Python packages:

```bash
pip install pandas matplotlib jupyter
Open the Jupyter Notebook:
jupyter notebook
Open analysis.ipynb and run all cells.

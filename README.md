# Vessel Analysis Programming Challenge
## Overview

This repository contains the solution to the **Freight Data Programming Challenge: Vessel Analysis**, which involves analyzing maritime vessel data across various dimensions such as speed, draft, vessel class, cargo, and geographic activity. 

The challenge includes multiple data analysis tasks using standard Python data libraries, with the goal of producing actionable insights into vessel operations.

##  Repository Contents

- `programming_challenge.ipynb`: Main Jupyter notebook containing all code, analysis, visualizations, and insights.
- `README.md`: This file — documentation for understanding the project and instructions for running it.
- Includes a `requirements.txt`

## Objective

The purpose of this challenge is to:
- Load and clean real-world vessel tracking and characteristic data.
- Explore operational trends in vessel speed, draft, and status.
- Classify vessels by DWT (Deadweight Tonnage).
- Perform cargo and geographical analyses to determine trends and identify key operators.
- Derive relationships between AIS draft data and vessel characteristics to infer cargo loading status.

  ## Technologies Used

- Python 3.13
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- shapely

1. **Data Loading and Cleaning**
   - Loaded `vessel_positions.csv` and `vessel_characteristics.csv`.
   - Handled missing values and verified data types.
   - Removed or corrected erroneous data points.

2. **Exploratory Analysis**
   - Explored relationships between vessel operational status, speed (`ais_speed`), draft (`ais_draft`), and operational_status

3. **Vessel Classification**
   - Added a new column `vessel_class` based on DWT.
   - Visualized the distribution of vessel classes.

4. **Cargo Analysis**
   - Analyzed correlation between vessel class and `vessel_commodity_group_onboard`.

5. **Geographical Analysis**
   - Defined a polygon representing Southeast Asia.
   - Identified vessels operating within this region and plotted their positions on a map.

6. **Integrated Insights**
   - Identified vessels loading cargo in Southeast Asia between Aug 20–24, 2024.
   - Analyzed top exports by country, cargo destinations, and most active operators.
   - Compared AIS-reported draft to vessel-design draft to infer loading activity.

## Getting Started

To get started with this project, all you need to do is clone the repository and run the notebook. Follow the steps below:

### 1. Clone the repository:
```bash
git clone https://github.com/Abdullah-Shahid01/Freight-Data-Programming-Challenge.git
cd Freight-Data-Programming-Challenge
```
### 2. Open the notebook:
Open the `programming_challenge.ipynb` file using your preferred environment

### 3. Run the code:
Run all cells in the notebook sequentially from top to bottom. The notebook contains:

- Data loading and cleaning
- Exploratory and statistical analysis
- Visualizations and maps
- Final insights and summary

No additional setup is required.
  

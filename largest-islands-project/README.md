
# Largest Islands — Data Analysis Project

## Project Overview

This project explores a dataset of the 100 largest islands in the world using Python.

The goal is to analyze island sizes, geographic regions, tropical islands, and islands shared by multiple countries or territories.

The analysis uses Pandas for data manipulation and Matplotlib for data visualization.

## Dataset Description

The dataset contains 100 islands and six columns:

- **region:** Geographic region where the island is located.
- **island:** Name of the island.
- **area:** Island area in square kilometers (km²).
- **countries:** Countries or territories associated with the island.
- **climate:** Climate classification of the island.
- **rank:** Worldwide ranking based on island area.


## Analysis Questions

This project addresses four main questions:

1. What are the 10 largest islands in the tropics?
2. What are the largest islands in each geographic region?
3. How does island area change according to worldwide ranking?
4. Which islands are shared by multiple countries or territories?


## Key Findings

### 1. Largest Tropical Islands

New Guinea is the largest tropical island in the dataset, with an area of 821,400 km².

Borneo ranks second with 755,000 km², followed by Madagascar with 591,896 km².

### 2. Largest Islands by Region

The analysis identified the largest island in each of the eight geographic regions represented in the dataset.

Greenland is the largest island overall, with an area of 2,166,086 km².

### 3. Island Area vs. World Ranking

The line chart shows that island area decreases sharply among the highest-ranked islands and then declines more gradually.

This indicates that the largest islands are significantly bigger than most other islands in the dataset.

### 4. Islands Shared by Countries or Territories

The analysis identified seven records containing multiple country or territory names.

Examples include Borneo, Hispaniola, New Guinea, and Ireland.


## Technologies Used

The following technologies were used in this project:

- **Python:** Programming language used for data analysis.
- **Pandas:** Library used for data loading, filtering, sorting, and grouping.
- **Matplotlib:** Library used to create data visualizations.
- **Jupyter Notebook:** Interactive environment used to write and execute Python code.
- **Visual Studio Code:** Code editor used to develop the project.
- **Git and GitHub:** Tools used for version control and project publication.



## How to Run the Project

1. Download or clone this repository.
2. Open the `largest-islands-project` folder in Visual Studio Code or Jupyter Notebook.
3. Make sure Python and the required libraries are installed.
4. Open `largest-islands.ipynb`.
5. Select a Python kernel and run the notebook cells in order.

### Required Libraries

```bash
pip install pandas matplotlib
```

The dataset is included in the project as `largest-islands.csv`.


## Data Sources and Credits

The dataset used in this project was provided as part of a Data Science learning exercise.

The original dataset references and source information are preserved in the `README.txt` file included in this project.

This repository contains my own data exploration, analysis, visualizations, and conclusions.

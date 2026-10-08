# Seattle Weather Project

> This project uses Python and data science techniques to compare precipitation between Seattle and Spokane, Washington. The goal is to determine whether Seattle actually receives more rain than Spokane by analyzing historical weather data.

---

## Project Overview

Seattle is famous for its rainy weather, but does it really rain more than Spokane? In this project, I use weather data from 2018 to 2022 to compare daily precipitation amounts and the frequency of rainy days in both cities.
The project involves cleaning and organizing the data, creating visualizations, calculating descriptive statistics, and performing statistical tests to identify differences between the two cities.


- **Objective:** Determine whether Seattle receives more precipitation than Spokane.
- **Domain:** Weather and Climate Analysis
- **Key Techniques:** Data Cleaning, Exploratory Data Analysis (EDA), Data Visualization, Descriptive Statistics, Time Series Analysis, and Hypothesis Testing.

---

## Project Structure

```
├── data/                 # Raw and processed data
├── code/                 # Jupyter notebooks and Python scripts
├── reports/              # Generated reports and visualizations
├── requirements.txt      # Dependencies
└── README.md             # Project documentation
```

---

## Data

- **Source:** National Oceanic and Atmospheric Administration (NOAA), National Centers for Environmental Information (NCEI).
- **Description:** The dataset contains daily precipitation observations for Seattle and Spokane from 2018 to 2022. It has 3,590 observations. Format: CSV file.
- **License:** (if applicable)

---

## Analysis

The analysis is performed using Python in a Jupyter Notebook.
The main steps include:
1.	Data Inspection: Load the dataset and examine its structure, columns, and data types.
2.	Data Cleaning: Check for missing values, duplicates, and incorrect data types.
3.	Exploratory Data Analysis: Calculate average daily precipitation and examine precipitation patterns.
4.	Data Visualization: Create line graphs, bar charts, histograms, and boxplots to compare Seattle and Spokane.
5.	Monthly Analysis: Compare precipitation amounts and rainy-day frequency across different months.
6.	Statistical Testing: Use t-tests and proportion tests to determine whether precipitation differences are statistically significant.


---

## Results

The analysis suggests that Seattle receives more precipitation than Spokane.
Average Daily Precipitation: Seattle received approximately 0.114 inches per day, compared with 0.064 inches in Spokane.
Rainy-Day Frequency: Seattle experienced precipitation on approximately more than 50% of days, compared with around 40% in Spokane.
Seasonal Differences: The differences were generally larger during the wetter months, especially in fall and winter.
Statistical Testing: Monthly hypothesis tests identified statistically significant differences during several months of the year.
Overall, the results support the conclusion that Seattle receives more precipitation and experiences rainy days more frequently than Spokane, especially during the wetter months.

---

## Authors

- Linh Chung - [@linhchung21](https://github.com/linhchung21)

---

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## Acknowledgements

- Tools/libraries used: Jupyter Notebook, NOAA, Python Libraries, 
- Tutorials or papers referenced
- Inspiration or collaborators

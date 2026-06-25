# SpaceX Launch Success Prediction & Analysis
### IBM Data Analyst Capstone Project

## Project Overview

This project was completed as part of the **IBM Data Analyst Professional Certificate Capstone Project**. The objective is to analyze historical SpaceX launch data and identify the factors that contribute to successful rocket launches. By exploring launch records, performing data visualization, and applying analytical techniques, the project provides insights into SpaceX's launch performance and mission outcomes.

## Project Goals

- Collect and clean SpaceX launch data
- Explore launch success trends over time
- Analyze how launch site, payload mass, booster version, and orbit type impact mission success
- Visualize key metrics using charts and maps
- Build predictive insights regarding launch outcomes

## Dataset

The dataset contains historical SpaceX launch records and includes:

- Flight Number
- Launch Site
- Payload Mass (kg)
- Booster Version
- Orbit Type
- Mission Outcome
- Launch Date
- Landing Success

### Data Sources

- SpaceX REST API
- Public launch datasets provided through the IBM Capstone Project

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Plotly
- Folium
- Jupyter Notebook
- SQL
- IBM Watson Studio

## Project Workflow

### 1. Data Collection

Data was collected from:

- SpaceX API
- Web scraping techniques
- CSV datasets

### 2. Data Wrangling

Tasks included:

- Handling missing values
- Data cleaning
- Data transformation
- Feature engineering

### 3. Exploratory Data Analysis (EDA)

Analysis focused on:

- Launch success rates
- Payload mass relationships
- Orbit success patterns
- Launch site performance

### 4. Data Visualization

Visualizations created:

- Scatter plots
- Bar charts
- Pie charts
- Interactive maps
- Dashboard reports

### 5. SQL Analysis

SQL queries were used to:

- Retrieve launch statistics
- Compare launch sites
- Analyze booster performance
- Calculate success rates

### 6. Predictive Analysis

Machine learning techniques were applied to:

- Predict launch success
- Evaluate model performance
- Identify influential features

## Key Findings

- SpaceX launch success rates have improved significantly over time.
- Certain launch sites consistently achieve higher success rates.
- Payload mass influences launch outcomes but is not the sole determining factor.
- Reusable boosters contribute to increased mission efficiency.
- Specific orbit types show higher success percentages than others.

## Repository Structure

```text
spacex-capstone-project/
│
├── data/
│   └── spacex_launch_dataset.csv
│
├── notebooks/
│   ├── Data_Collection.ipynb
│   ├── Data_Wrangling.ipynb
│   ├── EDA.ipynb
│   ├── SQL_Analysis.ipynb
│   └── Predictive_Model.ipynb
│
├── dashboard/
│   └── spacex_dashboard.py
│
├── images/
│   └── visualizations/
│
├── presentation/
│   └── Capstone_Presentation.pdf
│
└── README.md
```

## Results

The project demonstrates how data analytics can be used to understand launch success factors and support decision-making in aerospace operations. Through data collection, cleaning, visualization, SQL analysis, and predictive modeling, valuable insights into SpaceX launch performance were identified.

## Future Improvements

- Incorporate real-time SpaceX launch data
- Develop more advanced predictive models
- Expand analysis to include weather conditions
- Create a live dashboard for launch monitoring

## Author

**Jacob Miller**

GitHub: https://github.com/jacobmiller9826

---

*This project was completed as part of the IBM Data Analyst Professional Certificate Program and demonstrates skills in data collection, data wrangling, SQL, visualization, and predictive analytics.*

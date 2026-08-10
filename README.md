# Crime Data Analysis
This is an end-to-end analysis of the crime data from 2020 to present. 

<br><br>

<h3><b>Overview</b></h3>

This project analyzes the Crime Data from 2020 to Present dataset to identify crime patterns, temporal trends, geographic distributions, victim demographics, and other key insights.

The project follows an end-to-end data analytics workflow, from data loading and exploration in Python to SQL analysis in PostgreSQL, interactive dashboard development in Power BI, and presentation of findings through a professional report and Gamma presentation.

Dataset: Crime Data from 2020 to Present

The dataset contains crime records with information related to:

- Crime type and crime code <br>
- Date reported and date occurred <br>
- Time of occurrence <br>
- Area and reporting district <br>
- Premises/location <br>
- Victim age and gender <br>
- Crime status <br>
- Unique crime/DR number <br>

The dataset was cleaned and transformed before analysis to improve data quality and prepare it for visualization and SQL analysis.

Tools & Technologies :- <br>
- Python — Data loading, cleaning, EDA and feature engineering <br>
- Pandas & NumPy — Data manipulation and transformation <br>
- Matplotlib & Seaborn — Exploratory data visualization <br>
- PostgreSQL — SQL-based data analysis <br>
- Power BI — Interactive dashboard and data visualization <br>
- Gamma — Project presentation <br>
- Jupyter Notebook — Python-based analysis and documentation <br><br>
Project Steps
1. Data Loading
Loaded the Crime Data from 2020 to Present dataset into Python.
Examined the dataset structure, columns, data types and dimensions.
2. Exploratory Data Analysis - Performed EDA to understand:<br>
- Dataset structure and distributions
- Missing values
- Duplicate records
- Crime types
- Crime locations
- Victim demographics
- Temporal patterns
- Crime status distribution <br>
3. Data Cleaning - Performed data preprocessing including: <br>
- Handling missing values
- Correcting data types
- Identifying and handling invalid values
- Cleaning date and time fields
- Removing/handling inconsistent records
- Preparing reliable fields for analysis <br>
4. Feature Engineering - Created analytical features such as: <br>
- Clean Date
- Month
- Month Name
- Month Year
- Month Year Sort
- Day of Week
- Day Number
- Crime Hour
- Victim Age Groups <br>
These features were used to improve analysis and Power BI visualizations. <br>

5. PostgreSQL Analysis - Loaded the cleaned dataset into PostgreSQL and performed SQL analysis to answer business and analytical questions related to: <br>
- Crime frequency
- Crime types
- Geographic distribution
- Crime locations
- Victim demographics
- Temporal patterns
- Crime status <br>

6. Power BI Dashboard - Built an interactive Power BI dashboard consisting of multiple analytical pages covering: <br>
- Executive Overview
- Crime Patterns & Geographic Analysis
- Victim Demographic Analysis
- Time Analysis
- Crime Record Details using drill-through functionality <br>
The dashboard includes interactive slicers, KPI cards, charts, matrices and drill-through functionality. <br>

7. Reporting & Presentation - Prepared a detailed analytical report documenting the findings. <br>
Created a professional presentation using Gamma to communicate the key insights and conclusions. <br> <br>

Power BI Dashboard - The Power BI dashboard provides an interactive view of crime patterns across time, geography, crime types, locations and victim demographics. <br><br>

<h3><b> Dashboard Preview </b></h3>  <br>

- Page 1 :- <br> <br>
![image](https://github.com/Joykiran87/crime_data_analysis/blob/75da0a28bd9de3aaf0ba951741f540cd24f89ad0/Screenshot%202026-08-11%20001109.png)
<br><br>
- Page 2 :- <br><br>
![image](https://github.com/Joykiran87/crime_data_analysis/blob/75da0a28bd9de3aaf0ba951741f540cd24f89ad0/Screenshot%202026-08-11%20001208.png)
<br><br>
- Page 3 :- <br><br>
![image](https://github.com/Joykiran87/crime_data_analysis/blob/75da0a28bd9de3aaf0ba951741f540cd24f89ad0/Screenshot%202026-08-11%20001232.png)
<br><br>
- Page 4 :- <br><br>
![image](https://github.com/Joykiran87/crime_data_analysis/blob/75da0a28bd9de3aaf0ba951741f540cd24f89ad0/Screenshot%202026-08-11%20001307.png)
<br><br>

Crime-Data-Analytics/ <br>
│ <br>
├── README.md <br>
├── images/ <br>
│   └── crime-dashboard.png <br>
├── notebooks/ <br>
├── sql/ <rbr>
├── data/ <br>
└── reports/ <br><br>

<b> Key Analysis & Results </b>

The project provides insights into:

- Most frequently reported crime types
- Crime distribution across different areas and reporting districts
- Crime patterns by premises/location
- Crime status distribution
- Crime types across different geographic areas
- Victim age-group distribution
- Victim gender distribution
- Victim demographics across crime types and areas
- Monthly and yearly crime trends
- Crime distribution by month and day of week
- Peak crime periods
- Geographic and temporal crime patterns <br><br>

The interactive dashboard allows users to apply filters and explore these patterns dynamically. <br><br>

<h3><b> How to Run :- </b></h3> 
- Python Analysis <br>
- Clone the repository. <br>
- Install the required Python libraries: <br>
- pip install pandas numpy matplotlib seaborn jupyter <br>
- Place the dataset in the appropriate project directory. <br>
- Open the Jupyter Notebook. <br>
- Run the Python analysis cells sequentially. <br>
- PostgreSQL <br>
- Install PostgreSQL. <br>
- Create a database. <br>
- Load the cleaned dataset into PostgreSQL. <br>
- Run the SQL queries provided in the sql folder. <br>
- Power BI <br>
- Open the .pbix file in Power BI Desktop. <br>
- Update the data source if required. <br>
- Refresh the dataset. <br>
- Use the slicers and interactive visuals to explore the analysis. <br>
- Project Structure  <br> <br>

Crime-Data-Analytics/ <br>
│ <br>
├── data/ <br>
│   └── Crime Data from 2020 to Present <br>
│ <br>
├── notebooks/ <br>
│   └── crime_analysis.ipynb <br>
│ <br>
├── sql/ <br>
│   └── crime_analysis.sql <br>
│ <br>
├── powerbi/ <br>
│   └── crime_analysis_dashboard.pbix <br>
│ <br>
├── reports/ <br>
│   └── crime_analysis_report.pdf <br>
│ <br>
├── presentation/ <br>
│   └── crime_analysis_presentation.pdf <br>
│ <br>
├── images/ <br>
│   └── crime-dashboard.png <br>
│ <br>
└── README.md <br> <br>

<h3><b> Conclusion </b></h3> <br>

This project demonstrates an end-to-end data analytics workflow, combining Python, SQL, PostgreSQL and Power BI to transform raw crime data into meaningful analytical insights and an interactive dashboard. <br>

It showcases practical skills in data cleaning, exploratory data analysis, feature engineering, SQL analysis, data visualization, dashboard development, reporting and data storytelling.

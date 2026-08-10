# Crime Data Analysis
This is an end-to-end analysis of the crime data from 2020 to present. 

<br><br>

<h3><b>Overview</b></h3>

This project analyzes the Crime Data from 2020 to Present dataset to identify crime patterns, temporal trends, geographic distributions, victim demographics, and other key insights.

The project follows an end-to-end data analytics workflow, from data loading and exploration in Python to SQL analysis in PostgreSQL, interactive dashboard development in Power BI, and presentation of findings through a professional report and Gamma presentation.

Dataset

Dataset: Crime Data from 2020 to Present

The dataset contains crime records with information related to:

Crime type and crime code
Date reported and date occurred
Time of occurrence
Area and reporting district
Premises/location
Victim age and gender
Crime status
Unique crime/DR number

The dataset was cleaned and transformed before analysis to improve data quality and prepare it for visualization and SQL analysis.

Tools & Technologies
Python — Data loading, cleaning, EDA and feature engineering
Pandas & NumPy — Data manipulation and transformation
Matplotlib & Seaborn — Exploratory data visualization
PostgreSQL — SQL-based data analysis
Power BI — Interactive dashboard and data visualization
Gamma — Project presentation
Jupyter Notebook — Python-based analysis and documentation
Project Steps
1. Data Loading
Loaded the Crime Data from 2020 to Present dataset into Python.
Examined the dataset structure, columns, data types and dimensions.
2. Exploratory Data Analysis

Performed EDA to understand:

Dataset structure and distributions
Missing values
Duplicate records
Crime types
Crime locations
Victim demographics
Temporal patterns
Crime status distribution
3. Data Cleaning

Performed data preprocessing including:

Handling missing values
Correcting data types
Identifying and handling invalid values
Cleaning date and time fields
Removing/handling inconsistent records
Preparing reliable fields for analysis
4. Feature Engineering

Created analytical features such as:

Clean Date
Month
Month Name
Month Year
Month Year Sort
Day of Week
Day Number
Crime Hour
Victim Age Groups

These features were used to improve analysis and Power BI visualizations.

5. PostgreSQL Analysis

Loaded the cleaned dataset into PostgreSQL and performed SQL analysis to answer business and analytical questions related to:

Crime frequency
Crime types
Geographic distribution
Crime locations
Victim demographics
Temporal patterns
Crime status
6. Power BI Dashboard

Built an interactive Power BI dashboard consisting of multiple analytical pages covering:

Executive Overview
Crime Patterns & Geographic Analysis
Victim Demographic Analysis
Time Analysis
Crime Record Details using drill-through functionality

The dashboard includes interactive slicers, KPI cards, charts, matrices and drill-through functionality.

7. Reporting & Presentation
Prepared a detailed analytical report documenting the findings.
Created a professional presentation using Gamma to communicate the key insights and conclusions.
Power BI Dashboard

The Power BI dashboard provides an interactive view of crime patterns across time, geography, crime types, locations and victim demographics.

Dashboard Preview

Add your Power BI dashboard screenshot below:

![Power BI Crime Analysis Dashboard](images/crime-dashboard.png)

For GitHub, place your screenshot inside your repository, for example:

Crime-Data-Analytics/
│
├── README.md
├── images/
│   └── crime-dashboard.png
├── notebooks/
├── sql/
├── data/
└── reports/

Then the image will appear directly in your README.

Key Analysis & Results

The project provides insights into:

Most frequently reported crime types
Crime distribution across different areas and reporting districts
Crime patterns by premises/location
Crime status distribution
Crime types across different geographic areas
Victim age-group distribution
Victim gender distribution
Victim demographics across crime types and areas
Monthly and yearly crime trends
Crime distribution by month and day of week
Peak crime periods
Geographic and temporal crime patterns

The interactive dashboard allows users to apply filters and explore these patterns dynamically.

How to Run
Python Analysis
Clone the repository.
Install the required Python libraries:
pip install pandas numpy matplotlib seaborn jupyter
Place the dataset in the appropriate project directory.
Open the Jupyter Notebook.
Run the Python analysis cells sequentially.
PostgreSQL
Install PostgreSQL.
Create a database.
Load the cleaned dataset into PostgreSQL.
Run the SQL queries provided in the sql folder.
Power BI
Open the .pbix file in Power BI Desktop.
Update the data source if required.
Refresh the dataset.
Use the slicers and interactive visuals to explore the analysis.
Project Structure
Crime-Data-Analytics/
│
├── data/
│   └── Crime Data from 2020 to Present
│
├── notebooks/
│   └── crime_analysis.ipynb
│
├── sql/
│   └── crime_analysis.sql
│
├── powerbi/
│   └── crime_analysis_dashboard.pbix
│
├── reports/
│   └── crime_analysis_report.pdf
│
├── presentation/
│   └── crime_analysis_presentation.pdf
│
├── images/
│   └── crime-dashboard.png
│
└── README.md
Conclusion

This project demonstrates an end-to-end data analytics workflow, combining Python, SQL, PostgreSQL and Power BI to transform raw crime data into meaningful analytical insights and an interactive dashboard.

It showcases practical skills in data cleaning, exploratory data analysis, feature engineering, SQL analysis, data visualization, dashboard development, reporting and data storytelling.

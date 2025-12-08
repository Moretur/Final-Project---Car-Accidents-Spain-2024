# Final-Project---Car-Accidents-Spain-2024
Final Projet for Ironhack Data Analyst
This repository contains a full data analysis workflow for traffic accidents occurring in Spain in 2024, including data cleaning processes, table creation, visual exploration, and preparation for SQL storage and Power BI visualization.
🗂️ Data Files

The following .csv files contain the core dataset used throughout the project:

ACC_ANIMALES_2024.csv
Original source file containing accident records involving animals.

TABLA_ACCIDENTES_24.csv
General accident table (main raw dataset).

accidentes.csv
Cleaned and structured accident data, created from the original dataset.

ubicacion.csv
Derived table containing standardized location information (city, coordinates, road, etc.).

clima.csv
Derived table with weather conditions present at the moment of each accident.

via.csv
Derived table describing road characteristics (surface type, condition, signage, etc.).

All derived CSVs (accidentes, ubicacion, clima, via) were created after cleaning and preprocessing the original datasets using Jupyter notebooks.

📓 Notebooks

Primer Vistazo.ipynb
Initial data exploration: dataset dimensions, data types, first observations, and detection of null values, duplicates, and outliers.

Análisis.ipynb
In-depth analysis with visualizations, correlations, and data segmentation.

Creación Tablas.ipynb
Notebook used to generate the derived tables (accidentes.csv, ubicacion.csv, clima.csv, via.csv) from the raw dataset.

ConexionSQL.ipynb
Notebook for connecting to an SQL database, creating the relational model, and loading the cleaned tables.

📊 Visualizations

NewVisuals.pbix
Power BI file including dashboards and visual analytics based on the processed dataset.

📄 Other Files

LICENSE
Project license.

README.md
This documentation file.

🚀 Project Goals

Analyze accidents from different perspectives (location, weather, road type, animal involvement, etc.).

Clean, standardize, and structure data for SQL storage and relational modeling.

Create derived datasets to optimize analysis.

Build clear data visualizations to identify patterns, trends, and potential risk factors.

🛠️ Technologies Used

Python 3

Pandas

NumPy

Matplotlib / Seaborn (if applicable)

Jupyter Notebook

SQL

Power BI

CSV data format

📌 Workflow Overview

Data loading and initial exploration
(Primer Vistazo.ipynb)

Cleaning and in-depth analysis
(Análisis.ipynb)

Creation of derived tables
(Creación Tablas.ipynb)

SQL database modeling and insertion
(ConexionSQL.ipynb)

Visual exploration in Power BI
(NewVisuals.pbix)

📄 License

This project is licensed under the terms provided in the LICENSE file.

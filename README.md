# Hotels-Analysis

🐼 Data Analysis Project using Pandas Library
📌 Project Description
This project demonstrates data analysis using the Pandas library in Python.
Multiple datasets are loaded, cleaned, merged, and analyzed to extract meaningful insights related to hotel bookings.

The project follows a real-world analytical approach, working with fact and dimension tables commonly used in data analytics.

🛠️ Technology Used
Python

Pandas Library

Jupyter Notebook

📂 Datasets Used
The following datasets were analyzed using Pandas:

dim_date – Date and calendar-related information

dim_hotels – Hotel master data

dim_rooms – Room and category details

fact_booking – Detailed booking transactions

fact_aggregated_bookings – Aggregated booking metrics

fact_data_august – Booking data for August month

🎯 Objectives
Read multiple datasets using Pandas

Clean and preprocess raw data

Merge fact and dimension tables

Perform exploratory data analysis (EDA)

Generate insights using Pandas operations

🔍 Key Pandas Operations Used
read_csv()

info(), describe()

Handling missing values (isna(), fillna(), dropna())

Data filtering and sorting

groupby() and aggregation

merge() and concat()

Date-time operations

Column creation and transformation

📊 Analysis Highlights
Hotel-wise and city-wise booking analysis

Room category performance evaluation

Monthly and date-based trend analysis

Aggregated booking insights using groupby operations

📁 Project Structure
Pandas-Hotel-Booking-Analysis/
│
├── data/
│   ├── dim_date.csv
│   ├── dim_hotels.csv
│   ├── dim_rooms.csv
│   ├── fact_booking.csv
│   ├── fact_aggregated_bookings.csv
│   └── fact_data_august.csv
│
├── pandas_analysis.ipynb
└── README.md

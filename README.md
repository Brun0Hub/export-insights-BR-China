China Exports Analysis

🎯 Purpose

This script analyzes export data from the file China_Exports.csv to identify:

The total export values by month.

The most exported products across all months.

The cities with the highest export values in March.

The top products exported by the leading city in March.

⚙️ Workflow

Data Cleaning

Strips whitespace from column names and text fields.

Extracts the month name from the Month column.

Monthly Analysis

Aggregates export values (US$ FOB) by month.

Formats values for readability.

Product Analysis

Aggregates export values by product (SH4 Description).

Sorts products by total export value.

City Analysis (March)

Aggregates export values by city for March.

Identifies the city with the highest exports.

Breaks down exports by product for that city.

📊 Outputs

A table of export values by month.

A ranking of the most exported products overall.

A ranking of cities by export value in March.

A ranking of products exported by the top city in March.

🚀 Usage

Place the file China_Exports.csv in the project directory.

Run the script in a Python environment with pandas installed.

The script will display tables using Jupyter Notebook’s display() function.

📦 Requirements

Python 3.x

pandas

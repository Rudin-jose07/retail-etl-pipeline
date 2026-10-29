# retail-etl-pipeline

## What is this project?

This project moves order data from one place to another.

It reads data from an Oracle database, saves a raw copy in Google Cloud Storage, cleans the data with SQL in BigQuery, and loads the cleaned data into a database.

The project also checks that the data was moved correctly.

## Project flow

Oracle database  
→ Google Cloud Storage  
→ BigQuery  
→ Cleaned data  
→ Database  
→ Data checks

## Tools used

- **Oracle:** Stores the starting order data.
- **Google Cloud Storage:** Keeps a copy of the original data files.
- **BigQuery:** Stores and transforms data using SQL.
- **Python:** Moves data and runs project tasks.
- **Airflow:** Runs the project steps in order.
- **GitHub:** Stores the project files and tracks changes.
- **Spanner:** An optional database to try later.

## How I will build it

1. Create practice order data.
2. Save the data in Oracle.
3. Copy the data to Google Cloud Storage.
4. Load the data into BigQuery.
5. Use SQL to clean and change the data.
6. Load the cleaned data into a database.
7. Check row counts and sales totals.
8. Use Airflow to run the steps in order.

## Cost note

I will start with free or local tools where possible.

Cloud Composer and some cloud services may cost money. I will check costs before using them. Spanner is optional and will only be used if a free trial is available.

## Project status

This is a learning project. I will update this README as I build and test each step.

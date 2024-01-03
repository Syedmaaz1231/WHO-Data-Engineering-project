# WHO-Data-Engineering-project

# WHO Data Transformation and Database Integration: A Data Engineering Project

## Overview

This project involves the extraction, transformation, and loading (ETL) of World Health Organization (WHO) data from CSV files. The data is processed using the Pandas library in Jupyter Notebook, and a relational database is designed and implemented to store the transformed data. The project showcases data engineering skills in handling real-world health statistics and managing database systems.

## Project Highlights

- **Data Extraction**: CSV files from the WHO data repository are downloaded and processed.

- **Data Transformation**: Pandas is utilized to clean, reshape, and manipulate the data for optimal integration into a relational database.

- **Database Design**: A relational database is designed to efficiently store and manage the WHO data. Tables are created to reflect the structure of the information.

- **Data Loading**: The transformed data is loaded into the database, ensuring data integrity and relational consistency.

## Project Structure

|-- WHO_Data_Transformation_and_Database_Integration
|-- data
|-- WHO_data_file1.csv
|-- WHO_data_file2.csv
|-- vWHO_data_file3.csv
|-- notebooks
|-- WHO_Data_Transformation.ipynb
|-- database_scripts
|-- create_tables.sql
|-- load_data.sql
|-- README.md
![WHO PROJECT drawio](https://github.com/Syedmaaz1231/WHO-Data-Engineering-project/assets/109746888/c2522b8d-67b9-423d-b1b4-f341cbd3d7f9)


## Instructions

1. **Data Extraction and Transformation**: Explore the Jupyter Notebook `notebooks/WHO_Data_Transformation.ipynb` for a detailed walkthrough of the data extraction and transformation process.

2. **Database Setup**: Utilize the SQL scripts in `database_scripts/` to create the necessary tables (`create_tables.sql`) and load the transformed data into the database (`load_data.sql`).

3. **Dependencies**: Ensure that you have the necessary dependencies installed.
4. 
4. **Run the Project**: Execute the Jupyter Notebook and SQL scripts to reproduce the data transformation and database integration steps.

## Dependencies

- Python 3.x
- Pandas
- Jupyter Notebook
  


## Acknowledgments

Feel free to contribute and improve this project. If you encounter any issues or have suggestions, please create an issue or submit a pull request.


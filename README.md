- Project description:
The project creates a Postgres Database for a Music Streaming Application name as Sparkify. Thier main purpose is analyzing songs and activities of users what they do the most in app.
With this database schema & ETL pipeline, customer can run querries quickly and correctly.

- ETL Process: 
The processing of the logs and the creation of various tables so that analytical queries may be run on them are covered in this section. Additionally, it explains how the data is extracted and transformed as well as which directories contain specific types of data.

- Project Template: 
The project includes the following files:
1. **create_tables.py:** drops and creates your tables. Running this file to reset tables before each time run ETL scripts.
2. **etl.ipynb:** reads and processes a single file from song_data and log_data and loads the data into tables. This notebook contains detailed instructions on the ETL process for each of the tables.
3. **etl.py:** reads and processes files from song_data and log_data and loads them into tables.
4. **README.md:** Showing how & what I did in this project
5. **schema.png:** A picture describes the project's schema
6. **sql_queries.py:** contains all sql queries, and is imported into the last three files above.
7. **test.ipynb:** displays the first few rows of each table in order to check on the database.
8. **Run.ipynb:** This file was made to execute the "create_tables.py" & "etl.py" file.

- How To Run the Project: 
1. In run_file.ipynb file, input syntax: %run create_tables.py then execute it to create the database and tables.
2. Continue with syntax: %run etl.py to process for loading, extracting and inserting the data.
3. Follow step by step in etl.ipynb file to build the project
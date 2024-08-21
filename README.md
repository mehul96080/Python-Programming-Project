# Python-Programming-Project
Project Summary: Employee Data Processing and Analysis
Overview
The task involved processing employee data from various files in different formats, focusing on JSON data to eventually migrate to a SQL database and perform additional data analysis.

Tasks Completed
File Identification:

Counted the number of files in the directory containing the term "employee" in the file name.
JSON File Processing:

Identified and opened the JSON file among the various formats.
Read and parsed the JSON data to extract details.
Printed all details of the employee with ID 8.
Database Creation and Data Insertion:

Created a SQLite database named data.db.
Established a connection to the SQLite database.
Created an employee table within data.db.
Stored headers (column names) from the JSON data in a separate list.
Converted JSON data into a nested list and inserted it into the employee table.
Data Analysis and Export:

Imported the SQL data into a Pandas DataFrame.
Added a column named "bonus percent," with:
15% bonus for vaccinated employees.
5% bonus for non-vaccinated employees.
Exported the final DataFrame to an Excel file named employee.xlsx.
Deliverables
Database File: data.db
Excel File: employee.xlsx
Important Steps
Reading JSON Data:
Extracted and parsed JSON data to identify employee details.
Storing Column Names:
Collected and stored column names for future reference.
SQLite Operations:
Established connection to SQLite, created table, and inserted data.
Pandas DataFrame Operations:
Imported SQL data, added bonus calculations, and exported results.
Considerations
Ensured overall efficiency of the code.
Used appropriate object names and added comments for clarity.

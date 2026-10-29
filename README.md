This is a python implementation of a job I coded at work. It was originally coded in VBA then converted to powershell which was much better suited to the job.
This python version has extra functionality and uses a dummy data set I created containing fields and types that mirror the data used in powershell.

1. Loads in data. This has been interfaced so their are options
  1.1 Read in a SQL query from file then query postgre to get data
  1.2 Import data from CSV
  1.3 Import data from JSON
2. Group data by client
3. Use specific fields from the data to search a directory to find the payroll folder for each client
4. Save down a csv report for each client in the payroll folder found in 3.

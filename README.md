# Analyzing and Mapping data
Reading Data: The code reads three CSV files (train.csv, ideal.csv, and test.csv) using the Pandas library.

Class Definitions:

Task1: Base class for foundational calculations on the task.
Resultant: Inherits from Task1 and performs calculations to determine the ideal function.
Mapping: Inherits from Resultant and checks key values, deviations, and finds corresponding ideal values. It also creates a DataFrame with the results.
Driver Code:

Initializes four lists (y1, y2, y3, y4) from the training data.
Creates an instance of the Mapping class (mapper) using the training and ideal datasets.
Calls the myDataFrame method to obtain a DataFrame and prints the result.
Database Handling:

Uses SQLAlchemy to create an SQLite database (mapping.db).
Attempts to write the DataFrame to the mapping_table in the database, handling exceptions if the table already exists.

# Data_Cleaning_and_Preprocessing_Netflix_Dataset
Netflix Data Cleaning and Preprocessing
This notebook performs initial data cleaning and preprocessing on the Netflix Movies and TV Shows dataset.

Steps Performed:

Loading Data: The dataset was loaded into a pandas DataFrame.
Initial Inspection: The shape, column names, data types, and the first few rows of the dataset were inspected.
Handling Duplicates: Duplicate rows were removed from the dataset.
Handling Missing Values: Missing values in the 'director', 'cast', 'country', 'date_added', 'rating', and 'duration' columns were handled by filling them with appropriate values ('Not Available', 'Unknown', mode, 'Not Rated', 'Unknown').
Standardizing Column Names: Column names were converted to lowercase, stripped of leading/trailing whitespace, and spaces were replaced with underscores.
Final Check: Nulls and data types were checked after cleaning.

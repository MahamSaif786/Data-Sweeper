# Data-Sweeper
This code is a Streamlit-based web application called Data Sweeper, designed to help users upload, clean, visualize, and convert CSV and Excel files. The app simplifies data transformation and cleaning.

Features:
File Uploading:

Users can upload one or multiple CSV or Excel files.
The app automatically detects the file type.
Data Preview:

Displays the file name and size.
Shows the first 5 rows of the dataset.
Data Cleaning Options:
Remove Duplicates:
Users can remove duplicate rows from the dataset.
Fill Missing Values: Missing values in numerical columns are filled with their mean.

Column Selection:
Users can select specific columns to process.

Data Visualization:
Users can generate a bar chart for the first two numerical columns of the dataset.

File Conversion:
Users can convert CSV to Excel or Excel to CSV.
The converted file can be downloaded directly.

Usage Instructions:
Install Streamlit (if not already installed):
pip install streamlit pandas openpyxl
Save the script as app.py.
Run the app using the terminal or command prompt:
streamlit run app.py

The web interface will open, allowing users to upload, clean, visualize, and convert files easily.
This project uses Python, Pandas, and Streamlit to provide an interactive tool for basic data processing and visualization.









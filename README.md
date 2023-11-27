Attribute Type and Graph Selection App

This Streamlit app allows users to upload three CSV datasets, select attribute types for each column, and then choose graph attributes and types for visualization. The app generates a dashboard with selected options and displays various graphs using Plotly Express.

Instructions:
Upload Datasets:

Click on the "Upload your datasets" section to upload three CSV files.
Ensure that each dataset has relevant column headers.
Select Attribute Types:

For each dataset, choose attribute types from the provided options for every column.
Attribute types include "fixed decimal number," "decimal number," "whole number," "percentage," "date," "date/time," "time," "text," "true/false," and "binary."
Select Graph Attributes and Types:

Choose two attributes from each dataset for graphing.
Select the graph type from options such as "bar," "line," "pie," "scatter," "bubble," "histogram," "heatmap," "box," and "map."
Submit:

Click the "Submit" button to clear the screen, display selected options, and generate a dashboard with visualizations.
How to Run:
Install the required packages:

bash
Copy code
pip install streamlit pandas plotly
Run the Streamlit app:

bash
Copy code
streamlit run your_app_file.py
Replace your_app_file.py with the name of your Python script containing the Streamlit app.

Dependencies:
Streamlit
Pandas
Plotly Express
Sample Usage:
Upload three sample datasets.
Select attribute types for each column.
Choose graph attributes and types.
Click "Submit" to view the dashboard with selected options and visualizations.
Note:
Customize the generate_graph function in your script based on your specific data and visualization requirements.

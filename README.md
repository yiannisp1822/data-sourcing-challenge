# data-sourcing-challenge  
## NASA DONKI Data Analysis  

# Overview  

This notebook fetches and analyzes data on space weather events from NASA’s DONKI (Space Weather Database of Notifications, Knowledge, Information) API. Specifically, it focuses on Coronal Mass Ejections (CMEs) and Geomagnetic Storms (GSTs), aiming to understand the time between CME occurrences and subsequent GST events.  

# Key Features  

1. API Data Retrieval: Connects to NASA’s DONKI API to retrieve CME and GST data within a specified date range.  
2. Data Processing: Converts JSON responses to structured data and merges CME and GST datasets for analysis.  
3. Event Timing Calculation: Computes the time CMEs take to cause GSTs, providing insights into space weather patterns.  

# Requirements  
- Python 3.7+- NASA API Key (saved in a .env file)  


# Usage  

1. Retrieve CME and GST Data: Set date ranges in the notebook and run the data retrieval cells.  
2. Clean up the datasets, removing rows with empty cells and renaiming columns.   
3. Analyze Results: Review tables and calculated time intervals between CME and GST events.  

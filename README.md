## Overview

The Sunspot Data Analysis and Visualization project aims to extract, transform, and load (ETL) historical sunspot data from a CSV file. 

## Project Structure
1. ETL process:
   - Extraction: Loading CSV data into a DataFrame using the Pandas library.
   - Transformation: Clean up the data and calculate additional insights such as logarithmic transformation.
   - Load: Saving the transformed data into a SQLite database for future use.
2. Data analysis:
   - Creating a timestamp to facilitate time series analysis.
   - Use Python libraries such as Pandas and Matplotlib to visualise the data.
   - Apply procedures such as moving averages to smooth the data and identify major trends and patterns.

3. Findings and conclusions:
   - Investigate the trend and cyclicity of sunspot occurrence over time.

## Tools and Libraries Used
- Pandas
- NumPy
- Matplotlib
- SQLAlchemy

## How to Run the Project
1. Preparation:
   - Ensure you have Google Colab access or a local Python environment with the required libraries installed.
2. Execution on Google Colab:
   - Upload your CSV file containing sunspot data into Google Colab.
   - Execute the ETL script provided in your Google Colab environment.
   - Run the analysis script to generate visualizations and insights.
3. Execution Locally:
   - Clone the project repository.
   - Install the required Python libraries via `pip install -r requirements.txt`.
   - Run the Python script using your preferred environment.

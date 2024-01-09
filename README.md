# Data Quality Engineer Challenge

This repository contains the solution to the Data Quality Engineer technical test related to the Spotify API. The challenge consists of two parts: data processing and data quality analysis.

## Part 1: Data Processing

In this part of the challenge, a JSON file named `taylor_swift_spotify.json` is provided, which is processed and transformed into a CSV format called `df_processed.csv`. Python Pandas and JSON libraries are used to perform this task.

### Running the Script

To process the data and generate the `df_processed.csv` file, follow these steps:

1. Make sure you have a Google account to use Google Colab and the Pandas library installed in your development environment.

2. Execute the Python script `process_spotify_data.py` in the terminal:

   ```bash
   python process_spotify_data.py
   
3. The script will process the data and generate the dataset.csv file in the same directory.


## Part 2: Data Quality Analysis

In this part of the challenge, a data quality analysis is performed on the `dataset.csv` file. The goal is to identify and document data anomalies without correcting them. This is done using Python and possibly SQL or other tools as needed.

### Performing the analysis
To perform the data quality analysis, follow these steps:

1. Open the data_quality_analysis.py file in your development environment.

2. Use the necessary libraries and tools to perform the data quality analysis. The source code provided in the file shows how this analysis is approached.

3. Document the data quality anomalies found in the data quality report.

## Data Quality Report

The data quality report can be found in the `data_quality_report.pdf` file. This report includes a description of the data anomalies found and their justification.

## References

- [The Six Primary Dimensions for Data Quality Assessment](link_to_reference)
- [Spotify Web API - Track](link_to_reference)
- [Spotify Web API - Album](link_to_reference)
- [Spotify Web API - Artist](link_to_reference)
- [Spotify Web API - Track Audio Features](link_to_reference)

## Contribution

If you wish to contribute or improve this project, feel free to do so. Open issues or send pull requests to collaborate on enhancing the solution.

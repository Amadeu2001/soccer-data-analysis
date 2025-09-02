# Soccer data analysis

This project demonstrates how to consume data from the Football-Data.org API to obtain information about Premier League matches (ID 2021) in the 2024/2025 season.

Using a Python notebook, requests are made to the API, the received data is processed in JSON format, and the information is organized into a Pandas DataFrame.

### Features

- Consumption of the Football-Data.org API using requests;
- Authentication with X-Auth-Token;
- Conversion of the JSON response to a DataFrame;
- Cleaning of irrelevant columns;
- Date formatting.

### Technologies used

- Python
- Jupyter Notebook
- Main libraries:
  - requests
  - json
  - pandas

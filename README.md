# ETL Crowdfunding Project

### Project Summary

In this ETL (Extract, Transform, Load) mini-project, we had a comprehensive focus on cleaning and transforming a dataset loaded from an Excel spreadsheet. The data was unique in that it included one column featuring JSON-like strings with various pieces of information (contact_id, name, and email).

### Problem Statement

Our main objective was to take contact information from a complicated Excel file and transform it into a clean, straightforward format. We tackled this challenge using two distinct approaches—Pandas and regular expressions—to reach the same outcome. The cleaned-up data was then exported to a CSV file, ready for any subsequent analytics or business intelligence tasks.

### Data Sources

- crowdfunding.xlsx
- contacts.xlsx

_Provided by the course_

### Tools and Technologies

* Python
* Pandas
* Regular Expressions (re)
* Jupyter Notebook
* Excel

### Key steps

1. Extract

   We began the project by importing an Excel file into a Pandas DataFrame. This step was crucial as it served as the foundation for all subsequent transformations. The Excel file contained contact information but was structured in a way that made direct analysis challenging.
1. Transform

   The transformation step was the core of our project. We used regular expressions to parse JSON-like strings from one of the DataFrame's columns, extracting vital fields like contact_id, name, and email. Following the extraction, we further divided the name into first_name and last_name, reordered the columns, and converted data types for easier analysis.
1. Load

   After completing the transformation, we exported the cleaned and restructured data into a new CSV file. This step finalized our ETL process, rendering the data readily accessible for future analytics or business intelligence tasks. The CSV format ensures that the data can be easily imported into various data analysis tools.

### Collaborators
- John Shridik
- Eric Huynh

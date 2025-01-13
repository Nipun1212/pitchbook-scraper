# Pitchbook Scraper


## Overview
This project contains two Jupyter notebooks designed to scrape company details from the PitchBook website. The tool helps users locate the correct company profile and extract key information, including the company name and website. The scraped details are saved in a structured format, such as .xlsx or .csv.

## Features

Company Matching: Identifies possible matches for a given company name.
Detail Extraction: Finds the correct company profile by identifying emails and other attributes.
Data Export: Saves the extracted details in a user-friendly format (Excel/CSV).


## Example Workflow
Input: 
Provide a CSV file containing a list of company names and their respective websites. This file will serve as the base for matching with the company profiles on PitchBook.
Processing:
find_matches.ipynb: The notebook takes the input CSV and identifies possible matches on PitchBook. It filters these matches based on the provided company website to ensure accurate results.
scrape_details.ipynb: This notebook verifies the correct profile by matching additional details like email domains and then scrapes the required information.
Output:
The scraped details, including the company name, website, and other relevant information, are saved in .xlsx or .csv format for further analysis.

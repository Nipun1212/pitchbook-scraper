# Pitchbook Scraper


## Overview
This project contains two Jupyter notebooks designed to scrape company details from the PitchBook website. The tool helps users locate the correct company profile and extract key information, including the company name and website. The scraped details are saved in a structured format, such as .xlsx or .csv.

## Features

<ul>
  <li><strong>Company Matching:</strong> Identifies possible matches for a given company name.</li>
  <li><strong>Detail Extraction:</strong> Finds the correct company profile by identifying emails and other attributes.</li>
  <li>
    <strong>Browser Automation:</strong> Uses Selenium to automate the web browser for scraping, with features like random scrolling and dynamic timeouts to avoid detection as a bot.
  </li>
  <li><strong>Data Export:</strong> Saves the extracted details in a user-friendly format (Excel/CSV).</li>
</ul>



## Example Workflow

<ol>
  <li>
    <strong>Input:</strong> Provide a CSV file containing a list of company names and their respective websites. This file will serve as the base for matching with the company profiles on PitchBook.
  </li>
  <li>
    <strong>Processing:</strong>
    <ul>
      <li>
        <strong>find_matches.ipynb:</strong> The notebook takes the input CSV and identifies possible matches on PitchBook. It filters these matches based on the provided company website to ensure accurate results.
      </li>
      <li>
        <strong>scrape_details.ipynb:</strong> This notebook verifies the correct profile by matching additional details like email domains and then scrapes the required information.
      </li>
    </ul>
  </li>
  <li>
    <strong>Output:</strong>
    <ul>
      <li>The scraped details, including the company name, website, and other relevant information, are saved in <code>.xlsx</code> or <code>.csv</code> format for further analysis.</li>
    </ul>
  </li>
</ol>

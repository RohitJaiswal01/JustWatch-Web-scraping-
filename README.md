# JustWatch Data ETL Project
This repository contains my web scraping project focused on extracting, transforming, and loading (ETL) data from JustWatch. The goal was to scrape movie and TV show information from the JustWatch platform using  BeautifulSoup, and Python, Matplotlib, Seaborn followed by data filtering and analysis with Pandas, and finally exporting the results to a CSV file.
![image](https://github.com/user-attachments/assets/47f825a5-c232-48d4-9732-9840a5b04607)

## Project Description
JustWatch is a popular platform that allows users to search for movies and TV shows across multiple streaming services like Netflix, Amazon Prime, Hulu, etc. This project involved scraping movie and TV show data from JustWatch using HTML extraction methods (rather than APIs), and performing ETL processes to analyze the data.

## Technologies Used
Python: The primary programming language used for scripting.

BeautifulSoup: For parsing HTML content and extracting the required data.

Pandas: For data filtering, analysis, and exporting the results to CSV.

## Tasks Performed
### Web Scraping

Extracted data for movies and TV shows, including:

Movie/TV show title

Release year

Genre

IMDb rating

Available streaming services

URL to the JustWatch page

Scoped to scrape data for at least 50 movies and 50 TV shows, ensuring a diverse dataset.

### Data Filtering & Analysis

Filtered the dataset to include:

Movies and TV shows released in the last 2 years.

IMDb ratings of 7 or higher.

Performed analysis to:

Calculate the average IMDb rating.

Identify the top 5 genres with the most movies and TV shows.

Determine the streaming service with the highest number of offerings.

### Data Export

Exported the filtered and analyzed data to a CSV file for further processing and reporting.

### Submission Details
The repository includes my Python script with clear comments explaining the scraping, filtering, and analysis processes.

The script is error-free and executable in one go.

The dataset CSV file is available in the repository, and its link is shared in the notebook.

### Handling Errors and Best Practices
Properly handled errors and exceptions during web scraping to ensure robustness.

Followed Python best practices to maintain well-structured and easy-to-understand code.

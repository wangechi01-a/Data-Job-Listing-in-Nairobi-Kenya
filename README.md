# Data Jobs listing in Nairobi Kenya from My JobMag Kenya Website

This code is a Python script that uses Selenium to scrape Data jobs in Nairobi, Kenya from a MyJobMag webpage, saves the details to a CSV file, and sends me an email with the job listings. Here's a detailed explanation of each part:

## Overview of the Code Structure
Setup the Chrome WebDriver:

1. setup_driver function: Initializes the Selenium Chrome WebDriver and maximizes the browser window.
Scrape Job Details:

2. scrape_job_details function: Visits the specified URL, locates job cards, extracts job titles, URLs, and posting dates, and compiles this information into a structured format (list of dictionaries).
Save to CSV:

3. save_to_csv function: Converts the list of job details into a Pandas DataFrame and saves it as a CSV file.
Send Email:

4. send_email function: Uses the yagmail library to send an email with the job listings to a specified recipient.
Main Function:

### main function: Orchestrates the overall process by setting up the driver, scraping job details, saving them to a CSV file, preparing the email content, and sending the email.

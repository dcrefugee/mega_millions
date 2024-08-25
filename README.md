# Mega Millions Numbers Check Project

## Project Overview

This Python script automates the process of checking Mega Millions lottery numbers against the latest winning numbers and logs the results. It's designed for lottery enthusiasts who want to streamline their number-checking process and maintain a detailed record of their plays.

## Features

- Fetches the latest Mega Millions winning numbers from the New York Lottery API
- Prompts for user input of chosen numbers with validation
- Compares user numbers to winning numbers
- Provides immediate feedback on matches
- Logs results to a CSV file for future reference

## How It Works

1. The script starts by making a request to the NY Lottery API to fetch the most recent Mega Millions drawing data.
2. It processes the JSON response, extracting the winning numbers and Mega Ball.
3. The user is then prompted to input their five chosen numbers (between 1 and 70) and their Mega Ball number (between 1 and 25). Input validation ensures all numbers are within the correct range and unique where necessary.
4. The script compares the user's numbers to the winning numbers, identifying any matches.
5. Immediate feedback is provided, informing the user of how many numbers they matched and whether they got the Mega Ball correct.
6. Finally, the script logs the results to a CSV file, including the date, winning numbers, user's numbers, matching numbers, and Mega Ball information.

## Technologies Used

- Python
- Pandas: For efficient data handling and processing
- Requests: For fetching data from the NY Lottery API
- CSV module: For logging results to a file

## Setup and Usage

1. Ensure you have Python installed on your system.
2. Install the required libraries: pip install requests pandas
3. Clone this repository or download the script.
4. Run the script: python mega_millions_checker.py
5. 5. Follow the prompts to input your numbers.
6. Check the console output for immediate results and the CSV log file for a record of your plays.

## Future Improvements

- Implement an improved GUI for easier interaction (created using Juypyter Notebook)
- Add historical data analysis features
- Integrate with email or SMS for automated notifications


---

This project demonstrates the practical application of programming skills in a real-world scenario, combining API interaction, data processing, user input handling, and file operations. It's a useful tool for any Mega Millions player looking to automate their number-checking process and maintain detailed records of their lottery participation.


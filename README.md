Bank ETL Project
This project performs ETL (Extract, Transform, Load) operations on a list of the largest banks by market capitalization. The project extracts data from a web page, transforms it by converting market caps to different currencies, and loads the processed data into both a CSV file and a SQLite database.

Project Structure
banks_project.py: The main script for performing ETL operations.
exchange_rate.csv: CSV file containing exchange rates for GBP, EUR, and INR.
code_log.txt: Log file to track the progress of the ETL operations.
Requirements
Python 3.x
pandas
requests
beautifulsoup4
icecream
Installation
Install the required packages using pip:

bash
Copy code
pip install requests beautifulsoup4 pandas icecream
Usage
Run the banks_project.py script:

bash
Copy code
python banks_project.py
License
This project is licensed under the MIT License - see the LICENSE file for details.

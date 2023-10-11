# Mixpanel API Export to CSV and Excel

## Overview
This Python 3.x script fetches data from the Mixpanel API and exports it to both CSV and Excel formats. The script can be run in any environment that supports Python 3.x and the required libraries.

## System Requirements
- Python 3.x
- Operating System: Windows, macOS, or Linux

## Features
- Fetches data between a user-specified date range.
- Exports the data to a CSV file.
- Also exports the data to an Excel file with adjusted column widths.
- Error handling to catch common issues.

## Dependencies
The following Python libraries are used:
- os
- json
- base64
- requests
- pandas
- datetime
- dotenv
- openpyxl

## Setup
1. Clone the repository.
2. Navigate to the project directory.
3. Run `pip install -r requirements.txt` to install dependencies.

### Environmental Variables
Create a `.env` file in the project directory and add the following:
```
MIXPANEL_API_SECRET=your_mixpanel_api_secret_here
```

## Usage
Run the script with `your-file-name.py` and follow the on-screen prompts to input the date range for data fetching.

### Output
- The CSV file will be saved to `/path/to/your/csv/file.csv`
- The Excel file will be saved to `/path/to/your/excel/file.xlsx`

## Troubleshooting
- Ensure you have a `.env` file with the correct Mixpanel API secret.
- Ensure the date format for input is YYYY-MM-DD.

## Credits and Acknowledgements
This project was inspired by various Mixpanel API implementations and aims to make the data fetching and exporting process as seamless as possible.

## Contact Information
For questions, issues, or contributions, please contact via GitHub.

---

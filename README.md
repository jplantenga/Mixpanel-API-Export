# Mixpanel API Export to CSV and Excel

## Overview

This Python 3.x script fetches data from the Mixpanel API and exports it to both CSV and Excel formats. The script can be run in any environment that supports Python 3.x and the required libraries.

### Features

- Fetches data between a user-specified date range.
- Exports the data to a CSV file.
- Also exports the data to an Excel file with adjusted column widths.
- Error handling to catch common issues.

## System Requirements

- Python 3.x
- Operating System: Windows, macOS, or Linux

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

1. **Clone the Repository**

    ```
    git clone https://github.com/your-username/mixpanel-api-export.git
    ```

2. **Navigate to Project Directory**

    ```
    cd mixpanel-api-export
    ```

3. **Install Dependencies**

    ```
    pip install -r requirements.txt
    ```

## Environmental Variables

Create a `.env` file in the project directory and add the following:

```
MIXPANEL_API_SECRET=your_mixpanel_api_secret_here
```

## Configuration

### File Paths

Open the Python script and modify the following lines with the desired paths where the CSV and Excel files will be stored:

```python
csv_file_path = "/path/to/your/csv/file.csv"
excel_file_path = "/path/to/your/excel/file.xlsx"
```

## Usage

Run the script with `your-file-name.py` and follow the on-screen prompts to input the date range for data fetching.

### Output

- The CSV file will be saved to `/path/to/your/csv/file.csv`
- The Excel file will be saved to `/path/to/your/excel/file.xlsx`

## Troubleshooting

- Ensure you have a `.env` file with the correct Mixpanel API secret.
- Ensure the date format for input is YYYY-MM-DD.
- Ensure that you have the right Mixpanel URL Export for EU or USA.
- Use this URL for more information / details: https://developer.mixpanel.com/reference/raw-event-export

## Credits and Acknowledgements

This project was inspired by various Mixpanel API implementations and aims to make the data fetching and exporting process as seamless as possible.

## Contact Information

For questions, issues, or contributions, please contact via GitHub.

---

This README combines the best of both worlds: it keeps the essential elements of your original README while incorporating the additional details and instructions for modifying the Python script.

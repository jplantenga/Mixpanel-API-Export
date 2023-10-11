# Mixpanel API Export

## Description

This Python script fetches and exports data from the Mixpanel API to CSV and Excel formats. It is designed to be easily run from the command line and requires minimal setup.

## Requirements

- Python 3.x
- `requests`
- `pandas`
- `openpyxl`
- `python-dotenv`

## Installation

1. Clone this repository to your local machine.
    ```
    git clone https://github.com/jplantenga/Mixpanel-API-Export.git
    ```
2. Navigate to the cloned directory.
    ```
    cd Mixpanel-API-Export
    ```
3. Install the required Python packages.
    ```
    pip install -r requirements.txt
    ```

## Usage

1. Add your Mixpanel API Secret to a `.env` file in the root directory:
    ```
    MIXPANEL_API_SECRET=your-secret-key
    ```
2. Run the script.
    ```
    python your-file-name.py
    ```

## Features

- Retrieves data between user-specified date ranges.
- Outputs data to CSV and Excel formats.
- Automatically adjusts column widths in the Excel output.

## Contributing

Contributions, issues, and feature requests are welcome!

## License

This project is under the [MIT License](LICENSE).

---

Would you like to proceed with those steps?

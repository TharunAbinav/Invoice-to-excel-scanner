# Invoice Image to Excel Scanner

This Python script allows you to extract data from invoice images and convert it into an Excel spreadsheet. It utilizes the pytesseract library for Optical Character Recognition (OCR) and regular expressions (regex) to locate and extract relevant information from the invoice images.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Dependencies](#dependencies)
- [Sample Invoice](#dependencies)
- [Credits](#credits)
- [License](#license)

## Description

The Invoice Image to Excel Scanner is a powerful tool that can automate the tedious task of manually transcribing data from invoice images into a spreadsheet. By leveraging OCR technology and regex patterns, the script can accurately identify and extract fields such as company name, customer details, phone numbers, email addresses, and payment due dates from the invoice images.

## Features

- Extract data from invoice images in various formats (e.g., PNG, JPG, TIFF)
- Identify and extract company name, customer details, phone numbers, email addresses, and payment due dates
- Convert extracted data into an Excel spreadsheet for easy data manipulation and analysis
- Support for batch processing of multiple invoice images
- Customizable regex patterns to accommodate different invoice formats

## Installation

1. Clone the repository or download the source code.
2. Install the required dependencies (see [Dependencies](#dependencies) section).

## Usage

1. Place the invoice images you want to process in a designated folder.
2. Open the script file in a text editor or an Integrated Development Environment (IDE).
3. Configure the script by updating the following variables:
  - `image_directory`: Set the path to the folder containing the invoice images.
  - `output_file`: Set the desired filename and path for the output Excel file.
4. Run the script.
5. The extracted data will be written to the specified output Excel file.

## Dependencies

This script requires the following dependencies:

- Python 3.x
- pytesseract
- Pillow (Python Imaging Library)
- openpyxl
- re (regular expressions)

You can install the required dependencies using pip

## Sample Invoice

These are the 3 sample invoices i have attached

![alt text](https://github.com/TharunAbinav/Invoice-to-excel-scanner/blob/main/invoice1.png)

## Credits
This project uses the following resources:

- For using the regex keywords from regex library I have used (https://regex101.com/)
-I have attached exaple invoice so you can try or test the code using the provided images from various sources

## License
The Weather Wizard project is licensed under the MIT License.


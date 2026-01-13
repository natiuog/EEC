# Excel File Editor Website

This static website allows you to upload, view, edit, and download Excel files directly in your browser.

## Features

- Pre-loaded with a default Excel file for immediate editing
- Upload Excel files (.xlsx, .xls, .csv formats supported) (optional)
- View Excel data in a table format
- Edit individual cells by clicking and typing
- Switch between different sheets in multi-sheet workbooks
- Add new rows and columns
- Download the modified Excel file

## How to Use

1. Open `index.html` in your web browser
2. A default Excel file will load automatically
3. Edit cells by clicking on them and typing
4. Use the "Add Row" or "Add Column" buttons to expand your spreadsheet
5. Select different sheets using the dropdown menu (you can add more sheets if needed)
6. Click "Download Excel" to save your changes
7. Optionally, you can still upload your own Excel file using the "Choose Excel File" button

## Technical Details

The website uses the SheetJS library (xlsx) to handle Excel file operations entirely in the browser. No server-side processing is required.
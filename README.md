# selenium_automation

This README document explains the functionality of a Selenium WebDriver script designed to automate interactions with the 'Selenium Easy Demo' web page.

## Prerequisites

Before running this script, ensure you have the following installed:

- Python 3
- Selenium WebDriver
- Safari browser (The script is configured for Safari; it can be adapted for other browsers)

## Script Functionality

The script performs the following actions on the 'Selenium Easy Demo' web page:

1. Opens the Safari browser and navigates to the demo page.
2. Verifies that the correct page has been opened by checking the page title.
3. Locates the 'Show Message' button by its class name.
4. Checks if the button text is present in the page source.
5. Finds the user input box, clears any pre-existing text, and enters a custom message.
6. Clicks the 'Show Message' button to display the entered message.
7. Verifies that the entered message is displayed on the page.
8. Waits for 5 seconds before closing the browser to allow for manual verification.

## Script Usage

To run the script, navigate to the directory containing the script file and execute the following command in the terminal:

```bash
python selenium_script.py
```

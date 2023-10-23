# Image-Scrapper

This Python script is designed to scrape images from Google search based on a specified query. It utilizes the Selenium library along with a Chrome WebDriver to automate the process of fetching and downloading images.  

## Installation

To run this script, follow these steps:
  1) Install the required Python packages:
     ```
     pip install selenium pillow requests
     ```
  2)Make sure Google Chrome is installed on your machine.

  3)Check your Google Chrome version: (Go to the three dots menu, then click on Help, and then About Google Chrome).

  4)Download the corresponding Chrome WebDriver from [here](https://chromedriver.storage.googleapis.com/index.html). Make sure to download the version that matches your installed Chrome version.

  5)Place the downloaded Chrome WebDriver executable in the same folder as this script.

## Usage

To use the image scraper, you need to execute the script with the following parameters:
```
python scraper.py
```

Make sure to configure the DRIVER_PATH variable in the script with the correct path to the Chrome WebDriver executable.

## Example
```
DRIVER_PATH = r'chromedriver.exe'
search_term = 'Virat Kohli'
number_images = 10  # Number of images to scrape

search_and_download(search_term=search_term, driver_path=DRIVER_PATH, number_images=number_images)
```

## TroubleShooting

If you encounter any issues while running the script, check the following:

- Ensure that Chrome is installed and its version matches the downloaded Chrome WebDriver.
- Verify that the Chrome WebDriver executable is in the same folder as the script.
- Check your internet connection, as the script relies on web scraping.


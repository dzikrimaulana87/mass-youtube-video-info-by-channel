# YouTube Video Metadata Scraper

This project aims to collect metadata from a YouTube creator's videos and save it into an Excel file. The collected metadata includes interaction count, publication date, and video name.

## Requirements

- Python 3.6 or higher
- Pandas
- Requests
- BeautifulSoup
- Openpyxl

## Installation

1. Clone this repository:
    ```bash
    git clone https://github.com/dzikrimaulana87/Get-Youtube-videos-info-from-channel
    cd Get-Youtube-videos-info-from-channel
    ```

2. Install the required dependencies:
    ```bash
    pip install pandas requests beautifulsoup4 openpyxl
    ```

## Usage

1. Open and run Jupyter Notebook:
    ```bash
    jupyter notebook
    ```

2. Open the `.ipynb` file in Jupyter Notebook.

3. Adjust the `creator` variable to the YouTube username you want to scrape data from:
    ```python
    creator = '@#YOUTUBEUSERNAME'
    ```
    You can customize the information to be retrieved by modifying the `itemprop_list` variable.

4. Run all the cells in the notebook to collect video metadata and save it into an Excel file.

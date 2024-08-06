# Mars Data Analysis Project

## Overview

This project consists of two parts: 
1. Scraping titles and preview text from Mars news articles.
2. Scraping and analyzing Mars weather data from a table.

The main goal of this project is to collect data, organize and store data, analyze it, and visually communicate the insights.

## Files

- `part_1_mars_news.ipynb`: Jupyter Notebook for scraping Mars news articles.
- `part_2_mars_weather.ipynb`: Jupyter Notebook for scraping and analyzing Mars weather data.
- `Module 11 Challenge.pdf`: PDF document containing the detailed instructions for the challenge.

## Deliverables

### Deliverable 1: Scrape Titles and Preview Text from Mars News

1. **Automated browsing**: Uses Splinter to visit the Mars news site.
2. **HTML Extraction**: Creates a Beautiful Soup object to extract text elements.
3. **Data Storage**: Stores the titles and preview texts in a list of dictionaries, with each dictionary containing `title` and `preview` keys.
4. **Optional Data Export**: Optionally exports the scraped data to a JSON file.

### Deliverable 2: Scrape and Analyze Mars Weather Data

1. **Automated browsing**: Uses Splinter to visit the Mars Temperature Data Site.
2. **HTML Table Extraction**: Creates a Beautiful Soup object to scrape the data from the HTML table.
3. **DataFrame Assembly**: Assembles the scraped data into a Pandas DataFrame with appropriate column headings.
4. **Data Type Examination**: Examines and converts data types as necessary.
5. **Data Analysis**: Answers the following questions using Pandas functions:
   - How many months exist on Mars?
   - How many Martian days worth of data exist in the dataset?
   - Which months have the lowest and highest temperatures on Mars?
   - Which months have the lowest and highest atmospheric pressure on Mars?
   - How many terrestrial days exist in a Martian year?
6. **Data Export**: Exports the DataFrame to a CSV file.

## Setup and Installation

1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <repository-directory>
    ```

2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:
    ```bash
    pip install -r requirements.txt
    ```

4. Run the Jupyter Notebooks:
    ```bash
    jupyter notebook
    ```

## Usage

- Open `part_1_mars_news.ipynb` and run the cells to scrape the Mars news articles.
- Open `part_2_mars_weather.ipynb` and run the cells to scrape and analyze the Mars weather data.

## Data Sources

- [Mars News](https://static.bc-edx.com/data/web/mars_news/index.html)
- [Mars Weather Data](https://static.bc-edx.com/data/web/mars_facts/temperature.html)

## Credits

This project is part of the Module 11 Challenge for the Data Analytics Bootcamp provided by edX Boot Camps LLC.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.


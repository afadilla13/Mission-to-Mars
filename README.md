# Mars Data Scraping and Analysis

This repository provides a comprehensive guide to scraping and analyzing Mars data from two distinct sources: Mars News and Mars Temperature Data. The project involves using web scraping techniques to gather relevant information, followed by data analysis and visualization.

## Table of Contents
- [Introduction](#introduction)
- [Project Parts](#project-parts)
- [Getting Started](#getting-started)
- [Data Analysis](#data-analysis)
- [Visualization](#visualization)
- [Notebooks](#notebooks)
- [Contributing](#contributing)
- [License](#license)

## Introduction
In this project, we explore the fascinating realm of Mars by collecting and analyzing data from various sources. Through web scraping and data analysis, we aim to gain insights into Mars News and Mars Temperature Data, shedding light on different aspects of the Red Planet.

## Project Parts
This project consists of two main parts:

### Part 1: Mars News
- Open `part_1_mars_news.ipynb`.
- Utilize automated browsing techniques to access Mars News website and identify scraping targets.
- Create a Beautiful Soup object to extract titles and preview text.
- Organize data into Python dictionaries within a list.
- Optional: Export collected data to a JSON file.

### Part 2: Mars Weather Data
- Open `part_2_mars_weather.ipynb`.
- Scrape Mars Temperature Data using Beautiful Soup or Pandas.
- Structure data into a Pandas DataFrame with well-defined columns.
- Conduct insightful data analysis, including:
  - Determining the number of Mars months
  - Calculating Martian days' worth of data
  - Identifying the coldest and warmest months
  - Finding the months with the lowest and highest atmospheric pressure
  - Estimating the number of terrestrial days in a Martian year.
- Visualize analysis results through informative bar charts.
- Export the cleaned DataFrame to a CSV file.

## Getting Started
To replicate or build upon this project, follow these steps:

1. Clone this repository: `git clone https://github.com/your-username/mars-data-analysis.git`
2. Install the required dependencies: `pip install -r requirements.txt`
3. Open and explore the provided Jupyter Notebook files in the `notebooks` directory.

## Data Analysis
Our data analysis process uncovers valuable insights into Mars, including statistical trends and patterns. The analysis includes metrics such as the duration of a Martian day, temperature fluctuations, and atmospheric pressure variations.

## Visualization
We enhance data interpretation through visualization. The generated bar charts help to illustrate trends and differences, making the analysis more accessible and engaging.

## Notebooks
For detailed step-by-step instructions and code, refer to the Jupyter Notebook files in this repository's `notebooks` directory.

- [part_1_mars_news.ipynb](notebooks/part_1_mars_news.ipynb)
- [part_2_mars_weather.ipynb](notebooks/part_2_mars_weather.ipynb)

## Contributing
Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to submit a pull request.

## License
This project is licensed under the [MIT License](LICENSE).

Happy data exploration on Mars!

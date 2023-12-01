# PitStop Analytics: Formula 1 Data Insights

## Introduction
Welcome to the F1 Data Explorer, a comprehensive toolkit for Formula 1 enthusiasts and data analysts. This project consists of a set of Python scripts designed to scrape, analyze, and present data from the world of Formula 1 racing. Dive into race results, driver statistics, and team performances across various seasons with ease.

## Features
- **Data Scraping**: Automated scripts to fetch and store F1 race information from the official Formula 1 website.
- **Personal Analysis**: Tools to analyze driver names and performances, leveraging the Levenshtein distance algorithm for name matching.
- **Race Information Compilation**: Scripts to parse and structure race information into readable and analyzable formats.
- **Data Storage**: Well-defined text files to store structured data for further analysis or database insertion.
- **Versatility**: Ability to process data for specific races, years, or drivers based on user input.

## Repository Contents
- `README.md`: The file you are currently reading.
- `linkedlist.py`: A custom implementation of a linked list, potentially used for data handling (details not provided in the provided context).
- `personal_analysis.py`: A script for performing personal analyses of driver names and related statistics.
- `raceInfo.py`: A script dedicated to extracting and compiling race-specific information.
- `race_info.txt`: A text file that contains structured race information extracted by `raceInfo.py`.
- `scrape.py`: The main scraping script that fetches data from the Formula 1 website.
- `sqlData.txt`: A text file intended to store data in a format suitable for SQL database ingestion.
- `year_data.txt`: A text file with aggregated data on drivers, teams, and points across different years.

## How to Use
1. Ensure Python 3.x is installed on your system.
2. Install required Python libraries: `requests`, `numpy`, and `bs4`.
3. Run `scrape.py` to begin scraping data for the desired year(s).
4. Use `raceInfo.py` to extract detailed race information for further analysis.
5. Execute `personal_analysis.py` to find and analyze specific driver statistics based on name similarity.

## Contributing
Contributions to the F1 Data Explorer are welcome. Whether it's refining the scraping algorithms, expanding the data analysis capabilities, or improving documentation, your input is valuable.

## Feedback
If you encounter any issues or have suggestions, please open an issue in the GitHub repository.

## License
The F1 Data Explorer is open-sourced under the MIT license.

---

Embark on your journey through the thrilling races and fascinating data of Formula 1 with the F1 Data Explorer!

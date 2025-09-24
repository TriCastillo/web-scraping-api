# Web Scraping & APIs: Billboard and YouTube Top Charts

## Table of Contents

- [Scenario and Problem Statement](#scenario-and-problem-statement)
- [Dataset Description](#dataset-description)
- [Actions and Approach](#actions-and-approach)
- [Screenshots and Examples](#screenshots-and-examples)
- [Technologies Used](#technologies-used)
- [Project Structure](#project-structure)
- [Results and Insights](#results-and-insights)
- [Future Work](#future-work)
- [Acknowledgement](#acknowledgement)
- [Contact Information](#contact-information)

## Scenario and Problem Statement

This project demonstrates how to collect, process, and analyze trending music data from two major platforms: Billboard and YouTube. The goal is to automate the extraction of top chart data, store it in structured datasets, and enable further analysis for insights into global music trends.

## Dataset Description

- **billboard_top_charts.csv**: Contains the top songs and artists from the Billboard Hot 100 chart.
- **youtube_top_charts.csv**: Contains the most popular music videos on YouTube, including title, channel, and video link.

## Actions and Approach

1. **Web Scraping Billboard**: Uses BeautifulSoup and requests to extract song titles and artists from the Billboard Hot 100 chart.
2. **YouTube API Integration**: Uses the YouTube Data API v3 to fetch the most popular music videos, including metadata and links.
3. **Data Storage**: Saves the extracted data into CSV files for easy access and analysis.
4. **Notebook Documentation**: All code and workflow are documented in a Jupyter notebook for reproducibility.

## Screenshots and Examples

- Example output from Billboard scraping:
  ```
    Track 1:
    Title: Golden
    Artist: HUNTR/X: EJAE, Audrey Nuna & REI AMI
  ```
- Example output from YouTube API:
  ```
    Song 1:
    Title: Cardi B - Don't Do Too Much [Official Audio]
    Channel: Cardi B
    Link: https://www.youtube.com/watch?v=5-ueehJsBUI
  ```
- See the `notebooks/Web_Scraping_&_APIs.ipynb` for full code and outputs.

## Technologies Used

- Python
- Jupyter Notebook
- BeautifulSoup
- requests
- YouTube Data API v3
- pandas (recommended for further analysis)

## Project Structure

```
README.md
notebooks/
		Web_Scraping_&_APIs.ipynb
data/
		billboard_top_charts.csv
		youtube_top_charts.csv
```

## Results and Insights

- Successfully automated the collection of top chart data from Billboard and YouTube.
- Created structured datasets for further analysis and visualization.
- Demonstrated the use of web scraping and API integration in a real-world scenario.

## Future Work

- Add data visualization and trend analysis using pandas and plotly.
- Expand to other music platforms (e.g., Spotify, Apple Music).
- Schedule regular updates and automate data refresh.
- Enhance error handling and logging.

## Acknowledgement

- Billboard (https://www.billboard.com)
- YouTube Data API (https://developers.google.com/youtube/v3)
- Open-source Python libraries: BeautifulSoup, requests

## Contact Information

- Author: Reynaldo III Castillo
- Email: reynaldoiii.castillo@gmail.com
- LinkedIn: [Reynaldo III Castillo](https://www.linkedin.com/in/reynaldo-iii-castillo-975120303)
- GitHub: TriCastillo

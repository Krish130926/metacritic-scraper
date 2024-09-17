Metacritic New Album Releases Scraper

## Description
This Python project scrapes the latest album releases from [Metacritic](https://www.metacritic.com/browse/albums/release-date/available/metascore) and extracts valuable data such as album titles, artists, release dates, metascores, and user scores. The goal is to provide an overview of the top 10 recently released albums along with their user and critic ratings. 

The project also visualizes user scores using a bar chart and computes basic analytics, such as average metascores and user scores, to help users quickly assess the popularity of recent music albums.

Website Chosen
The project uses **Metacritic** as its source for album data because it aggregates scores from both critics and users, making it a trusted and popular platform for music reviews. The data is highly relevant for users looking to discover the latest music releases with detailed feedback from a broad audience.

Features
- Scrape the latest 10 albums with details including title, artist, release date, metascore, user score, and summary.
- Visualize user scores of the top albums using a bar chart.
- Analyze the average metascore and user score of the top albums.
- Rate-limiting implemented to prevent overwhelming the server.

- How to Run

Clone the Repository
bash


Install Requirements
Ensure you have Python installed. Then, install the required Python libraries.
pip install -r requirements.txt

Run the Scraper
Execute the scraper by running the Python script:
python scraper.py



Additional Notes:
1.	requirements.txt File: Make sure your requirements.txt includes:
requests
beautifulsoup4
matplotlib

File Structure:

├── README.md
├── ETHICS.md
├── requirements.txt
├── scraper.py
└── example_plot.png  # Optional: an example visualization if needed










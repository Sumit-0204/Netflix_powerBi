# Netflix Data Dashboard (Power BI)

This project is an interactive dashboard built using Power BI that visualizes key metrics and trends from Netflix's global content catalog. It provides insights into content distribution by type, genre, country, and release year, along with runtime and IMDb ratings.

![Netflix Dashboard Screenshot](https://github.com/Sumit-0204/Netflix_powerBi/blob/main/Untitled.png)

## Overview

This dashboard answers the following questions:

- What types of content dominate Netflix's library?
- Which countries produce the most content?
- What are the top genres in Netflix's catalog?
- How has Netflix's content grown or changed over the years?

## Dataset

- Source: Kaggle – Netflix Movies and TV Shows Dataset  
  https://www.kaggle.com/datasets/shivamb/netflix-shows
- Key Columns Used: Title, Type, Genre, Country, Date Added, Release Year, Rating, Duration, IMDb Rating

## Key Visuals and Metrics

- KPI Cards:
  - Runtime (Hours): 7513
  - Total Content: 5806
  - Movies: 3759
  - Shows: 2047
  - Average IMDb Rating: 5.94

- Top 5 Genres:
  - Bar chart comparing content count between Movies and Shows for popular genres

- Country Map:
  - Bubble map showing content distribution across countries

- Content by Year:
  - Line chart showing growth trends from 2000 to 2023

- Total Content by Type:
  - Donut chart showing that 65% of the content are Movies, and 35% are Shows

- Filters/Slicers:
  - Genre
  - Title
  - Release Year

## Insights

- Movies make up the majority of Netflix's content.
- The United States, India, and the UK are the top content producers.
- Drama and Comedy are the most frequent genres.
- Netflix saw major content growth after 2015, with a peak around 2019–2020.
- A slight decline is observed in new content additions post-2021.

## Tools Used

- Power BI Desktop
- Power Query for data transformation
- DAX for calculated measures
- Bing Maps visual for geographic distribution

## How to Use

1. Download the `Netflix Data.pbix` file from this repository.
2. Open it using Power BI Desktop.
3. Use the filters to explore the data based on genre, title, and year.
4. Hover over visuals to explore dynamic insights.

## Future Enhancements

- Add external ratings data from IMDb or Rotten Tomatoes
- Integrate subscriber or viewing statistics (if available)
- Enable drill-through pages for deeper genre or country analysis


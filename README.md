# Netflix Dashboard

This repository contains a Tableau dashboard visualizing Netflix content data, providing insights into the streaming platform's library composition and trends.

## Overview

The dashboard presents a comprehensive analysis of Netflix's content library, including movies and TV shows distribution, geographical presence, ratings, and genre popularity. The visualization showcases data through multiple interconnected views that allow for interactive exploration.

## Dashboard Components

### Content Details
The top section displays information about specific content, including:
- Type
- Title 
- Date Added 
- Release Year 
- Duration 
- Rating 
- Description 
- Genre 

### Global Distribution
A world map visualization showing the total number of movies and TV shows by country, with the United States (2,032) having the highest content count, followed by India and other regions.

### Content Ratings
Bar chart displaying the distribution of content ratings, with TV-MA and TV-14 being the most common ratings.

### Content Type Distribution
Pie chart showing the distribution between movies (4,265, 68.42%) and TV shows (1,969, 31.58%).

### Top 10 Genres
Horizontal bar chart displaying the most popular genres on Netflix:
1. Documentaries (299)
2. Stand-Up Comedy (273)
3. Dramas, International Movies (248)
4. Dramas, Independent Movies, International Movies (186)
5. Comedies, Dramas, International Movies (174)
6. Kids' TV (159)
7. Documentaries, International Movies (150)
8. Children & Family Movies, Comedies (129)
9. Comedies, International Movies (120)
10. Children & Family Movies (120)

### Content Growth Over Time
Area chart showing the growth of Netflix's content library from 2007 to 2021, with separate areas for movies and TV shows, demonstrating significant growth particularly from 2015 onward.

## Installation and Usage

1. Clone this repository
2. Open the .twbx file with Tableau Desktop or Tableau Reader
3. Interact with the dashboard by:
   - Hovering over data points for detailed information
   - Using filters to explore specific content categories
   - Clicking on map regions to see country-specific content

## Data Source

This dashboard uses Netflix content data including release dates, content types, ratings, genres, and geographical distribution.

## Technologies Used

- Tableau Desktop for visualization creation
- Data preprocessing tools for data cleaning and preparation

## Future Improvements

- Add streaming metrics and viewership data
- Incorporate content recommendation analysis
- Create additional visualizations for content performance metrics
- Add time-based filters for temporal analysis


## References
- [Youtube Video](https://www.youtube.com/watch?v=BTArwS4ljC4&list=PL7RSbI9s6KhgovdILZ-lIpW-LTkduE-ll&index=1)
- [View Dashboard on Tableau Public](https://public.tableau.com/app/profile/datascience.roadmap/viz/Netflix_16791909068940/Netflix)
- [Dataset Source](https://github.com/DataScienceRoadMapDSRM/Tableau-Dashboards-info/blob/main/netflix_titles.csv)


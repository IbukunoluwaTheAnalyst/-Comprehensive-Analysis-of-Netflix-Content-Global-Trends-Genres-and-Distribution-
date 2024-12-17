# Comprehensive-Analysis-of-Netflix-Content-Global-Trends-Genres-and-Distribution
![8b514d341909dca0c6bbb9d20d742dab](https://github.com/user-attachments/assets/fbc35650-b03b-44fc-ab20-a01e574c3dd6)

# Introduction

Netflix – the undisputed king of streaming! Once just a humble DVD rental service, Netflix has evolved into a global entertainment powerhouse that revolutionized how we consume movies and TV shows. If you’ve ever spent hours scrolling through endless titles only to re-watch Friends or Stranger Things for the tenth time, you’re not alone. That’s the magic (and curse) of Netflix – it gives us too many options, and we still can’t decide!

With its sleek red-and-black logo and “Ta-dum” intro sound, Netflix has become a household name. It offers something for everyone: heart-pounding thrillers, tear-jerking dramas, laugh-out-loud comedies, and even the occasional oddball documentary (yes, we all watched the Tiger King saga in 2020). Whether you’re a fan of crime dramas, romantic comedies, or the latest stand-up specials, Netflix has made it almost impossible to leave your couch.

Behind the scenes, Netflix isn’t just about binging—it’s also a treasure trove of fascinating data. From genre trends to global contributions, its content catalog reflects the world’s changing tastes in entertainment. So, grab some popcorn, settle in, and let’s dive into the world of Netflix to explore what makes it so binge-worthy!

# Overview

This project focuses on analyzing and visualizing Netflix’s content catalog using Power BI. The dashboard highlights key metrics such as the number of movies and TV shows, genres, release years, directors, and global content distribution. It also explores trends in total duration.

# Research Questions

Content Variety: What is the distribution of Movies vs. TV Shows on Netflix?

Genre Insights: What are the most popular genres based on the total number of shows and movies?

Regional Analysis: Which countries contribute the most content to Netflix’s catalog?

Temporal Trends: How has the release of movies evolved over the years?

Duration Trends: How has the total runtime of movies changed between 2000 and 2024?

Director Analysis: Who are the most prolific directors in Netflix’s catalog?

# Use case
An analysis like this can bridges the gap between data and entertainment, offering something valuable to both industry professionals and entertainment enthusiasts.

# Analysis Process
Data Analysis requires a structured approach to ensure accurate and actionable insights. This process involves several key stages, each critical to the successful interpretation of available information. The methodology employed in this instance comprised the following steps:
# 1. Data Gathering/Collection
Introduction to the Dataset

The dataset used for this project was obtained from The Movie Database (TMDb), focusing specifically on Netflix Movies and TV Shows. Using Python and the BeautifulSoup library for web scraping, combined with the TMDb API key, I extracted detailed information about Netflix’s content catalog. This approach allowed me to gather comprehensive and up-to-date data on a variety of attributes for each title.
![code snippet](https://github.com/user-attachments/assets/e322200b-5d42-4b29-81c5-a21ee7a38fef)
**Code Snippet for Extraction**

Data Attributes Extracted

1. Show ID: A unique identifier for each title.

2. Type: Specifies whether the content is a Movie or TV Show.

3. Title: The name of the show or movie.

4. Director: The director(s) of the movie or TV show.

5. Cast: Leading actors and actresses featured in the content.

6. Country: The country where the show or movie was produced.

7. Date Added: The date when the title was added to Netflix’s catalog.

8. Release Year: The year the content was originally released.

9. Rating: The content rating (e.g., PG, R, TV-MA) indicating its suitability for different audiences.

10. Duration: The runtime for Movies (in minutes) or the number of Seasons for TV Shows.

11. Listed in: Genres or categories the content falls under, such as Drama, Comedy, or Thriller.

12. Description: A short synopsis or overview of the content.

![WhatsApp Image 2024-12-17 at 14 34 35_9a2a5c05](https://github.com/user-attachments/assets/6551ad6d-1de6-475d-9805-9dae5cd300a8)
**A picture showing the extraced data**

# 2. Data Preparation

Handled missing values for columns like Director, Cast, and Country.

Create calculated fields:
Year Added: Extract the year from the Date Added column.
Duration in Minutes: Convert Duration into numerical values for Movies.

# 3. Data Modeling
Create relationships between relevant columns for better analysis.

# 4. Dashboard Visualization
For Visualization, i exported the dataset in csv file to PowerBI and i created a dashboard for better display and for further explanation on the analysis.
![Netflix dashboard_page-0001](https://github.com/user-attachments/assets/746625f7-dfcc-494a-9d78-4712b062a480)

# Communication and Interpretation

The Netflix Dashboard, built using data extracted from The Movie Database (TMDb), provides an interactive and visually engaging analysis of Netflix’s content catalog. The dataset includes attributes like type, title, director, cast, country, genres, release year, duration, and ratings, offering a comprehensive view of Netflix’s offerings.

Key insights include the dominance of movies over TV shows, with genres like Drama, Comedy, and Thriller leading in popularity. A geographic analysis highlights the United States as the top content contributor, followed by countries like India and the UK, emphasizing Netflix’s global diversity. Release year trends reveal a surge in recent additions, reflecting Netflix’s aggressive expansion. Duration analysis shows most movies fall within the 90–120 minute range, while TV Shows typically have 1–3 seasons. Rating trends indicate Netflix caters to audiences of all ages, with a significant portion targeting mature viewers.

Interactive visuals, such as pie charts, bar graphs, and maps, make the dashboard easy to navigate. Filters for genre, country, and year enhance user engagement. The dashboard serves multiple purposes, from helping Netflix refine its content strategy to guiding competitors, academic researchers, and entertainment enthusiasts. By turning raw data into actionable insights, the project demonstrates the power of analytics in the streaming industry.














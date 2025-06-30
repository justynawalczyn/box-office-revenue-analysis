# Box Office Revenue Insights

This project is a  data analysis of box office performance, enriched with IMDb and OMDb metadata. It includes data cleaning, enrichment, data modeling (star schema), SQL querying, visualizations, and an interactive dashboard.

##  Project Overview

-  **Goal**: Discover revenue trends, top-rated movies, and distributor performance using real-world movie data.
-  **Stack**: Python, Pandas, SQLite, Looker Studio, Jupyter Notebook
-  **Database**: Star schema designed in SQLite
-  **Visualization**: Interactive dashboard (Google Looker Studio)

##  Key Features

- Cleaned and enriched box office data
- Connected OMDb API for movie metadata (IMDB rating, awards, runtime)
- Designed and implemented **dimensional star schema** in SQLite
- Built an **interactive dashboard** with trends
- Highlighted top distributors, genres, and high-performing movies

## Project Structure

 box-office-revenue-insights/
├── box_office_analysis.ipynb # Jupyter Notebook
├── enriched_revenue_data.csv # Final enriched dataset (to download here: https://drive.google.com/drive/folders/1FUdUkno2Ea71GFw0A40pQyTUGSvxQE3E?usp=drive_link)
├── revenues_per_day.csv # Original box office data (to download here: https://drive.google.com/drive/folders/1FUdUkno2Ea71GFw0A40pQyTUGSvxQE3E?usp=drive_link)
├── ERD.pdf # Entity-Relationship Diagram
├── dashboard.pdf # Screenshot of Looker Studio dashboard
└── README.md # This file

# Spotify_analytics_dashboard
🎵 Spotify Data Analytics Dashboard
This project is an end-to-end data analysis project using Power BI. The dashboard provides a comprehensive analysis of Spotify's streaming data, offering insights into artist popularity, album types, and song characteristics.
The UI is designed with a dark-mode aesthetic to mimic the actual Spotify application, providing a familiar and intuitive user experience.

🔍 Key Insights & KPIs
Based on the dataset analyzed, here are the top-level metrics:
Total Distinct Songs: 789
Total Artists: 342
Average Song Duration: 3.28 Minutes
Average Popularity Score: 90/100

📈 Visualizations & Features
The dashboard includes the following analytical visuals:
Artist Analysis: A ranking of top artists (e.g., Taylor Swift, Travis Scott) based on the number of songs and popularity.
Song Performance: A breakdown of top tracks (e.g., "Cruel Summer", "As It Was") by streams/popularity.
Distribution Metrics:
Album vs. Single: Analysis of song releases by type (269 Singles vs. 562 Album tracks).
Explicit vs. Non-Explicit: Content rating distribution.
Temporal Trends:
Songs by Year: Comparison of releases between 2023 and 2024.
Popularity Trends: Monthly average popularity showing seasonal peaks (with a dip in October/November).
Quarterly Analysis: Distinct song releases broken down by Q1–Q4.
Interactive Player UI: A custom-designed central visual showcasing the currently selected track (featuring "1989 Taylor's Version") with dynamic album art.

🛠️ Technical Workflow
Data Extraction: Dataset obtained from [Kaggle / Spotify API / Excel].
Data Cleaning (Power Query):
Removed null values and duplicates.
Standardized artist names and song titles.
Created conditional columns for "Explicit" content flags.
Data Modeling: Established relationships between Song Tables, Artist Tables, and Calendar Tables (Star Schema).
DAX Calculations: Created measures for:
Average Popularity
Distinct Song Count
Dynamic Titles
UI/UX Design: Used canvas background design, transparency, and overlay techniques to replicate the Spotify "Glassmorphism" look.

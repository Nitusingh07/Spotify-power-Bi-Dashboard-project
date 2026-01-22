🎵 Spotify Power BI Dashboard Project

Analyze Music Trends, Top Artists & Listening Insights

This project is a professionally designed Spotify Power BI Dashboard that helps analyze music trends, top artists, track performance, and listener preferences using real-world Spotify data. It is ideal for students, data analysts, and professionals who want to showcase their Power BI and data analytics skills through an interactive and insightful project.

🚀 Project Overview

The Spotify Power BI Dashboard enables users to:
- Explore global music trends over time
- Identify top artists and popular tracks
- Analyze audio features such as energy, danceability, tempo, and valence
- Gain meaningful insights using interactive and dynamic visualizations

This project is ready-to-use and suitable for portfolio building and learning advanced Power BI techniques.

🎧 Key Features of the Spotify Power BI Dashboard

🔹 Modular Dashboard Design
The dashboard is structured into multiple clean and interactive modules:
- Top Artists by Popularity — view the most popular artists worldwide ranked by popularity index.
- Track Analysis — analyze song-level metrics such as popularity, duration, and explicit content.
- Genre Distribution — visual breakdown of different genres to understand audience preferences.
- Audio Features Dashboard — analyze key Spotify audio metrics (danceability, energy, acousticness, valence, tempo, instrumentalness).
- Album Insights — compare album types, release dates, track counts, and popularity.
- Trend Analysis — understand how music trends evolve over time using interactive charts.

🔍 Dynamic Filtering Options
- Filter songs by year of release, artist, or genre
- Slice data based on popularity range or audio features
- Switch between track-level and artist-level views for deeper analysis

📊 Advanced Visualizations
- Fully interactive charts and graphs powered by Power BI
- Key KPIs including Top 10 Artists, Most Streamed Songs, Popular Genres, Energy Levels
- Use of bar charts, line charts, and heatmaps to identify influential music patterns

🧭 User-Friendly Navigation
- Separate pages for Artists, Tracks, Genres, and Audio Features
- Clean layouts with minimal design for professional presentation
- Easy navigation for both technical and non-technical users

👥 Who Is This Project For?
- Students & Learners — practice Power BI with real-world Spotify data and strengthen your portfolio.
- Data Analysts & Professionals — add a unique music analytics dashboard to your professional projects.
- Music Enthusiasts — explore music trends and insights using data-driven visualizations.

📚 Additional Learning Resources
Every user can learn from the included guidance on:
- Key Spotify KPIs and metrics explained
- Tips to customize filters and visuals for personal projects
- How to showcase this dashboard on LinkedIn, GitHub, or resumes

🎯 Why Choose This Project?
- Real-world Spotify dataset with advanced audio metrics
- End-to-end Power BI dashboard design
- Strong portfolio-ready project for interviews and job applications
- Combines data analytics + music insights in a unique way

🛠 Tools & Technologies Used
- Power BI
- Spotify Dataset
- DAX
- Data Modeling & Visualization

---

How to open and reproduce

1. Install Power BI Desktop (latest stable release).
2. Open `DASHBOARD/spotify dashboard.pbix` in Power BI Desktop.
3. If rebuilding from CSV: `Get data → Text/CSV` → select `Cleaned data/spotify-top-50-world.csv`.
4. In Power Query:
   - Parse `date` and `release_date` as Date type.
   - Ensure `position` and `popularity` are numeric.
   - Clean `artist` or `genre` fields as needed; add `Week`/`Month` columns for aggregation.
5. Close & Apply, then `Refresh` to update visuals after CSV changes.

Recommended measures to create (DAX)
- AvgPosition = AVERAGE(Table[position])
- Appearances = COUNTROWS(Table)
- DistinctSongs = DISTINCTCOUNT(Table[song])

Exporting & Sharing

- Export report pages as images or PDF via `File → Export`.
- Publish to Power BI Service if you have an account and want to share online.

Notes

- Dataset: `Cleaned data/spotify-top-50-world.csv` contains daily top-50 snapshots. Columns include `date`, `position`, `song`, `artist`, `popularity`, `duration_ms`, `album_type`, `total_tracks`, `release_date`, `is_explicit`, `album_cover_url`.
- Keep album cover URLs if you want image tiles in Power BI.
- See `LICENSE` for repository licensing.

Want more?

I can: add page-level documentation for the PBIX, create sample DAX measures, or export sample screenshots for the README. Tell me which you'd prefer next.
🎵 Spotify Power BI Dashboard Project
Analyze Music Trends, Top Artists & Listening Insights
This project is a professionally designed Spotify Power BI Dashboard that helps analyze music trends, top artists, track performance, and listener preferences using real-world Spotify data.
It is ideal for students, data analysts, and professionals who want to showcase their Power BI and data analytics skills through an interactive and insightful project.
🚀 Project Overview
The Spotify Power BI Dashboard enables users to:
Explore global music trends over time
Identify top artists and popular tracks
Analyze audio features such as energy, danceability, tempo, and valence
Gain meaningful insights using interactive and dynamic visualizations
This project is ready-to-use and suitable for portfolio building and learning advanced Power BI techniques.
🎧 Key Features of the Spotify Power BI Dashboard
🔹 Modular Dashboard Design
The dashboard is structured into multiple clean and interactive modules:
Top Artists by Popularity
View the most popular artists worldwide ranked by popularity index.
Track Analysis
Analyze song-level metrics such as popularity, duration, and explicit content.
Genre Distribution
Visual breakdown of different genres to understand audience preferences.
Audio Features Dashboard
Analyze key Spotify audio metrics:
Danceability
Energy
Acousticness
Valence


Tempo
Instrumentalness
Album Insights
Compare album types, release dates, track counts, and popularity.
Trend Analysis
Understand how music trends evolve over time using interactive charts.
🔍 Dynamic Filtering Options
The dashboard supports advanced and flexible filtering:
Filter songs by year of release, artist, or genre
Slice data based on popularity range or audio features
Switch between track-level and artist-level views for deeper analysis
📊 Advanced Visualizations
Fully interactive charts and graphs powered by Power BI
Key KPIs including:
Top 10 Artists
Most Streamed Songs
Popular Genres
Energy Levels
Use of bar charts, line charts, and heatmaps to identify influential music patterns
🧭 User-Friendly Navigation
Separate pages for:
Artists
Tracks
Genres
Audio Features
Clean layouts with minimal design for professional presentation
Easy navigation for both technical and non-technical users
👥 Who Is This Project For?
Students & Learners
Practice Power BI with real-world Spotify data and strengthen your portfolio.
Data Analysts & Professionals
Add a unique music analytics dashboard to your professional projects.
Music Enthusiasts
Explore music trends and insights using data-driven visualizations.
📚 Additional Learning Resources
Every user can learn from the included guidance on:
Key Spotify KPIs and metrics explained
Tips to customize filters and visuals for personal projects
How to showcase this dashboard on LinkedIn, GitHub, or resumes
🎯 Why Choose This Project?
Real-world Spotify dataset with advanced audio metrics
End-to-end Power BI dashboard design
Strong portfolio-ready project for interviews and job applications
Combines data analytics + music insights in a unique way
🛠 Tools & Technologies Used
Power BI
Spotify Dataset
DAX
Data Modeling & Visualization
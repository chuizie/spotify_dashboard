🎧 Spotify 2023 Music Visualization Dashboard

An interactive data visualization dashboard built with ECharts + HTML, based on the Spotify 2023 Kaggle dataset.
The dashboard presents insights into global music trends through popularity distribution, emotional landscape, tempo structure, and multidimensional audio feature profiling.

🚀 Features

✔ Top 20 Most Streamed Tracks

A ranked bar chart of the top 20 songs by streams. Clicking a track automatically opens its radar chart.

✔ Emotional Space (Valence × Energy)

A scatter plot that maps each song's emotional position—
Valence (sad → happy) on the x-axis and Energy on the y-axis, with color encoding danceability.

✔ Tempo Structure (BPM × Energy)

Analyzes the relationship between tempo (BPM), energy, danceability, and streams.

✔ Audio Feature Radar Chart

Compares individual track features against the global average, covering:
Danceability · Valence · Energy · Acousticness · Instrumentalness · Liveness · Speechiness

📂 Project Structure
project/
│── spotify_dashboard.html     # Main dashboard interface
│── spotify-2023.csv           # Dataset (must be placed in the same directory)

🖥 How to Run

Make sure spotify_dashboard.html and spotify-2023.csv are in the same folder.

1️⃣ Open a terminal or PowerShell and navigate to the folder
2️⃣ Start a local HTTP server:
python -m http.server 8000

3️⃣ Open the dashboard in a browser:
http://localhost:8000/spotify_dashboard.html

📊 Dataset Source

Kaggle: Spotify 2023 Dataset

Contains metadata and audio features for popular tracks, including:
Streams, Danceability, Valence, Energy, BPM, Acousticness, etc.

✨ Highlights

Clean, modern, Spotify-inspired UI

Fully interactive charts with tooltips and dynamic updates

Multi-tab layout: Overview / Emotion / Tempo / Radar

Radar chart with enhanced chip-style track info display

Responsive design that works across screen sizes

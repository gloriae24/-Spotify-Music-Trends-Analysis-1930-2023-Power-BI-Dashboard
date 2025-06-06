
# 🎵 Spotify Music Trends Analysis (1930–2023) | Power BI Dashboard

This project presents a **Power BI dashboard** built on a dataset of songs released between **1930 and 2023**, offering insights into streaming behavior, release trends, and audio characteristics across platforms like **Spotify**, **Apple Music**, **Deezer**, and **Shazam**.

---

## 📊 Dashboard Highlights

This interactive Power BI dashboard provides the following insights:

* 📈 **Total Tracks and Streams** released from 1930 to 2023
* �� **Average Streams per Track**
* 🗓️ **Average Track Releases by Month** to uncover popular release periods
* 🥇 **Top Most Streamed Track**
* 🏆 **Top 5 Most Streamed Tracks** (ranked visually)
* 🔍 Exploration of audio features or music info:

  * Danceability
  * Energy
  * Acousticness
  * Instrumentalness
  * Valence
  * Speechiness
  * BPM, Key, Mode
* 🔄 Platform cross-analysis:

  * Number of times tracks appeared in **Spotify, Apple, Deezer, Shazam Charts & Playlists**

---

## 📾 Dataset Overview

The dataset contains the following columns:

| Column Name            | Description                                    |
| ---------------------- | ---------------------------------------------- |
| `track_name`           | Name of the song                               |
| `artist(s)_name`       | Name(s) of the performing artist(s)            |
| `artist_count`         | Number of artists featured                     |
| `released_year`        | Year of release                                |
| `released_month`       | Month of release                               |
| `released_day`         | Day of release                                 |
| `in_spotify_playlists` | Count of Spotify playlists featuring the track |
| `in_spotify_charts`    | Presence in Spotify charts                     |
| `streams`              | Total number of streams                        |
| `in_apple_playlists`   | Count of Apple Music playlists                 |
| `in_apple_charts`      | Presence in Apple Music charts                 |
| `in_deezer_playlists`  | Count of Deezer playlists                      |
| `in_deezer_charts`     | Presence in Deezer charts                      |
| `in_shazam_charts`     | Presence in Shazam charts                      |
| `bpm`                  | Beats per minute (tempo)                       |
| `key`                  | Musical key (e.g., C, D, E)                    |
| `mode`                 | Major or minor mode                            |
| `danceability_%`       | Danceability score (percentage)                |
| `valence_%`            | Mood/happiness score (percentage)              |
| `energy_%`             | Energy level (percentage)                      |
| `acousticness_%`       | Acoustic value (percentage)                    |
| `instrumentalness_%`   | Instrumental score (percentage)                |
| `liveness_%`           | Live performance score (percentage)            |
| `speechiness_%`        | Spoken word content score (percentage)         |
| `cover_url`            | Link to album or track cover image             |

---

## 📁 Repository Structure

```
Spotify-Music-Analysis/
│
├── 📊 Spotify_Music_Analysis.pbix        # Power BI Dashboard file
├── 📄 README.md                          # Project documentation
├── 📂 data/
│   └── spotify_tracks_1930_2023.csv      # Dataset used for analysis
├── 📂 images/
│   ├── dashboard_full_view.png           # Screenshot of full dashboard
│   └── top_streamed_tracks.png           # Visualization of top 5 tracks
```

---

## 🧪 Analysis & Methodology

1. **Data Cleaning**

   * Removed duplicates and missing values
   * Formatted date columns (year, month, day)
   * Converted percentage columns to numeric formats
   * Validated stream counts

2. **Feature Engineering**

   * Created KPIs: Total Streams, Total Tracks, Average Streams
   * Extracted temporal data for release trend analysis
   * Added platform engagement indicators (chart & playlist appearances)

3. **Dashboard Design**

   * Used **KPI cards**, **bar charts**, and **line graphs** for visuals
   * Implemented **slicers** for interactive filtering by year, artist, or platform
   * Developed **audio feature profiles** using radial and stacked visuals

---

## 📷 Sample Visuals

### 💼 Dashboard Overview

![Dashboard Full View](images/dashboard_full_view.png)

### 🔝 Top Streamed Tracks

![Top Tracks](images/top_streamed_tracks.png)

---

## 🛠 Tools Used

* 📊 **Power BI** – Data modeling, visualization, and dashboard creation
* 📁 **CSV** – Raw dataset for import
* 🖊 **DAX** – Calculated columns and measures
* 🧹 **Power Query** – Data cleaning and transformation

---

## 💡 Insights Discovered

* The **most streamed track** from 1930–2023 had over **X million streams**
* **June and November** saw higher track release activity on average
* Songs with high **danceability** and **energy** values tend to have more streams
* Majority of charting tracks appeared more on **Spotify** than other platforms
* Rise in multi-artist collaborations in recent years (using `artist_count`)

---

## 🔄 Future Enhancements

* Integrate real-time Spotify API data
* Add genre-based breakdowns and visualizations
* Cluster tracks using audio feature similarity
* Include lyric sentiment analysis for emotion classification

---

## 📅 How to Use This Project

1. Download or clone this repository
2. Open the `.pbix` file with **Power BI Desktop**
3. Explore the visuals, filter insights, or add your own analysis
4. Use the dataset to build additional charts or reports

---

## 👤 Author

**Gloria Obianuju Egesi**
🎓 Data Analyst & Visualization Enthusiast
📧 \[Your Email Address]
🔗 \[Your LinkedIn / Portfolio / Medium Profile]

---

## 📜 License

This project is released under the [MIT License](LICENSE). You may use or modify it for educational or non-commercial purposes with credit.

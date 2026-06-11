# Spotify Tracks Exploratory Data Analysis 

This project is a comprehensive, data-driven Exploratory Data Analysis (EDA) pipeline designed to uncover patterns, user preferences, and correlations within Spotify's audio feature architecture. It analyzes how individual song attributes like acousticness, danceability, and energy influence overall track popularity and stream distributions.

---

## Key Insights
* **Energy and Loudness Link:** Discovered a strong positive correlation between a track's energy and its loudness, reflecting modern mainstream production and mastering trends.
* **The Popularity Threshold:** Identified that tracks with higher danceability scores tend to cluster heavily in the top 15% popularity bracket, indicating clear audience behavior trends.
* **Emotional Shift:** Long-term data signals a slight downward trend in valence over the years, showing an evolution toward moodier audio profiles in mainstream music.

---

## Dataset and Audio Features
The analysis evaluates thousands of Spotify tracks across key behavioral and digital signal processing metrics defined by the Spotify Web API:

* **Acoustics and Energy:** Acousticness, Energy, Loudness (dB), and Instrumentalness.
* **Rhythm and Sentiment:** Danceability, Tempo (BPM), Liveness, and Valence (the musical positiveness of a track).
* **Metadata:** Popularity score (ranging from 0 to 100) and track duration.

---

## Tech Stack and Libraries
* **Language:** Python
* **Data Manipulation:** Pandas and NumPy
* **Statistical Visualization:** Matplotlib and Seaborn
* **Environment:** Jupyter Notebook

---

## Pipeline and Execution Steps

### 1. Data Cleaning and Integrity Checks
* Standardized column data types and checked for missing value metrics across the entire dataset.
* Cleaned out duplicate tracks while preserving unique statistical occurrences.
* Converted track duration from milliseconds to minutes to improve readability and analysis.

### 2. Univariate and Distribution Analysis
* Visualized structural distributions of individual audio features using histograms and Kernel Density Estimate plots.
* Observed significant left-skewness in danceability metrics and heavy right-skewness in speechiness.

### 3. Bivariate and Multivariate Analysis
* Generated a Pearson Correlation Heatmap to isolate tightly linked musical variables.
* Built scatter plots and joint distribution graphs to map the explicit relationships between a song's structural energy and its commercial popularity score.

---

## Summary and Takeaway
This exploratory analysis shows how streaming metrics align directly with modern audio characteristics. By isolating specific audio feature profiles, we can mathematically highlight which structural variables give a track the highest probability of breaking into mainstream viral playlists.

---
Maintained and documented by Gayatri

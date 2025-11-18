# 🎧 Project Spotlight: Spotify Music Analysis Dashboard

This dashboard provides a comprehensive visual analysis of how different music genres compare in commercial success (Popularity) and technical audio features (Energy, Danceability, Acousticness). It strategically combines bar charts and a scatter plot to highlight meaningful patterns across the music catalog.

## 🔗 Live Dashboard

Explore the full interactive dashboard here:

> **[Spotify Music Analysis Dashboard](https://public.tableau.com/app/profile/zeshan.asif/viz/spotify_17634786987220/Dashboard1)**

---

## 📈 Key Analysis & Visualizations

The dashboard is divided into two primary sections for feature comparison and relationship analysis:

### 📊 Popularity by Genre (Top Charts)

The top section displays comparative bar charts showing the average scores per genre for:

* **Instrumentalness:** Measures the degree to which a track lacks vocals.
* **Acousticness:** Measures how acoustic (vs. electronic/synthesized) the music is.
* **Popularity:** The core metric of listener engagement (plays, saves, and ranking).

**Key Insights:**

* **Instrumental Focus:** Genres such as **Classical, Jazz, and Soundtrack** display consistently higher **Instrumentalness**.
* **Acoustic/Electronic Divide:** **Folk** and **Acapella** genres show high **Acousticness**, while **Electronic-focused genres** exhibit low Acousticness but high popularity.
* **Commercial Success:** **Pop, Rap, and Hip-Hop** genres score highest in overall **Popularity**, confirming current market trends.

### 🎶 Energy vs Danceability (Scatter Plot)

The bottom **Scatter Plot** is used to analyze the **correlation** between two key rhythmic features:

* **Avg. Energy** (x-axis)
* **Avg. Danceability** (y-axis)

**Observations (Clustering):**

| Cluster | Energy | Danceability | Genres Included |
| :--- | :--- | :--- | :--- |
| **High Activity** | High | High | **Reggaeton, Dance, Electronic, Pop** |
| **Moderate Tempo** | Moderate | Moderate | **Jazz, Soul, R&B** |
| **Low Activity** | Low | Low | **Classical, Opera, Soundtrack** |
| **Unique Feature** | High | Moderate | **Rock and Country** (High energy but moderate danceability) |

---

## ⭐ Overall Summary

This dashboard acts as a powerful tool to illustrate:

* How technical musical characteristics cluster by genre type.
* Which genres attract the highest listener engagement and popularity.
* The relationship between musical drive (Energy) and rhythmic suitability (Danceability).

**Useful for:** Music recommendation systems, playlist curation, and streaming platform content strategy.

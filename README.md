# 🎵 Gaana Music Data Analysis

This project focuses on **data cleaning, exploratory data analysis (EDA), and visualization**
of a music dataset inspired by the Gaana music platform.

The goal of this analysis is to understand **language distribution, artist dominance,
song duration trends, and collaboration patterns** in the dataset.

---

## 📂 Dataset Overview

- Total Songs: **41,355**
- Total Columns: **6**

### Columns:
- `name` – Song name  
- `singer` – Artist(s) name  
- `singer_id` – Artist identifier  
- `duration` – Song duration in `mm:ss` format  
- `link` – Song URL  
- `language` – Language of the song  

---

## 🧹 Data Cleaning

The following steps were performed:
- Checked for missing values (none found)
- Removed duplicate songs based on song name and singer
- Converted song duration from `mm:ss` to seconds
- Created a numerical column `duration_in_secs` for analysis

---

## 📊 Exploratory Data Analysis & Visualizations

### 1. Language Distribution
- Bar chart showing the most common languages
- Helps identify regional content focus

### 2. Artist Analysis
- Top singers based on number of songs
- Highlights artist dominance on the platform

### 3. Song Duration Analysis
- Histogram of song durations
- Most songs fall within the 3–6 minute range

### 4. Average Duration by Language
- Comparison of average song length across languages

### 5. Collaboration Analysis
- Analysis of single-artist vs multi-artist songs
- Majority of songs are solo performances

---

## 🚫 Why Heatmaps Were Not Used

Heatmaps are typically used for correlation analysis between multiple numerical variables.
Since this dataset mainly contains categorical features and only one numerical attribute,
heatmap visualization was not applicable.

---

## 🛠️ Tools Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

---

## 📈 Conclusion

The analysis provides insights into music catalog trends such as dominant languages,
frequently featured artists, and standard song durations.  
These insights can help music platforms optimize content strategy and playlist curation.



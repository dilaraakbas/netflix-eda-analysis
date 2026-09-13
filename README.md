# 🎬 Netflix Movies & TV Shows: Exploratory Data Analysis (EDA)

An end-to-end exploratory data analysis and visual storytelling project investigating Netflix's global content library, growth trajectories, format distributions, and regional production strategies.

---

## 📌 Executive Summary
This project analyzes the Netflix Movies and TV Shows dataset to uncover strategic shifts in content cataloging. By transforming raw, unstructured text metrics into structured numerical and temporal variables, the analysis highlights post-2000 production surges, movie duration optimizations, and localized regional scaling across international markets.

---

## 🛠️ Tech Stack & Methods
* **Language:** Python 3.x
* **Core Libraries:** Pandas, NumPy, Matplotlib, Seaborn
* **Techniques:** Missing value imputation, string parsing & type coercion (`to_numeric`), temporal feature engineering (`datetime`), categorical explosion (`explode`), frequency crosstabs, and aesthetic visualization standardization.

---

## 🔍 Key Findings & Business Insights

### 1. Production Velocity (Post-2000 Focus)
* Content additions escalated sharply after 2015.
* Feature films peaked aggressively between 2017 and 2019, followed by a stabilized trajectory.
* Multi-episode series maintained sustained momentum into the late 2010s, underscoring a strategic shift toward subscriber retention through episodic engagement.

### 2. Duration & Binge-Watching Trends
* **Films:** Durations exhibit a normal distribution centered around a median of ~95–100 minutes, aligning with industry viewer attention standards.
* **Series:** The overwhelming majority of TV shows consist of a single season, reflecting both the popularity of limited-run mini-series and competitive first-season renewal thresholds.

### 3. Geographic & Genre Diversification
* While the **United States** leads overall catalog volume, **India** ranks second, highlighting significant investments in regional localizations.
* **International Movies**, **Dramas**, and **Comedies** represent the core foundation of the platform's content library.

### 4. Release Scheduling Mechanics
* Content additions peak decisively on **Fridays** and **Thursdays**, designed to capture weekend streaming windows.
* Monthly cadence reaches peak concentrations in **July** and **December**, correlating with seasonal leisure periods and holiday viewing demand.

---

## 🚀 Getting Started

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/dilaraakbas/netflix-eda-analysis.git](https://github.com/dilaraakbas/netflix-eda-analysis.git)
   cd netflix-eda-analysis
